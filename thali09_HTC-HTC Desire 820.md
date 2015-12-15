#### Test 50650278654db8c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1551): handler message = 4011
E/HtcModeClient( 1551): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 1551): Don't start project servcice
D/HtcModeClient( 1551): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1551): connectState: CONNECTION_READY = false
D/SilentMusic( 1551): call stop
D/HtcModeClient( 1551): close connection
W/HtcModeClient( 1551): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 1551): read the terminate packet, so break
D/Process (  910): killProcessQuiet, pid=1551
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
--------- beginning of /dev/log/system
I/ActivityManager(  910): Killing 1551:com.htc.bgp/u0a14 (adj 15): empty #17
I/ActivityManager(  910): Recipient 1551
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils-trace( 3888): Error opening trace file: No such file or directory (2)
I/ActivityManager(  910): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3897 uid=10078 gids={50078}
D/PMS     (  910): acquireWL(41d6c3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10078}
V/AlarmManager(  910): sending alarm PendingIntent{42554788: PendingIntentRecord{42548e08 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450201652061, Int=60000
D/PMS     (  910): releaseWL(41d6c3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
D/SMSBackup( 3897): SMSBackupAgentService started
D/SMSBackup( 3897): Checking restore status
D/SMSBackup( 3897): Restore complete
D/SMSBackup( 3897): cancelCheckAlarm
D/SMSBackup( 3897): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  910): killProcessQuiet, pid=3690
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
I/ActivityManager(  910): Killing 3690:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 3690
D/WifiService(  910): Client connection lost with reason: 4
D/CustomizationManager( 3888): ====startRecUseTime====
D/htc.customization.log.level( 3888):  is 
W/CustomizationLogLevel( 3888): Level value is invalid, use default level 2
D/CustomizationManager( 3888):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3888): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3888): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3888): Parsing tag category name = system
I/CustomizationCIDLoader( 3888): Parsing tag category name = application
I/CustomizationCIDLoader( 3888): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3888): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3888): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3888): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3888): Parsing tag category name = Settings
D/CustomizationManager( 3888):  Read CID file spent 0.101 (s)
D/CustomizationManager( 3888):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 3888): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3888): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3888): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3888): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3888
D/PMS     (  910): acquireHCC(4236c2d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(422cfdd8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x6a251f90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1112076800
I/FeedHostManager( 1254): [onPause]
I/FeedProviderManager( 1254): onPause
I/FeedHostManager( 1254): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f94b00
D/PMS     (  910): acquireWL(42417440): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/SocialFeedProvider( 1254): +onPause
I/SocialFeedProvider( 1254): -onPause
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3912 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1254): [trimMemory] 20
W/asset   ( 3912): Copying FileAsset 0x5d85e428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3912): Binding Chromium to main looper Looper (main, tid 1) {41ac9900}
I/LibraryLoader( 3912): Expected native library version number "",actual native library version number ""
I/chromium( 3912): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3912): Initializing chromium process, renderers=0
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420080b0:true
D/PMS     (  910): acquireWL(421b54f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  910): acquireWL(420e44f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  910): releaseWL(421b54f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3912): 1101934144: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3912): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3912): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3912): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3912): Local Branch: 
I/Adreno-EGL( 3912): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3912): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3912):                  aa63bbd948f41d15fc72f585e
W/chromium( 3912): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3912): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3912): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3912): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3912): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3912): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3912): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3912): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3912): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3912): CordovaWebView is running on device made by: HTC
,W/AwContents( 3912): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  910): Disable input method client, pid=1254
W/ResourceType( 3912): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3912): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b143c8, mServedView=org.apache.cordova.engine.SystemWebView{41ada158 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 3912): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  910): Enable input method client, pid=3912
I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +289ms
W/XT9_C   ( 1191): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1191): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1191): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1191): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  910): releaseWL(42417440): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/PMS     (  910): acquireWL(4228c138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10074}
V/AlarmManager(  910): sending alarm PendingIntent{42308fc0: PendingIntentRecord{440a9f50 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450201652779, Int=0
D/PMS     (  910): releaseWL(4228c138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/JsMessageQueue( 3912): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3912): JniHelper::setJavaVM(0x415a2048), pthread_self() = 1662402696
D/JX-Cordova( 3912): jxcore cordova android initializing
V/LightsService(  910): setLight #0: color=#25
V/LightsService(  910): setLight #0: color=#22
V/LightsService(  910): setLight #0: color=#1b
D/Finsky  ( 3623): [377] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3623): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
V/LightsService(  910): setLight #0: color=#14
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 11.577MB for 96598-byte allocation
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 11.661MB for 144892-byte allocation
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 11.755MB for 217334-byte allocation
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 11.928MB for 325996-byte allocation
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 12.202MB for 488990-byte allocation
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 13.211MB for 1100216-byte allocation
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 14.122MB for 1650320-byte allocation
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 15.508MB for 2475476-byte allocation
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
,D/PMS     (  910): releaseHCC(4236c2d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(422cfdd8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3912): Grow heap (frag case) to 17.590MB for 3713210-byte allocation
,W/jxcore-log( 3912): Initializing JXcore engine
,W/jxcore-log( 3912): JXcore engine is ready
,W/jxcore-log( 3912): Starting JXcore engine
,W/jxcore-log( 3912): Platform android
W/jxcore-log( 3912): 
,W/jxcore-log( 3912): Process ARCH arm
W/jxcore-log( 3912): 
,D/PMS     (  910): releaseWL(420e44f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3912): JXcore Cordova bridge is ready!
I/jxcore-log( 3912): 
,W/jxcore-log( 3912): JXcore engine is started
,I/chromium( 3912): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3912): Toggling radios to true
I/jxcore-log( 3912): 
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  910): checking for enable restriction...
,D/BluetoothManagerService(  910): checkBTEasState, ret=true
I/BluetoothManagerService(  910): isBluetoothRestricted(): false
,D/BluetoothManagerService(  910): enable(): region ID = 6
,D/BluetoothManagerService(  910): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  910): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 1
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
,W/Settings:Agent(  910): Process.myTid(): 1361
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
,W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  910): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  910): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  910): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3912): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
D/WifiService(  910): New client listening to asynchronous messages
D/WifiService(  910): setWifiEnabled: true pid=3912, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1242
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
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
,W/Settings:Agent(  910): << traceCallingStack(): 6(ms)
I/ActivityManager(  910): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3958 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3912): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/PMS     (  910): acquireWL(44060198): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiManager( 3912): reconnect: Base Package Name=com.test.thalitest, uid=10389
I/jxcore-log( 3912): Radios toggled
I/jxcore-log( 3912): 
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3912): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3912): 
I/jxcore-log( 3912): Perf Test app loaded loaded
I/jxcore-log( 3912): 
I/Choreographer( 3912): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3912): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3912): check test folder
I/jxcore-log( 3912): 
,I/jxcore-log( 3912): found test : ./testFindPeers.js
I/jxcore-log( 3912): 
,D/AdapterServiceConfig( 3958): Adding HeadsetService
D/AdapterServiceConfig( 3958): Adding A2dpService
D/AdapterServiceConfig( 3958): Adding HidService
D/AdapterServiceConfig( 3958): Adding HealthService
D/AdapterServiceConfig( 3958): Adding PanService
,D/AdapterServiceConfig( 3958): Adding GattService
,W/linker  ( 3958): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/jxcore-log( 3912): found test : ./testSendData.js
I/jxcore-log( 3912): 
,D/BluetoothAdapterService( 3958): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
,W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424d0cc8:true
D/BluetoothAdapterState( 3958): make
I/BluetoothAdapterState( 3958): Entering OffState
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3958): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  910): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  910): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  910): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapter( 1203): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41d00d30
D/BluetoothAdapter( 1203): onBluetoothServiceUp done
D/BluetoothAdapter( 3958): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41ae5d18
D/BluetoothAdapter( 3958): onBluetoothServiceUp done
D/BluetoothAdapter( 1109): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41af93d0
D/BluetoothAdapter( 1109): onBluetoothServiceUp done
D/BluetoothAdapter(  910): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@424df710
D/BluetoothAdapter(  910): onBluetoothServiceUp done
,D/BluetoothAdapter( 1222): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41d410d0
,D/BluetoothAdapter( 1222): onBluetoothServiceUp done
D/BluetoothAdapter( 3912): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@426067a8
D/BluetoothAdapter( 3912): onBluetoothServiceUp done
D/BluetoothAdapter( 1237): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bff088
D/BluetoothAdapter( 1237): onBluetoothServiceUp done
,D/BluetoothManagerService(  910): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3958): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3958): Setting state to 11
I/BluetoothAdapterState( 3958): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3958): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  910): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  910): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3958): make
,I/IntentController( 1109): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3958): StableState(): Entering Off State
D/PMS     (  910): acquireWL(43ae1a60): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1203 10029 null
,D/HeadsetService( 3958): Received start request. Starting profile...
D/HeadsetStateMachine( 3958): Version 1.6
,D/HeadsetStateMachine( 3958): make
D/PMS     (  910): releaseWL(43ae1a60): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3984 uid=10040 gids={50040, 3002, 3001}
,I/HeadsetStateMachine( 3958): setCurrentDevice, the latest mCurrentDevice is:null
,I/BluetoothAdapterState( 3958): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/QuickSettingBluetooth( 1109): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpService( 3958): Received start request. Starting profile...
V/Avrcp   ( 3958): make
,D/Avrcp   ( 3958): fillIntentFilter()
,D/A2dpStateMachine( 3958): make
,D/A2dpStateMachine( 3958): Enter Disconnected: -2
,D/HidService( 3958): Received start request. Starting profile...
,D/HealthService( 3958): Received start request. Starting profile...
,D/PanService( 3958): Received start request. Starting profile...
,D/BluetoothTethering(  910): supplyMessenger
,D/BluetoothTethering(  910): supplyMessenger mAsyncChannel is null
D/HtcBtWidget_BTWidgetProvider( 3984): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3984): updateWidget(context) for widget: 
D/BluetoothTethering(  910): got MESSAGE_CONNECT_PANSERVICE, call connect
,D/BluetoothTethering(  910): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 3958): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/Process (  910): killProcessQuiet, pid=3384
,I/ActivityManager(  910): Killing 3384:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/BtGatt.DebugUtils( 3958): handleDebugAction() action=null
D/BtGatt.GattService( 3958): Received start request. Starting profile...
D/BtGatt.GattService( 3958): start()
V/BluetoothPbapService( 3958): Pbap Service onCreate
V/BluetoothPbapService( 3958): Starting PBAP service
D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 11
D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 11
E/BluetoothMasService( 3958): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3958): Add permission for SmsProvider.
V/BluetoothMasService( 3958): Starting MAS instances
D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 11
I/MailMessageReceiver( 3958): reg:com.android.bluetooth.btservice.AdapterApp@41ad9280 with com.htc.util.mail.MailMessageReceiver@41b19648
I/MailManager( 3958): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b19648
V/EmailUtils( 3958): Manager Instance is not NULL
,I/ActivityManager(  910): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=4002 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  910): interfaceAdded wlan0
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Tethering(  910): wlan0 is not a tetherable iface, ignoring
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Tethering(  910): interfaceAdded p2p0
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Tethering(  910): p2p0 is not a tetherable iface, ignoring
D/libc    (  910): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  910): releaseWL(44060198): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
D/Tethering(  910): interfaceStatusChanged p2p0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,I/ActivityManager(  910): Recipient 3384
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  910): Client com.google.android.music (pid 3384): Died!
,I/wpa_supplicant( 4017): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4017): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4017): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4017): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4017): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4017): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4017): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4017): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4017): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4017): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4017): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4017): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4017): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4017): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4017): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4017): update_config=1
D/wpa_supplicant( 4017): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4017): device_name='Android_1950'
D/wpa_supplicant( 4017): manufacturer='HTC'
D/wpa_supplicant( 4017): model_name='HTC_PHONE'
D/wpa_supplicant( 4017): model_number='1234'
D/wpa_supplicant( 4017): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4017): p2p_oper_reg_class=126
D/wpa_supplicant( 4017): p2p_oper_channel=36
D/wpa_supplicant( 4017): p2p_ssid_postfix='-Android_1950'
,D/wpa_supplicant( 4017): persistent_reconnect=1
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 3
D/EmailUtils( 3958): ============NULL aList========
V/EmailUtils( 3958): <-getEmailAccountIdList
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 3
V/BluetoothMasService( 3958): onCreate: mIsEmailEnabled: true
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4017): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4017): nl80211: RFKILL status not available
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4017): nl80211: Using driver-based roaming
D/wpa_supplicant( 4017): nl80211: TDLS supported
D/wpa_supplicant( 4017): nl80211: TDLS external setup
D/wpa_supplicant( 4017): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4017): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4017): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4017): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4017): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4017): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4017): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4017): nl80211: Subscribe to mgmt frames with non-AP handle 0xb74b2758
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74b2758
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4017): htc_wext_command_init +
E/wpa_supplicant( 4017): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4017): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4017): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4017): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4017): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4017): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4017): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4017): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4017): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
,D/Tethering(  910): interfaceStatusChanged p2p0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
D/Tethering(  910): interfaceStatusChanged p2p0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 11
V/BluetoothMasService( 3958): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3958): Manager Instance is not NULL
D/EmailUtils( 3958): ============NULL aList========
V/EmailUtils( 3958): <-getEmailAccountIdList
D/HeadsetPhoneState( 3958): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/BluetoothSapService( 3958): Sap Service onCreate
V/BluetoothSapService( 3958): initBinder
V/BluetoothSapService( 3958): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b1fec8
V/BluetoothSapReceiver( 3958): BluetoothSapReceiver init
D/BluetoothSapService( 3958): setSapService()
V/BluetoothSapService( 3958): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3958): state: 12
D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 11
D/BluetoothAdapterService( 3958): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3958): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3958): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3958): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 3958): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothTethering(  910): got CMD_CHANNEL_FULLY_CONNECTED
D/BluetoothAdapterService( 3958): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterState( 3958): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/Process (  910): killProcessQuiet, pid=3367
I/ActivityManager(  910): Killing 3367:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/BluetoothMasReceiver( 3958): Bluetooth STATE CHANGED to 11
,I/qcom-bluetooth( 4022): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  910): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4023 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4040): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4041): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4023): Received state change = 11
D/WifiMonitor(  910): startMonitoring(wlan0) with mConnected = false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  910): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/qcom-bluetooth( 4043): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/IntentController( 1109): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/qcom-bluetooth( 4044): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/WIFI_ICON( 1109): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/qcom-bluetooth( 4045): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4046): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/ActivityManager(  910): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4047 uid=10050 gids={50050}
,D/WifiService(  910): New client listening to asynchronous messages
I/ActivityManager(  910): Recipient 3367
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=3555
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1340): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  910): Killing 3555:com.google.android.talk/u0a111 (adj 15): empty #17
,I/QuickSettingWifi( 1109): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/HtcWiFiWidget_WiFiWidgetProvider( 4047): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4047): updateWidget(context) for widget: 
,D/Process (  910): killProcessQuiet, pid=3729
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  910): Killing 3729:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3729
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 4017): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4017):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4017):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4017):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4017): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4017): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4017): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4017): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4017): nl80211: Flush PMKIDs
E/wpa_supplicant( 4017): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4017): State: DISCONNECTED -> INACTIVE
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 3555
,D/wpa_supplicant( 4017): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4017): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4017): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4017): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4017): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4017): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): Using existing control interface directory.
D/wpa_supplicant( 4017): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4017): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4017): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4017): P2P: Own listen channel: 1
D/wpa_supplicant( 4017): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4017): P2P: Add operating class 81
I/wpa_supplicant( 4017): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4017): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4017): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4017): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4017): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4017): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4017): disable_scan_offload=1
D/wpa_supplicant( 4017): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4017): update_config=1
D/wpa_supplicant( 4017): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4017): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4017): manufacturer='HTC'
D/wpa_supplicant( 4017): model_name='HTC Desire 820'
D/wpa_supplicant( 4017): model_number='HTC Desire 820'
D/wpa_supplicant( 4017): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4017): persistent_reconnect=1
D/wpa_supplicant( 4017): p2p_disabled=1
D/wpa_supplicant( 4017): hs20=1
D/wpa_supplicant( 4017): interworking=1
D/wpa_supplicant( 4017): Line: 18 - start of a new network block
D/wpa_supplicant( 4017): key_mgmt: 0x2
D/wpa_supplicant( 4017): priority=1 (0x1)
,D/wpa_supplicant( 4017): signinfail=0 (0x0)
,I/qcom-bluetooth( 4062): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4063): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3958): btu_task pending for preload complete event
,D/wpa_supplicant( 4017): Priority group 1
D/wpa_supplicant( 4017):    id=0 ssid='NG700'
I/wpa_supplicant( 4017): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4017): nl80211: RFKILL status not available
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4017): nl80211: Using driver-based roaming
D/wpa_supplicant( 4017): nl80211: TDLS supported
D/wpa_supplicant( 4017): nl80211: TDLS external setup
D/wpa_supplicant( 4017): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4017): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4017): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4017): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4017): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4017): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4017): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4017): nl80211: Subscribe to mgmt frames with non-AP handle 0xb74c2718
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4017): htc_wext_command_init +
I/wpa_supplicant( 4017): htc_wext_command_init -
I/wpa_supplicant( 4017): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4017): Don't set 00 to countryID.conf
D/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4017): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4017): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4017): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4017): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4017): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4017): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4017): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4017): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 4017): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4017):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4017):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4017):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4017): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4017): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4017): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4017): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4017): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4017): send_and_recv error -22 - cmd 54,
,D/wpa_supplicant( 4017): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4017): TDLS: Driver uses external link setup
D/wpa_supplicant( 4017): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4017): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4017): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4017): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4017): Using existing control interface directory.
I/wpa_supplicant( 4017): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4017): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4017): Auto country group 1: ch36
I/wpa_supplicant( 4017): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4017): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4017): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4017): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 4017): random: Got 20/20 bytes from /dev/random,
,D/wpa_supplicant( 4017): Get randomness: len=20 entropy=0
V/RegulatoryObserver(  910): uevent:
V/RegulatoryObserver(  910): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  910): Regulatory Country Code:DE
V/RegulatoryObserver(  910): Start wifi-crda service to run crda.
V/RegulatoryObserver(  910): Country Code is DE
V/RegulatoryObserver(  910): Send broadcast country code message.
I/RegulatoryObserver(  910): Broadcast intent for crda country code: DE
D/wpa_supplicant( 4017): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4017): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_910-2
D/wpa_supplicant( 4017): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4017): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4017): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4017): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4017): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4017): nl80211: Event message available
D/wpa_supplicant( 4017): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4017): nl80211: Regulatory domain change
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4017): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4017): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4017): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4017): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4017): P2P: Add operating class 81
D/wpa_supplicant( 4017): P2P: Add operating class 115
D/wpa_supplicant( 4017): P2P: Add operating class 116
D/wpa_supplicant( 4017): P2P: Add operating class 117
D/wpa_supplicant( 4017): P2P: Update channel list
D/wpa_supplicant( 4017): p2p0: Updating hw mode
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4017): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4017): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4017): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4017): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4017): nl80211: Added 802.11b mode based on 802.11g information
,D/WifiNative-wlan0(  910): doBoolean: SET_WIFI_ON 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4017): set wifi ON
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER MACADDR
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1109): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  910): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiConfigStore(  910): Loading config and enabling all networks
,D/WifiNative-wlan0(  910): doString: LIST_NETWORKS
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): list_network_info: ret=0x1, pos=0xb74c5117 buf=0xb74c50e8
,I/wpa_supplicant( 4017): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4017): 0	NG700	any	
D/WIFI_ICON( 1109): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiNative-wlan0(  910):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  910): 0	NG700	any	
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 ssid
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/HtcWiFiWidget_WiFiWidgetProvider( 4047): onWiFiStateChanged() for widget: 
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 bssid
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'bssid'
,D/HtcWiFiWidget_WiFiWidgetProvider( 4047): updateWidget(context) for widget: 
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 priority
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_key2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3',
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'as_cert_file'
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_psk
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 psk
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4017): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 proto
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  910): Failed to look-up a string: W
,D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  910): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 group
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  910): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
,D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
,D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 limited
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='limited'
,D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 eap
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 phase2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 identity
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
,D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 password
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 client_cert
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
,D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 engine
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='engine_id',
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 key_id
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 private_key
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4017): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4017): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  910): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  910): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4017): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4017): WPS: Set UUID for interface wlan0
I/wpa_supplicant( 4017): wpa_supplicant_scan enter
,I/wpa_supplicant( 4017): State: DISCONNECTED -> SCANNING
D/WifiNative-wlan0(  910):    returned true
I/wpa_supplicant( 4017): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4017): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  910): doBoolean: SET manufacturer HTC
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 33
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 4017): Scan req (ret=0) - timeout 10 secs
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 4017): nl80211: Event message available
,D/wpa_supplicant( 4017): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4017): manufacturer='HTC'
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET model_name HTC Desire 820
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'model_name'='HTC Desire 820'
,D/wpa_supplicant( 4017): model_name='HTC Desire 820'
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4017): model_number='HTC Desire 820'
D/WifiNative-wlan0(  910):    returned true
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET config_methods physical_display virtual_push_button
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4017): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DISABLE_OFFLOAD
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET auto_interworking 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4017): auto_interworking=0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: STATUS
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): SET_SCREEN_ON:On
I/wpa_supplicant( 4017): htc_wext_set_keepalive +
I/wpa_supplicant( 4017): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4017): getPrivFuncNum +	
I/wpa_supplicant( 4017): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 4017): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4017): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4017): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4017): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET ps 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4017): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
W/Settings(  910): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  910): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE: field=AIR_MODE id=0
D/WifiP2pService(  910): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): SETBAND: 0
D/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4017): P2P: Add operating class 81
D/wpa_supplicant( 4017): P2P: Add operating class 115
D/wpa_supplicant( 4017): P2P: Add operating class 116
D/wpa_supplicant( 4017): P2P: Add operating class 117
,D/wpa_supplicant( 4017): P2P: Update channel list
I/wpa_supplicant( 4017): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4017): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4017): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4017): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4017): p2p_oper_reg_class=126
D/wpa_supplicant( 4017): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4017): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 4017): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4017): CTRL_IFACE SET 'p2p_oper_channel'='36'
,D/wpa_supplicant( 4017): p2p_oper_channel=36
E/wpa_supplicant( 4017): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4017): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4017): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4017): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4017): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: BSS_FLUSH 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4017): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  910): doBoolean: SET pno 0
D/libc    (  910): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 4017): wpa_supplicant_scan enter
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiMonitor(  910): startMonitoring(p2p0) with mConnected = true
I/QuickSettingWifi( 1109): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  910): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4017): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4017): persistent_reconnect=1
I/wpa_supplicant( 4017): Recv Cmd 2: SET persistent_reconnect=1
D/WifiP2pService(  910): P2pEnablingState
D/WifiP2pService(  910): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2p socket connection successful
D/WifiP2pService(  910): P2pEnabledState
D/WifiDisplayController(  910): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  910): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiP2pService(  910): sending p2p connection changed broadcast
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doBoolean: SET device_name Android_1950
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 4017): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 4017): device_name='Android_1950'
I/wpa_supplicant( 4017): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  910):    returned true
,D/WifiNative-p2p0(  910): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 4017): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 4017): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4017): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 4017): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4017): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4017): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  910):    returned true
,D/WifiNative-p2p0(  910): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4017): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4017): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4017): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  910):    returned true,
D/WifiNative-p2p0(  910): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4017): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4017): Single channel concurrency preference: sta
,I/wpa_supplicant( 4017): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doString: STATUS
,W/WifiHW  (  910): QCOM Debug wifi_send_command "STATUS"
,D/WifiNative-p2p0(  910): doBoolean: P2P_FLUSH
W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4017): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4017): P2P: Stopping find
D/wpa_supplicant( 4017): P2P: Clear timeout (state=IDLE)
,I/wpa_supplicant( 4017): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4017): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  910):    returned true
,D/WifiNative-p2p0(  910): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4017): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4017): Recv Cmd 2: P2P_SERVICE_FLUSH,
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doString: LIST_NETWORKS
W/WifiHW  (  910): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4017): list_network_info: ret=0x22, pos=0xb74c510a buf=0xb74c50e8
I/wpa_supplicant( 4017): list_network_info: buf=network id / ssid / bssid / flags
,I/wpa_supplicant( 4017): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  910):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  910): doBoolean: AP_SCAN 1
D/WifiDisplayController(  910): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  910): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiP2pService(  910): Send p2p flush in initializeP2pSettings
,D/WifiDisplayController(  910): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  910):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  910):  primary type: 10-0050F204-5
D/WifiDisplayController(  910):  secondary type: null
D/WifiDisplayController(  910):  wps: 0
D/WifiDisplayController(  910):  grpcapab: 0
D/WifiDisplayController(  910):  devcapab: 0
D/WifiDisplayController(  910):  status: 3
D/WifiDisplayController(  910):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  910):  WFD CtrlPort: 0
D/WifiDisplayController(  910):  WFD MaxThroughput: 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  910):    returned false
D/WifiNative-p2p0(  910): doBoolean: SET wifi_display 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4017): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4017): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4017): WFD: Update WFD IE
,I/wpa_supplicant( 4017): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4017): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  910): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4017): WFD: Set subelement 0
D/wpa_supplicant( 4017): WFD: Update WFD IE
,I/wpa_supplicant( 4017): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4017): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  910):    returned true
V/AudioService(  910): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  910):     Client/Owner: Client
V/AudioService(  910):     GroupId: 
V/AudioService(  910):     Passphrase: 
V/AudioService(  910):     SessionId: 0
V/AudioService(  910):     IP Address: }
D/HtcEffectManagerBase(  910): onEventChanged id=5 status=false
D/HtcEffectManager(  910): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
,D/HtcEffectManager(  910): convertEffect before=902
,D/HtcEffectManager(  910): convertEffect after=902
D/WifiP2pService(  910): sending p2p persistent groups changed broadcast
D/WifiP2pService(  910): InactiveState
D/WifiP2pService(  910): InactiveState{ when=-14ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  910):  WFD CtrlPort: 7236
D/WifiP2pService(  910):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-14ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  910):  WFD CtrlPort: 7236
D/WifiP2pService(  910):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  910): Successfully set WFD info.
I/WifiDisplayController(  910): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  910): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  910):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  910):  primary type: 10-0050F204-5
D/WifiDisplayController(  910):  secondary type: null
D/WifiDisplayController(  910):  wps: 0
D/WifiDisplayController(  910):  grpcapab: 0
D/WifiDisplayController(  910):  devcapab: 0
D/WifiDisplayController(  910):  status: 3
D/WifiDisplayController(  910):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  910):  WFD CtrlPort: 7236
D/WifiDisplayController(  910):  WFD MaxThroughput: 50
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/wpa_supplicant( 4017): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4017): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4017): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
,D/Tethering(  910): interfaceStatusChanged p2p0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4017): nl80211: Event message available
D/wpa_supplicant( 4017): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4017): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4017): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 4017): nl80211: Survey data missing
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4017): Sorted scan results
I/wpa_supplicant( 4017): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 4017): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 4017): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 4017): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 4017): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 4017): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4017): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4017): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4017): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4017): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4017): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4017): wpa_supplicant_pick_network+
I/wpa_supplicant( 4017): Selecting BSS from priority group 1
I/wpa_supplicant( 4017): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4017): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4017): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4017): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4017):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4017):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 4017): Start print parameters
I/wpa_supplicant( 4017): wpa_s->wpa_state is 3
I/wpa_supplicant( 4017): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4017): isConcurrentMode() is 0
I/wpa_supplicant( 4017): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4017): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4017): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4017): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4017): wpa_s->reassociate is 0
I/wpa_supplicant( 4017): wpa_s->is_screen_on 1
I/wpa_supplicant( 4017): wpa_s->ifname wlan0
I/wpa_supplicant( 4017): End print parameters
I/wpa_supplicant( 4017): selected network = 1
D/wpa_supplicant( 4017): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb74c34e8  current_ssid=0x0
D/wpa_supplicant( 4017): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4017): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4017): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4017): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4017): check if in concurrent case
,I/wpa_supplicant( 4017): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 4017): wpa_supplicant_associate, 1777,
D/wpa_supplicant( 4017): wpa_supplicant_associate, 1780
,D/wpa_supplicant( 4017): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4017): RSN: PMKSA cache search - network_ctx=0xb74c34e8 try_opportunistic=0,
D/wpa_supplicant( 4017): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 4017): RSN: No PMKSA cache entry found,
I/wpa_supplicant( 4017): State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 4017): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4017): netlink: Operstate: linkmode=-1, operstate=5,
,D/wpa_supplicant( 4017): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4017): nl80211: Set mode ifindex 22 iftype 2 (STATION)
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4017): nl80211: Unsubscribe mgmt frames handle 0xb74c2718 (mode change)
,D/wpa_supplicant( 4017): nl80211: Subscribe to mgmt frames with non-AP handle 0xb74c2718
,D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718,
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718,
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4017): nl80211: Register frame type=0xd0 nl_handle=0xb74c2718
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4017): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4017):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4017):   * freq=2412
D/wpa_supplicant( 4017):   * Auth Type 0
D/wpa_supplicant( 4017):   * WPA Versions 0x2,
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4017): nl80211: Connect request send successfully
D/wpa_supplicant( 4017): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4017): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4017): reply (489) for get BSS: id=0
I/wpa_supplicant( 4017): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4017): freq=5220
I/wpa_supplicant( 4017): level=-47
I/wpa_supplicant( 4017): tsf=0000000102331702
I/wpa_supplicant( 4017): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4017): ssid=NG7005g
I/wpa_supplicant( 4017): ====
I/wpa_supplicant( 4017): id=1
I/wpa_supplicant( 4017): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4017): freq=2412
I/wpa_supplicant( 4017): level=-51
I/wpa_supplicant( 4017): tsf=0000000102331734
I/wpa_supplicant( 4017): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4017): ssid=NG700
I/wpa_supplicant( 4017): ====,
I/wpa_supplicant( 4017): id=2
I/wpa_supplicant( 4017): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4017): freq=2412
I/wpa_supplicant( 4017): level=-52
I/wpa_supplicant( 4017): tsf=0000000102331725
I/wpa_supplicant( 4017): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4017): ssid=01ABC
I/wpa_supplicant( 4017): ====
I/wpa_supplicant( 4017): id=3
I/wpa_supplicant( 4017): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4017): freq=2427
I/wpa_supplicant( 4017): level=-80
I/wpa_supplicant( 4017): tsf=0000000102331745
I/wpa_supplicant( 4017): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4017): ssid=Gonzos
I/wpa_supplicant( 4017): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (4) end of scan result ==
D/WifiManager( 1203): getScanResults enter 
D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (4) end of scan result ==
,D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 102331702, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 102331734, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 102331725, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 102331745, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 4 to mScanResults
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 4017): EAPOL: disable timer tick
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18,
,D/wpa_supplicant( 4017): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4017): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4017): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4017): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4017): nl80211: Event message available
D/wpa_supplicant( 4017): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4017): nl80211: Connect event
D/wpa_supplicant( 4017): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4017): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4017): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4017): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4017): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4017): Add randomness: count=6 entropy=4
I/wpa_supplicant( 4017): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4017): TDLS: Remove peers on association
D/wpa_supplicant( 4017): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 4017): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4017): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4017): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4017): htc_wext_set_keepalive +
I/wpa_supplicant( 4017): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4017): getPrivFuncNum +	
I/wpa_supplicant( 4017): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4017): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4017): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4017): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4017): Get randomness: len=32 entropy=5
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMo,nitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/Tethering(  910): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 4017): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb74c29f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4017):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4017): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4017): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f54b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4017):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 11
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 4017): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4017): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4017): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4017): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4017): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4017): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4017): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4017): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4017): set send_ind_to_ndc = 0
I/wpa_supplicant( 4017): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4017): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4017): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4017): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4017): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4017): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4017): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4017): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4017): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4017): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4017): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4017): EAPOL authentication completed successfully
I/wpa_supplicant( 4017): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4017): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4017): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4017): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/bt-btu  ( 3958): btu_task received preload complete event
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/bt-btm  ( 3958): btm_acl_device_down
D/bt-btm  ( 3958): btm_acl_reset_paging
D/bt-btm  ( 3958): btm_acl_set_discing
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/bt-btm  ( 3958): btm_reset_complete
I/bt-btm  ( 3958): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/bt-btm  ( 3958): Start reading local supported commands
D/bt-btm  ( 3958): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 3958): BTM reads next extended features page (1)
D/bt-btm  ( 3958): BTM reads next extended features page (2)
D/bt-btm  ( 3958): BTM reached last extended features page (2)
D/bt-btm  ( 3958): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
D/bt-btm  ( 3958): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
D/bt-btm  ( 3958): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3958): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 3958): btm_read_ble_wl_size 
D/bt-btm  ( 3958): btm_read_white_list_size_complete 
D/bt-btm  ( 3958): btm_get_ble_buffer_size 
D/bt-btm  ( 3958): btm_read_ble_buf_size_complete 
D/bt-btm  ( 3958): btm_read_ble_local_supported_features 
D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/bt-btm  ( 3958): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3958): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3958): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3958): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3958): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3958): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3958): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3958):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3958): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3958): BTM_SetInquiryMode
I/bt-btm  ( 3958): BTM_SetPageScanType
I/bt-btm  ( 3958): BTM_SetInquiryScanType
D/bt-btm  ( 3958): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3958): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3958): BTM_BleLoadLocalKeys
D/bt-btm  ( 3958): BTM_BleLoadLocalKeys
I/bt-btm  ( 3958): BTM_Sec: application registered
E/bt-btm  ( 3958): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fa9941 
I/bt-btm  ( 3958): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3958): SMP_Register state=0
E/bt-btm  ( 3958): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fa9941 
I/bt-btm  ( 3958): BTM_Sec: application registered
D/bt-btm  ( 3958): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3958): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3958): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3958): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3958): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3958): BTM_RegBusyLevelNotif
I/bt-att  ( 3958): GATT_Register
D/bt-att  ( 3958): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3958): allocated gatt_if=3
I/bt-att  ( 3958): GATT_StartIf gatt_if=3
D/bt-att  ( 3958): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3958): gatt_find_the_connected_bda found=0 found_idx=7
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/IntentController( 1109): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1109): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WISPrService( 3330): >>>>>WISPrService start isConnected = false<<<<<
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
E/bt-btif ( 3958): Write Extended Inquiry Response to controller
I/bt-btm  ( 3958): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3958): BTM_AllocateSCN
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3958): BTM_AllocateSCN
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btm  ( 3958): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3958):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3958):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3958):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3958):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3958):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3958):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3958):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3958):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3958): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:6
D/WISPrService( 3330): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/bt-a2d  ( 3958): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
D/bt-avp  ( 3958): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3958): AVRC_AddRecord uuid: 110e
,I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btm  ( 3958): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3958):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-att  ( 3958): GATT_Register
D/bt-att  ( 3958): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3958): allocated gatt_if=4
I/bt-att  ( 3958): GATT_StartIf gatt_if=4
D/bt-att  ( 3958): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3958): gatt_find_the_connected_bda found=0 found_idx=7
,D/WifiService(  910): New client listening to asynchronous messages
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 08:ec:a9:50:75:41
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: f8:cf:c5:d9:e5:61
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
E/bt-btif ( 3958): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3958): HAL bt_hal_cbacks->adapter_properties_cb
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3958): BTM_GetHCIConnHandle
I/bt-btm  ( 3958): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:2 len:6
D/bt-btm  ( 3958): BTM_SecAddDevice : rmt_io_caps is 0 
D/BluetoothAdapterProperties( 3958): Address is:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:1 len:14
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3958): Scan Mode:20
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3958): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:8 len:60
D/BluetoothAdapter( 3958): getBluetoothService(): entry
D/BluetoothAdapter( 3958): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3958): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b29940
D/BluetoothDevice( 3958): getService : Register callback
,D/BluetoothAdapterProperties( 3958): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 3958): Adding bonded device:80:01:84:8A:B3:68
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/BluetoothAdapterProperties( 3958): Adding bonded device:14:B4:84:21:3B:49
D/BluetoothAdapterProperties( 3958): Adding bonded device:08:EC:A9:50:76:27
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/BluetoothAdapterProperties( 3958): Adding bonded device:08:EC:A9:50:75:41
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/BluetoothAdapterProperties( 3958): Adding bonded device:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3958): Adding bonded device:7C:F9:0E:34:8A:A0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [2][0][0]
D/BluetoothAdapterProperties( 3958): Adding bonded device:90:E7:C4:F6:69:77
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/BluetoothAdapterProperties( 3958): Adding bonded device:90:E7:C4:3C:62:6A
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
D/BluetoothAdapterProperties( 3958): Adding bonded device:38:94:96:B5:06:DC
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): WiFioffload: set mMobileNetworkType= Unknown,
D/WifiNative-wlan0(  910): doBoolean: MOBILE_TYPE Unknown
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): WiFioffload: update mobile network = Unknown
D/WifiNative-wlan0(  910):    returned true,
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): Power_Mode_Type mode = 1
I/wpa_supplicant( 4017): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 61
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd: failed to issue private commands,
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
,I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(438c7aa0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425dc5a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425dc5a0 target=com.android.internal.util.StateMachine$SmHandler }
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
I/QuickSettingWifi( 1109): receive.wifiConnect:false wifiAPname:null elapse:1
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3958): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
D/BluetoothRemoteDevices( 3958): Remote class is:5898764
I/bt-btif ( 3958): BTA_JvEnable
I/bt-btm  ( 3958): BTM_ReadConnectability
I/bt-btm  ( 3958): BTM_ReadDiscoverability
I/bt-btm  ( 3958): BTM_SetDiscoverability
I/bt-btm  ( 3958): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3958): br_edr_supported=0x2
I/bt-btm  ( 3958): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3958): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3958): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3958): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3958): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3958): BTM_SetConnectability
I/bt-btm  ( 3958): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3958): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3958): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3958): BTM_SetDiscoverability
I/bt-btm  ( 3958): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3958): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3958): br_edr_supported=0x0
I/bt-btm  ( 3958): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3958): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3958): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3958): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3958): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3958): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3958): BTM_SetConnectability
I/bt-btm  ( 3958): btm_ble_set_co,nnectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3958): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3958): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3958): bta_pan_co_init
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3958): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3958):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3958):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3958): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3958):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3958): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3958):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
E/bt_mct  ( 3958): hci lib postload completed
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btif ( 3958): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3958): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3958): ScanMode =  20
D/BluetoothAdapterProperties( 3958): State =  11
I/bt-btm  ( 3958): BTM_SetDiscoverability
I/bt-btm  ( 3958): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3958): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3958): br_edr_supported=0x0
I/bt-btm  ( 3958): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3958): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3958): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3958): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3958): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3958): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3958): BTM_SetConnectability
I/bt-btm  ( 3958): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3958): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3958): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3958): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3958): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3958): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3958): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3958): Setting state to 12
,I/BluetoothAdapterState( 3958): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3958): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  910): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  910): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1222): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3958): Scan Mode:21
I/bt-btif ( 3958): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3958): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3958): Discoverable Timeout:120
I/BluetoothAdapterState( 3958): Entering On State,
D/BluetoothPan(  910): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1109): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1222): Proxy object connected
D/BluetoothAdapterService(1101935016)( 3958): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3958): getBondedDevices: length=10
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothPan(  910): BluetoothPAN Proxy object connected
D/BluetoothHeadset( 1109): Proxy object connected
I/QuickSettingMiniLite( 1109): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41de4698
D/BluetoothHeadset( 1222): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1222): Proxy object connected
D/BluetoothPhoneService( 1222): BluetoothHeadset onServiceConnected
D/BluetoothAdapter( 1222): 1103252472: getState(). Returning 12
,D/BluetoothHeadset(  910): onBluetoothStateChange: up=true
D/BluetoothA2dp(  910): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  910): Proxy object connected
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,D/BluetoothAdapter(  910): 1111800896: getState(). Returning 12
,D/BluetoothManagerService(  910): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1109): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 3958): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3958): ***********state = 12
,D/BluetoothA2dp(  910): Proxy object connected
,D/BluetoothAdapter(  910): 1111800896: getState(). Returning 12
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/PMS     (  910): acquireWL(43873db8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1203 10029 null
D/PMS     (  910): acquireWL(43fde2f8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3330 1000 null
D/BluetoothMasReceiver( 3958): Bluetooth STATE CHANGED to 12
D/BluetoothAdapterService(1101935016)( 3958): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3958): getBondedDevices: length=10
,V/BluetoothSapReceiver( 3958): SapReceiver onReceive 
V/BluetoothSapReceiver( 3958): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3958):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3958): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManagerService(  910): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 12
D/PMS     (  910): releaseWL(43873db8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 12
V/BluetoothMasService( 3958): parseIntent 1: mIsEmailEnabled: true
D/HtcBtWidget_BTWidgetProvider( 3984): onBTStateChanged() for widget: 
,V/EmailUtils( 3958): Manager Instance is not NULL
,D/HtcBtWidget_BTWidgetProvider( 3984): updateWidget(context) for widget: 
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426d61c0:true
,W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/PMS     (  910): releaseWL(43fde2f8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  910): acquireWL(426d6008): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3330 1000 null
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/EmailUtils( 3958): ============NULL aList========
V/EmailUtils( 3958): <-getEmailAccountIdList
V/BluetoothSapService( 3958): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3958): state: 12
D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 12
I/LocationAgent( 3330): new LocationAgent instance!!
W/ContextImpl( 3958): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/HtcTagManager( 3330): HtcTagManager construction complete
V/BluetoothSapService( 3958): Starting SAP server process
V/BluetoothPbapService( 3958): Handler(): got msg=1
V/BluetoothPbapService( 3958): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3958): Pbap Service initSocket
V/BluetoothMasService( 3958): handleMessage: mIsEmailEnabledtrue
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtMns   ( 3958): BluetoothMns: isEmailEnabled: true
D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
D/BluetoothMasService( 3958): Map_prev 1
D/BluetoothAdapter( 3958): getBluetoothService(): entry
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothInputDevice( 3330): BluetoothInputDevice()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/BluetoothAdapter( 3958): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  910): Registered receivers: 7
D/BluetoothAdapter( 3958): getBluetoothService(): entry
W/BluetoothAdapter( 3958): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3958): SOCK FLAG = 1 ***********************
I/bt-btif ( 3958): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btif ( 3958): BTA_JvRfcommStartServer
I/bt-btm  ( 3958): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3958):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3958): Succeed to create listening socket 
V/BluetoothPbapService( 3958): Accepting socket connection...
E/BluetoothServiceJni( 3958): SOCK FLAG = 3 ***********************
I/bt-btif ( 3958): BTA_JvCreateRecordByUser
D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
D/BluetoothInputDevice( 3330): BluetoothInputDevice(): Binding service...
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btif ( 3958): BTA_JvRfcommStartServer
I/bt-btm  ( 3958): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3958):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothPan( 3330): BluetoothPan()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  910): Registered receivers: 8
D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
D/BluetoothPan( 3330): BluetoothPan(): Binding service...
D/BluetoothAdapter( 3958): getBluetoothService(): entry
W/BluetoothAdapter( 3958): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3958): SOCK FLAG = 3 ***********************
I/bt-btif ( 3958): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
,I/bt-btif ( 3958): BTA_JvRfcommStartServer
,I/bt-btm  ( 3958): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3958):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothMap( 3330): Create BluetoothMap proxy object
,D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 9
,E/BluetoothMap( 3330): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothAdapter( 1109): 1104651664: getState(). Returning 12
,D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothSap( 3330): BluetoothSap() call bindService
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 10
,D/BluetoothAdapter( 1109): 1104651664: getState(). Returning 12
W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,I/QuickSettingBluetooth( 1109): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1109): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothPbap( 3330): BluetoothPbap()
,D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 11
D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
,D/BluetoothPbap( 3330): BluetoothPbap(): Binding service...
W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothA2dp( 3330): BluetoothA2dp()
,D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 12
D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
,D/BluetoothA2dp( 3330): BluetoothA2dp(): Binding service...,
W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,D/BluetoothAdapter( 1109): 1104651664: getState(). Returning 12
,I/QuickSettingMiniLite( 1109): updateLiteState:no connect device!
,D/wpa_supplicant( 4017): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4017): EAPOL: disable timer tick
,D/BluetoothHeadset( 3330): BluetoothHeadset()
,D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothSapService( 3958): Sap_prev 1
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 13
D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
,D/BluetoothHeadset( 3330): BluetoothHeadset(): Binding service...
,V/BluetoothSapService( 3958): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 3958): Sap Service initRfcommSocket
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/HtcTagManager( 3330): startProxy
D/BluetoothAdapter( 3958): getBluetoothService(): entry
,W/BluetoothAdapter( 3958): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3958): SOCK FLAG = 3 ***********************
I/bt-btif ( 3958): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btif ( 3958): BTA_JvRfcommStartServer
I/bt-btm  ( 3958): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3958):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3958): Succeed to create listening socket 
,V/BluetoothSapService( 3958): Accepting socket connection...
,W/ContextImpl( 3330): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3330): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3330): finishStartingService: stopping service
,D/BluetoothPan( 3330): BluetoothPAN Proxy object connected
D/PanProfile( 3330): Bluetooth service connected
D/BluetoothA2dp( 3330): Proxy object connected
,D/A2dpProfile( 3330): Bluetooth service connected
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4023): onCreate: going to find gatt base service first.
,D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
,D/BluetoothHeadset( 3330): Proxy object connected
,D/HeadsetProfile( 3330): Bluetooth service connected
,D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
V/TAG     ( 3958): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 3958): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b21608
,D/BluetoothInputDevice( 3330): Proxy object connected
,D/HidProfile( 3330): Bluetooth service connected
,D/BluetoothAdapter( 3330): 1103542104: getState(). Returning 12
,V/BluetoothPbapService( 3958): Pbap Service onBind
,D/SapServerProfile( 3330): Bluetooth service connected
D/BluetoothPbap( 3330): Proxy object connected
,D/PbapServerProfile( 3330): Bluetooth service connected
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43fc9bf0:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  910): releaseWL(426d6008): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/[HTC_BLE][Constants]( 4023):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4023):  + enableOnBonded = false
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/[HTC_BLE][Constants]( 4023):  + discoverServicesOnBonded = false
I/BluetoothFtpService( 3958): Ftp Service onCreate
D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 12
D/BluetoothMasReceiver( 3958): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3958): getBluetoothService(): entry
W/BluetoothAdapter( 3958): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3958): SOCK FLAG = 0 ***********************
I/bt-btif ( 3958): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btif ( 3958): BTA_JvRfcommStartServer
I/bt-btm  ( 3958): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3958):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3958): Accept thread started.
,D/BluetoothFtpService( 3958): Ftp_prev 1
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3958): getBluetoothService(): entry
,W/BluetoothAdapter( 3958): getBluetoothService() called with no BluetoothManagerCallback
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4023):  + Google LE service found. Using BaseLeProfilesGoogle.
E/BluetoothServiceJni( 3958): SOCK FLAG = 1 ***********************
I/bt-btif ( 3958): BTA_JvCreateRecordByUser
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4023): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41ae9198
D/[HTC_BLE][Constants]( 4023): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4023): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4023): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4023): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4023): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4023): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
D/bt-sdp  ( 3958): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3958): Write Extended Inquiry Response to controller
I/bt-btif ( 3958): BTA_JvRfcommStartServer
I/bt-btm  ( 3958): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3958):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3958): Run Accept thread
D/BluetoothAdapter( 3958): 1101953192: getState(). Returning 12
V/BluetoothMasService( 3958): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3958): Manager Instance is not NULL
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4023): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4023): Received state change = 12
,D/HtcTagManager( 3330): onServiceConnected
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4023): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4023): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41ae9198
D/HtcTagProfile( 3330): setup proxy
D/HtcPxpProfile( 3330): setup proxy
,D/HtcFmpProfile( 3330): setup proxy
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4023): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ae9198
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4023): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ae9198, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41af4180
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4023): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ae9198
,D/EmailUtils( 3958): ============NULL aList========
,V/EmailUtils( 3958): <-getEmailAccountIdList
,D/BluetoothMasService( 3958): Map_prev 1
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@432bc040:true
,I/LocationAgent( 3853): new LocationAgent instance!!
,D/HtcTagManager( 3853): HtcTagManager construction complete
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/BluetoothInputDevice( 3853): BluetoothInputDevice()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 14
D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/BluetoothInputDevice( 3853): BluetoothInputDevice(): Binding service...
,D/BluetoothPan( 3853): BluetoothPan()
D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 15
,D/RingtoneManager( 4023): getExternalStorageState=mounted
D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/BluetoothPan( 3853): BluetoothPan(): Binding service...
W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,D/BluetoothMap( 3853): Create BluetoothMap proxy object
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 16
,E/BluetoothMap( 3853): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  910): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[1]: Daisy
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[3]: Foxglove
D/BluetoothManagerService(  910): Registered receivers: 17
,D/BluetoothSap( 3853): BluetoothSap() call bindService
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[7]: Licorice
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[10]: Snowbell
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4023):  + mAlertUri: content://settings/system/alarm_alert
,W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4023): BleProfilesStateMachine is initialized...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4023): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4023): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4023): initScanModeInterface: true
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4269bb00:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4023): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4023):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE][Constants]( 4023):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4023):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4023):  + discoverServicesOnBonded = false
,D/BluetoothPbap( 3853): BluetoothPbap()
,D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 18
,W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/BluetoothPbap( 3853): BluetoothPbap(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4023): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41af4180
,D/BluetoothA2dp( 3853): BluetoothA2dp()
,D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/BluetoothA2dp( 3853): BluetoothA2dp(): Binding service...
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 19
,D/BluetoothHeadset( 3853): BluetoothHeadset()
W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
D/BluetoothManagerService(  910): Registered receivers: 20
,D/BluetoothHeadset( 3853): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3853): startProxy
,W/ContextImpl( 3853): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3853): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3853): setBluetoothStateOn
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/HtcTagManager( 3853): startProxy
D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
D/BluetoothAdapterService(1101935016)( 3958): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3958): getBondedDevices: length=10
D/BluetoothAdapter( 3853): getBluetoothService(): entry
D/BluetoothAdapter( 3853): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3853): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b237b0
D/BluetoothDevice( 3853): getService : Register callback
E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,E/BluetoothDevice( 3853): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): addHtcTagProfiles
,D/AuthorizationBluetoothService( 1340): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1340): Proximity feature is not enabled.
D/BluetoothInputDevice( 3853): Proxy object connected
,D/HidProfile( 3853): Bluetooth service connected
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
D/BluetoothPan( 3853): BluetoothPAN Proxy object connected
,D/PanProfile( 3853): Bluetooth service connected
D/SapServerProfile( 3853): Bluetooth service connected
D/BluetoothPbap( 3853): Proxy object connected
D/PbapServerProfile( 3853): Bluetooth service connected
D/BluetoothA2dp( 3853): Proxy object connected
,D/A2dpProfile( 3853): Bluetooth service connected
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/BluetoothHeadset( 3853): Proxy object connected
,D/HeadsetProfile( 3853): Bluetooth service connected
,D/BluetoothAdapter( 3853): 1101963448: getState(). Returning 12
,D/HtcTagManager( 3853): onServiceConnected
D/HtcTagProfile( 3853): setup proxy
D/HtcPxpProfile( 3853): setup proxy
,D/HtcFmpProfile( 3853): setup proxy
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420eb370
,W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  910): Couldn't get kernel wake lock stats
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420eb370, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e48dd0
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@4269f920
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,W/PMS     (  910): mWirelessDisplayManager is null
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/SensorManager(  910): mEventCount = 1200
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 318ms
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1237): applyRouting - 0
,D/NfcService( 1237): ScreenObserver: OFF
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1237): applyRouting -2
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@421eefe0)
D/PMS     (  910): acquireWL(41dcd5f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1237 1027 null
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
D/PMS     (  910): releaseWL(41dcd5f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputMethodManagerService(  910): Disable input method client, pid=3912
,W/ResourceType( 3912): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3912): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ada158 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/PMN     (  910): wakingUp
D/PMS     (  910): acquireWL(420f0058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/WindowManager(  910): No lock screen! windowToken=null
I/BatteryService(  910): n_update end
D/PMN     (  910): onScreenOn
D/PMS     (  910): releaseWL(420f0058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/ActivityManager(  910): Disable JIT of com.htc.bgp
,D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/ActivityManager(  910): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4129 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
I/ClockThread( 1109): stop update clock
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/MtpService( 2204): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
D/NfcService( 1237): applyRouting - 0
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
I/wpa_supplicant( 4017): Power_Mode_Type mode = 0
I/wpa_supplicant( 4017): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,D/MtpService( 2204): [MTP][onReceive]-
,D/NfcService( 1237): applyRouting -2
D/PMS     (  910): acquireWL(42280098): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1237 1027 null
D/PMS     (  910): releaseWL(42280098): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): SET_SCREEN_ON:On
I/wpa_supplicant( 4017): htc_wext_set_keepalive +
I/wpa_supplicant( 4017): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4017): getPrivFuncNum +	
I/wpa_supplicant( 4017): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4017): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4017): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4017): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 4017): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  910): releaseWL(438c7aa0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  372): ParamSet string: screen_state=on
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
D/NetworkPolicy(  910): updateScreenOn: false
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4017): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  910): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4017): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19733 delay=15s
,I/IntentController( 1109): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/CalendarProvider2( 4129): Created com.android.providers.calendar.CalendarAlarmManager@41b0caa8(com.android.providers.calendar.HtcCalendarProvider@41af4e30)
,D/WifiWatchdogStateMachine(  910): WAN detection
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/WIFI_ICON( 1109): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/MDST    (  910): default: setTeardownRequested(true)
,D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WISPrService( 3330): >>>>>WISPrService start isConnected = true<<<<<
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/CalendarProvider2( 4129): wait start:true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0,
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42451840
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/PMS     (  910): acquireWL(44146068): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/PMS     (  910): releaseWL(44146068): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43f79c90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/PMS     (  910): releaseWL(43f79c90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/CalendarProvider2( 4129): wait end:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4023): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4023): onScreenOn: 1450201660580
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4023): onScreenOn: 1450201660581,
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
I/QuickSettingWifi( 1109): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e48dd0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e48dd0, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@4269f920
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(43b361c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,D/PMS     (  910): acquireWL(4252c720): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [1][0][0]
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4159 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19733 mDataStallAlarmIntent=PendingIntent{43820550: PendingIntentRecord{438204d0 android broadcastIntent}}
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4017): SET_SCREEN_ON:Off
I/wpa_supplicant( 4017): htc_wext_set_keepalive +
I/wpa_supplicant( 4017): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4017): getPrivFuncNum +	
D/PMS     (  910): releaseWL(4252c720): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,D/PMS     (  910): acquireWL(41eb08e8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
I/wpa_supplicant( 4017): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4017): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4017): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4017): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4017): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4017): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  910):    returned true
D/PMS     (  910): releaseWL(41eb08e8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/ContactMessageStore( 1222): start background delete task...
D/ContactMessageStore( 1222): size: 0 , 0
,D/ContactMessageStore( 1222): Background delete complete
D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4159): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): releaseWL(43b361c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4159): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(437aa870): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4159 1000 null
,D/PMS     (  910): releaseWL(437aa870): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4159): getMobilePolicyEnabled, result = true
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1324): receiver - intent: android.intent.action.USER_PRESENT
,D/TetherSettings( 3330): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3330): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3330): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3330): Cust_ConnectToPC   : spcsc>false
D/        ( 3330): Cust_ConnectToPC   : IPT>true
D/        ( 3330): Cust_ConnectToPC   : Singel_USB>false
D/AutoSetting( 1324): service - onCreate()
,W/Settings( 3330): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3330): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3330): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3330): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] getTotalRam: 1873 Mb
,D/AutoSetting( 1324): service - AddressCache: using context: com.htc.Weather
,I/PSReceiver( 3330): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): acquireWL(43817b98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43817b98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Delay finish: com.android.settings/.PSReceiver
,D/PMS     (  910): acquireWL(4381c458): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
I/SmartNS_PSService( 3330): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3330): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3330):  defaultType:0
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  910): request 424921c8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
I/ActivityManager(  910): Resuming delayed broadcast
D/PMS     (  910): releaseWL(4381c458): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/NetworkPolicy(  910): updateScreenOn: false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4023): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4023): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4023): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4023): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4023): onScreenOff
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4159): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4159): isEpsOn(), nState = 0
D/SmartSyncUtils( 4159): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4159): isEpsOn(), nState = 0
D/WifiService(  910): New client listening to asynchronous messages
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4269f920
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4269f920, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4269f920, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4269f920
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4269fe68 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4269fe68 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/CalendarProvider2( 4129): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4129): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3839): ---------------------------------------------------
D/ProviderChangeReceiver( 3839): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3839): start to updateAlertNotification!
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (3765/10100)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  910): acquireWL(438cfde8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null,
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4196 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3407/10053)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/CaptivePortalTracker(  910): NoActiveNetworkState
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [2][0][0]
,I/ConnectivityHelper( 1254): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1518/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1254/10076)
D/libc    (  910): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/AlertService( 3839): No fired or scheduled alerts
D/libc    (  910): [NET] getaddrinfo-, 1
D/HtcAlertUtils( 3839): -- cancelReminderNotification --
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =20ad +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/HtcAlertUtils( 3839): broadcastExistReminder!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (3765/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43910940): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/MusicStore( 4196): Database version: 95
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!,
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(4235b978): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 910 1000 WorkSource{10029}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(423c2340): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 910 1000 WorkSource{10029}
D/PMS     (  910): acquireWL(4263d9c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 910 1000 WorkSource{10029}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(4244a238): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 910 1000 WorkSource{10029}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4196): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  910): acquireWL(431b26a8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 910 1000 WorkSource{10096}
,I/ActivityManager(  910): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4224 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/GpsLocationProvider(  910): [handleMessage] INJECT_NTP_TIME
D/libc    (  910): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/PMS     (  910): releaseWL(43910940): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e716 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4310ff78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(4310ff78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/jxcore-log( 3912): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3912): 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(430450a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(430450a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4196): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42615208): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  910): releaseWL(42615208): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,W/ContextImpl( 4196): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/dalvikvm( 1970): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 149
D/libc    (  365): [NET]res_nsend:resplen=104
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
D/PMS     (  910): acquireWL(43620ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(43620ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  910): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1970): Failed to find provider info for com.android.contacts.metadata
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4196, uid=10154, userID:0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43673708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/SyncManager(  910): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 25549, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 105809, reason: UserStart
D/PMS     (  910): releaseWL(4244a238): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1518/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
I/IntentController( 1109): receive(android.intent.action.TIME_SET,4,false)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/DotMatrix( 1506): [EventService] EVENT_RESET_THEME_TIMESTAMP
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/FeedActionBar( 1254): updateLastUpdatedTime(in String) LAST UPDATED 18:46
,D/DotMatrix( 1506): [EventService] isTheSameDay:false,timestamp is early than today:true
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/MediaRouterService(  910): Client com.google.android.music (pid 4196): Registered
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
E/ExternalAccountType( 1309): Unsupported attribute readOnly
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/PMS     (  910): releaseWL(43673708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4326c870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
I/MediaRouter( 4196): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/Auth.Api.Credentials( 1970): [CredentialSyncAdapter] Unknown sync event.
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,I/NetworkMonitor( 4196): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4196/10154)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2204/10021)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4248 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/MediaRouter( 4196): getSelectedRoute
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 4196): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/PMS     (  910): releaseWL(4326c870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43c3a8c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4196/10154)
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(423c2340): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4196, uid=10154, userID:0,
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/libc    (  365): [NET]res_nsend:resplen=104,
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  910): NTP server returned: 1450201661381 (Tue Dec 15 18:47:41 CET 2015) reference: 106015 certainty: 10 system time offset: 13
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/PMS     (  910): acquireWL(4401f4b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 910 1000 WorkSource{10029}
D/PMS     (  910): releaseWL(43c3a8c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4224): Delaying sync.
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43fe67b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(43fe67b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4383d298): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Process (  910): killProcessQuiet, pid=3765
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
D/PMS     (  910): releaseWL(4235b978): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/ActivityManager(  910): Killing 3765:com.google.android.apps.docs/u0a100 (adj 15): empty #17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1109): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!,
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3765
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  910): [handleMessage] INJECT_NTP_TIME_FINISHED
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(423f83d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 910 1000 WorkSource{10029}
D/PMS     (  910): releaseWL(4383d298): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(438cfde8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/ACRA    ( 4248): ACRA is enabled for com.facebook.katana, intializing...
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4242c530): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(4242c530): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42619980): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ACRA    ( 4248): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4248): Looking for error files in /data/data/com.facebook.katana/app_minidumps
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PhoneStatusBar( 1109): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(42619980): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(420c3168): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/Process (  910): killProcessQuiet, pid=3787
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): releaseWL(431b26a8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/ActivityManager(  910): Killing 3787:com.htc.backup/1000 (adj 15): empty #17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
I/ActivityManager(  910): Recipient 3787
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(420c3168): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(438c9638): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(438c9638): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,W/SystemClassLoaderAdder( 4248): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4248): Preparing secondary program dexes.
V/DexLibLoader( 4248): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4248): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4248): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4248): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4248): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4248): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4248): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4248): Dex already copied
D/OdexVerifier( 4248): Odex verification is skipped.
,V/DexLibLoader( 4248): Creating class loader
,V/DexLibLoader( 4248): Finished creating class loader
V/DexLibLoader( 4248): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4248): Dex already copied
D/OdexVerifier( 4248): Odex verification is skipped.
,V/DexLibLoader( 4248): Creating class loader
,V/DexLibLoader( 4248): Finished creating class loader
V/DexLibLoader( 4248): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4248): Dex already copied
D/OdexVerifier( 4248): Odex verification is skipped.
,V/DexLibLoader( 4248): Creating class loader
W/DriveInitializer( 1970): Awaiting to be initialized
,W/DriveInitializer( 1970): Background init thread started
,V/DexLibLoader( 4248): Finished creating class loader
,V/DexLibLoader( 4248): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4248): Dex already copied
D/OdexVerifier( 4248): Odex verification is skipped.
,V/DexLibLoader( 4248): Creating class loader
,V/DexLibLoader( 4248): Finished creating class loader
,V/DexLibLoader( 4248): Verifying classes from secondary dexes.
,D/DexLibLoader( 4248): DexLibLoader.ensureDexLoaded took 172 ms
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 1970): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,W/DriveInitializer( 1970): Background init thread ended
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43047d68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(4401f4b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(43abfd38): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 910 1000 WorkSource{10096}
D/PMS     (  910): releaseWL(43047d68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42343f98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4224): Delaying sync.
D/PMS     (  910): releaseWL(42343f98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(423420f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(43abfd38): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(438cb0c8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 910 1000 WorkSource{10029}
D/PMS     (  910): releaseWL(423420f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(438cfbc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(4263d9c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/BTIF_CORE( 3958): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3958): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3958): Wake lock released
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(438cfbc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43fda1b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(43fda1b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1203): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43786e28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(423f83d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(43bf8fc0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 910 1000 WorkSource{10029}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43786e28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4404a1f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(4404a1f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(431e31e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
W/AlarmManager(  910): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{423fe9d8: PendingIntentRecord{438ef500 com.google.android.gms startService}}) : type=2 triggerAtTime=315360106643 win=-1 tElapsed=315360106643 maxElapsed=551880106641 interval=0 standalone=false
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43bf8fc0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(431a4348): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 910 1000 WorkSource{10160}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(431e31e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(434c7288): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(434c7288): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43b0ea10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(431a4348): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(43619820): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 910 1000 WorkSource{10160}
D/PMS     (  910): releaseWL(43b0ea10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(438dd6e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(438dd6e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(440adb38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(438cb0c8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  910): acquireWL(4297f508): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 910 1000 WorkSource{10029}
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(440adb38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(437931f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(43619820): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/PMS     (  910): releaseWL(437931f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42bff8c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(42bff8c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,I/Scheduler( 1203): Use legacy PeriodicScheduler
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/InstanceID/Rpc( 1203): Found 10029
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4372a410): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,I/IntentController( 1109): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4297f508): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  910): releaseWL(4372a410): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/PhoneStatusBar( 1109): removeIcon slot=sync_active index=7 viewIndex=0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4248): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4248): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4248): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4248): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4248): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4248): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4248): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4248): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4a7 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,W/dalvikvm( 4248): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,E/FbInjectorInitializer( 4248): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4248): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4248): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4248): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4248): Grow heap (frag case) to 9.517MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=3805
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 3805:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3805
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1324): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4300 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1324): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
D/AutoSetting( 1324): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1324): service - onStartCommand() check timezone in 30000
,W/fb4a(:<default>):UserScope( 4248): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4248): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4248): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4300): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4300): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4300): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4300): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4300/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4300/10079)
,D/PMS     (  910): acquireWL(430eb2c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4314 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=3751
,I/ActivityManager(  910): Killing 3751:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4300/10079)
,D/PMS     (  910): acquireWL(44041bf8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1970): Checkin interval check for package: unspecified last checkin: 1450196925722 min interval config: 0 actual interval: 4737654
D/PMS     (  910): releaseWL(430eb2c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3751
I/CheckinService( 1970): Checking schedule, now: 1450201663385 next: 1450196955690
,I/CheckinService( 1970): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1970, uid=10029, userID:0
,I/CheckinService( 1970): Preparing to send checkin request
,I/EventLogService( 1970): Accumulating logs since 1450200012704
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,E/dalvikvm( 4248): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4248): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4248): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4248): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4248): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4248): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4248): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4248): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4248): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4248): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4248): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4248): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
W/dalvikvm( 4248): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4248): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
E/dalvikvm( 4248): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4248): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4248): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4248): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4314): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4314): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4314): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4314): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4314): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4248): Grow heap (frag case) to 9.968MB for 84664-byte allocation
,I/dalvikvm-heap( 4248): Grow heap (frag case) to 10.004MB for 39954-byte allocation
,I/CheckinRequestBuilder( 1970): Checkin reason type: 8 attempt count: 1
D/WifiService(  910): New client listening to asynchronous messages
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1970): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4248): Grow heap (frag case) to 10.080MB for 79892-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4314/10151)
,V/WebViewChromiumFactoryProvider( 4314): Binding Chromium to main looper Looper (main, tid 1) {41acd978}
,I/LibraryLoader( 4314): Expected native library version number "",actual native library version number ""
,I/chromium( 4314): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4314): Initializing chromium process, renderers=0
,I/dalvikvm-heap( 4248): Grow heap (frag case) to 10.107MB for 28144-byte allocation
,E/AudioManagerAndroid( 4314): BLUETOOTH permission is missing!
D/PMS     (  910): acquireWL(439129c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  910): acquireWL(43841528): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  910): releaseWL(43841528): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4314): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4314): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4314): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4314): Local Branch: 
I/Adreno-EGL( 4314): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4314): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4314):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4314): Starting up...
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4314/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4314/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [4][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/Process (  910): killProcessQuiet, pid=3523
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3594/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3594/10160)
I/ActivityManager(  910): Killing 3523:com.google.android.gm/u0a107 (adj 15): empty #17
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (1970/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,I/dalvikvm-heap( 4248): Grow heap (frag case) to 10.283MB for 75760-byte allocation
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1970, uid=10029, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43894248 u0 ReceiverList{43894128 4248 com.facebook.katana/10027/u0 remote:42542128}}
,I/iu.SyncManager( 1970): SYNC; picasa accounts
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ece110 u0 ReceiverList{43ece0b0 4248 com.facebook.katana/10027/u0 remote:440266a0}}
V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/NetworkLogImpl( 1970): Loaded NetworkSpeedPredictor
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 1970): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,I/iu.UploadsManager( 1970): num queued entries: 0
,I/iu.UploadsManager( 1970): num updated entries: 0
I/iu.SyncManager( 1970): NEXT; no task
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/AlertReceiver( 3839): beginStartingService
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
D/PMS     (  910): acquireWL(4400e508): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3839 10013 null
,D/PMS     (  910): acquireWL(42768728): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4248): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4248): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4248): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  910): Recipient 3523
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/PMS     (  910): releaseWL(42768728): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ContactMessageStore( 1222): notify MmsSms
D/AccFlag ( 1222): sense_version=6.0
,D/AccFlag ( 1222): sku_id=99
D/libc    ( 1340): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1340): [NET] getaddrinfo-,err=8
D/libc    ( 1340): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1340): [NET] getaddrinfo-, 1
,D/libc    ( 1340): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2872 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  910): acquireWL(44066a10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/AlertService( 3839): start to updateAlertNotification!
D/PMS     (  910): acquireWL(440656b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029}
V/AlarmManager(  910): sending alarm PendingIntent{43dc0c58: PendingIntentRecord{44002b00 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
D/PMS     (  910): releaseWL(440656b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
,D/AccFlag ( 1222): sku_id=99
,D/AlertService( 3839): No fired or scheduled alerts
,D/HtcAlertUtils( 3839): -- cancelReminderNotification --
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4368 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
D/HtcAlertUtils( 3839): broadcastExistReminder!
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1340): [NET] getaddrinfo_proxy-, success
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  910): releaseWL(4400e508): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
W/AlertReceiver( 3839): stopSelfResult true
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
D/AccFlag ( 1222): sku_id=99
,W/WeatherRequest( 1109): request cur loc, but there is no sys cur
,D/libc    ( 1340): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1340): [NET] getaddrinfo-,err=8
I/ActivityManager(  910): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4383 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
,D/AccFlag ( 1222): sku_id=99
,W/WeatherUtility( 4368): can't get weather sync account
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4395 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/libc    ( 1340): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1340): [NET] getaddrinfo-,err=8
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1222): sku_id=99
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
D/PMS     (  910): acquireWL(43d565b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4383 10071 null
D/PMS     (  910): acquireWL(43d55ee8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4383 10071 null
W/WeatherRequest( 4368): request cur loc, but there is no sys cur
,W/Settings( 4368): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCM     ( 1340): GCM config loaded
D/PMS     (  910): releaseWL(43d565b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  910): acquireWL(43be60d0): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43be60d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4412 uid=10090 gids={50090, 3003, 5012, 1028}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/PMS     (  910): acquireWL(438e3950): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4395): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/TodoTaskshortcut( 4383): update TASK shortcut>
,W/dalvikvm( 4395): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/AppWidgetHostView( 1254): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/MultiDex( 4395): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4395): install
,I/RemoteViews( 1254): com.htc.widget.weatherclock (true,33751552)
,I/MultiDex( 4395): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,I/MultiDex( 4395): loading existing secondary dex files
,I/RemoteViews.Performance( 1254): com.htc.widget.weatherclock 2 10 17
,I/MultiDex( 4395): load found 3 secondary dex files
,I/MultiDex( 4395): install done
,I/TodoTaskNotifyService( 4383): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 4383): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
I/WorldClock.Global( 4412): isHtcDevice = true
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/dalvikvm( 4395): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4395): VFY: unable to resolve instance field 36
,W/dalvikvm( 4395): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  910): acquireWL(42581ad0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,I/WorldClock.Global( 4412): isHtcDevice = true
,V/JNIHelp ( 4395): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/NotifyReceiver( 4383): stopSelfResult true
W/ContextImpl( 3853): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): releaseWL(43d55ee8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,I/WorldClock.AlarmUtils( 4412): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
D/PMS     (  910): releaseWL(44066a10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4433 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1340/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,I/WorldClock.AlarmUtils( 4412): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4412): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,I/ProviderInstaller( 4395): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  910): releaseWL(42581ad0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/IntentController( 1109): receive(android.intent.action.ALARM_CHANGED,1,false)
D/PMS     (  910): acquireWL(4249d188): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1340/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1340/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/Process (  910): killProcessQuiet, pid=3897
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,I/ActivityManager(  910): Killing 3897:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TimeService( 4433): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450201664396
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/Process (  910): killProcessQuiet, pid=3623
,I/ActivityManager(  910): Killing 3623:com.android.vending/u0a74 (adj 15): empty #17
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/dalvikvm( 4395): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4395): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Process (  910): killProcessQuiet, pid=4047
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
I/ActivityManager(  910): Recipient 3897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
D/PMS     (  910): releaseWL(4249d188): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Killing 4047:com.htc.widget.process2/u0a50 (adj 15): empty #17
D/PMS     (  910): acquireWL(43768c30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43768c30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4395): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4395): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4395): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4395): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4395): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4047
,I/CheckinService( 1970): Checkin interval check for package: unspecified last checkin: 1450196925722 min interval config: 0 actual interval: 4738711
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): acquireWL(42543d00): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1970 10029 null
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
D/PMS     (  910): acquireWL(43658e48): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
D/PMS     (  910): releaseWL(42543d00): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
D/PMS     (  910): releaseWL(43658e48): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,D/NativeLibraryUtils( 4395): Install completed successfully. count=14 extracted=0
I/ActivityManager(  910): Recipient 3623
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4451 uid=10041 gids={50041}
,D/WVCdm   (  372): PrepareKeyRequest: nonce=4120313327
,I/ActivityManager(  910): Delay finish: com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent
,D/Process (  910): killProcessQuiet, pid=3984
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 3984:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3984
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WVCdm   (  372): CdmEngine::CloseSession
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4395): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4395): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4395): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4395): Local Branch: 
I/Adreno-EGL( 4395): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4395): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4395):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4395/10029)
,I/Adreno-EGL( 4395): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4395): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4395): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4395): Local Branch: 
I/Adreno-EGL( 4395): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4395): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4395):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4395): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4395): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4395): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4395): Local Branch: 
I/Adreno-EGL( 4395): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4395): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4395):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  910): Resuming delayed broadcast
,D/Process (  910): killProcessQuiet, pid=4002
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4002:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4002
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 1970): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/Icing   ( 1970): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(438e3950): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(440180c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
D/PMS     (  910): acquireWL(43918e70): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4383 10071 null
E/TodoTaskNotifyService( 4383): java.lang.NullPointerException
W/System.err( 4383): java.lang.NullPointerException
,W/System.err( 4383): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
D/PMS     (  910): acquireWL(4269f940): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4383 10071 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
D/PMS     (  910): acquireWL(44020698): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4383 10071 null
D/PMS     (  910): acquireWL(4269f940): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4383 10071 null
,D/PMS     (  910): releaseWL(43918e70): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/System.err( 4383): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4383): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4383): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4383): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
W/NotifyReceiver( 4383): stopSelfResult false
E/TodoTaskNotifyService( 4383): java.lang.NullPointerException
W/System.err( 4383): java.lang.NullPointerException
W/System.err( 4383): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4383): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4383): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4383): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4383): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/NotifyReceiver( 4383): mStartingService is null
W/NotifyReceiver( 4383): stopSelfResult true
D/PMS     (  910): releaseWL(44020698): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  910): releaseWL(4269f940): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  910): releaseWL(440180c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WearableService( 1203): callingUid 10029, callindPid: 1203
D/LocationInitializer( 1970): Restart initialization of location
D/AuthorizationBluetoothService( 1340): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1340): Proximity feature is not enabled.
E/MDM     ( 1203): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  910): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4477 uid=10078 gids={50078}
,W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1203): location=null
,D/SMSBackup( 4477): Got a database change event
D/PMS     (  910): acquireWL(43822018): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43822018): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  910): killProcessQuiet, pid=3330
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
I/ActivityManager(  910): Killing 3330:com.android.settings/1000 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3330
,D/WifiService(  910): Client connection lost with reason: 4
,W/Settings( 4395): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=565799470
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 1970): Classify the device as Phone.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/libc    ( 1970): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1970): [NET] getaddrinfo-,err=8
D/libc    ( 1970): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1970): [NET] getaddrinfo-, 1
,D/libc    ( 1970): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1c6d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,W/fb4a(:<default>):UserScope( 4248): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4248): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1970): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/libc    ( 1970): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1970): [NET] getaddrinfo-,err=8
,D/libc    ( 1970): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1970): [NET] getaddrinfo-,err=8
D/libc    ( 1970): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1970): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4248): Called registerBroadcastReceiver twice.
,I/CheckinTask( 1970): Sending checkin request (12245 bytes)
,D/PMS     (  910): acquireWL(4380ea60): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4196 10154 null
,W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4196, uid=10154, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
I/MusicLeanback( 4196): Conditions not met for autocaching.
,I/MusicLeanback( 4196): Stop autocaching.
,W/ContextImpl( 4196): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  910): releaseWL(4380ea60): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4248/10027)
,D/PMS     (  910): acquireWL(41aead38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10014}
,V/AlarmManager(  910): sending alarm PendingIntent{440f7240: PendingIntentRecord{43fc4b18 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=111007, Int=0
,D/PMS     (  910): acquireWL(4376f030): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4129 10014 null
,D/PMS     (  910): releaseWL(41aead38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(4376f030): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/CheckinRequestBuilder( 1970): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1970): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  910): releaseWL(439129c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (1970/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=4 [22][1][0]
,I/CheckinRequestBuilder( 1970): Classify the device as Phone.
,I/CheckinTask( 1970): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1970): Checking schedule, now: 1450201666918 next: 1450724603910
,I/CheckinService( 1970): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1970, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,D/CheckinService( 1970): Recording last checkin time for package unspecified as 1450201666944
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(44041bf8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1970/10029)
,D/GCM     ( 1340): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 4314): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=3407
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3407:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3407
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1324): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1324): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1324): service - requestNLP() NetworkLocationProvider not enabled
,D/Process (  910): killProcessQuiet, pid=4159,
,I/ActivityManager(  910): Killing 4159:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4159
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4512 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1254): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/Launcher( 1254): Deferring update until onResume
D/Launcher( 1254): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,W/SystemReader( 1237): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
,D/PhoneApp( 1222): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4512): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4512): MmsConfig.loadMmsSettings
,W/dalvikvm( 4512): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4512): VFY: unable to resolve instance field 36
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4535 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
W/dalvikvm( 4512): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4512): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4512, uid=10111, userID:0
,W/Settings( 4512): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4535): onCreate
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4512, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4512, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4512, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4512, uid=10111, userID:0
,V/GetPrviateResource( 4535): GetPrviateResource
,V/GetPrviateResource( 4535): GetPrviateResource
,D/MmsCustomizationProvider( 4535): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4512, uid=10111, userID:0
D/PMS     (  910): acquireWL(42350a60): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4512 10111 null
,D/MmsCustomizationProvider( 4535): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1324): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1324): handle notify Blinkfeed plugin client changed
I/Babel   ( 4512): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4512): MmsConfig.loadFromDatabase
I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2594): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/Babel   ( 4512): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4512): MmsConfig.loadFromResources
,E/Babel   ( 4512): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4512): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  910): acquireWL(440a5a30): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(440a5a30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42350a60): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  910): acquireWL(426a25c8): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  910): killProcessQuiet, pid=4300
,I/ActivityManager(  910): Killing 4300:com.google.android.setupwizard/u0a79 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4300
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MessageCustFlag( 4535): sense_version=6.0
D/BTAccessoryUtil( 4535): createReceiver
D/BTAccessoryUtil( 4535): registerReceiver return intent = null
D/MessageCustFlag( 4535): sku_id=99
W/SystemReader( 4535): Cannot find message_ambs_application_id, use default value instead
I/ProviderInstaller( 4512): Installed default security provider GmsCore_OpenSSL
,D/Messaging( 4535): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4535): networkCode: 
,D/MessageCustFlag( 4535): sku_id=99
D/MmsConfig( 4535): SIE smsPri: null
,D/MmsConfig( 4535): networkCode: 
D/HtcTelephonyCapability( 4535): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4535): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4535): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4535): Cannot find qct_8960_interface, use default value instead
,W/PackageManager(  910): Unable to load service info ResolveInfo{44199550 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PMS     (  910): releaseWL(426a25c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42597d88): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(437bcb80): PARTIAL_WAKE_LOCK  AsyncService 0x1 3594 10160 null
,D/PMS     (  910): releaseWL(437bcb80): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(42597d88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4562 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  910): acquireWL(437ea4e8): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,D/PMS     (  910): releaseWL(437ea4e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreNlp( 1203): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  910): acquireWL(437eb6c8): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/HtcFingerPrintQuickLaunchProvider( 4562): -onCreate()
,V/Settings:HtcSettingsApplication( 4562): [4562/4562] onCreate()
D/PMS     (  910): releaseWL(437eb6c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4579 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Killing 4224:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4224
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(4383e1c0): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(426c0090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(426c0090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43803878): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43803878): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(438c57d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4383e1c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(438c57d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(425be4f0): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(425be4f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(437a1928): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Recipient 4224
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/PMS     (  910): releaseWL(437a1928): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(425b6510): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(425b6510): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Settings:HtcWirelessFeatureFlags( 4562): id/is att sku: 99/false
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4579, uid=10074, userID:0
,W/SystemReader( 4562): Cannot find devicepolicy_lower_fp_quality, use default value instead
D/PMS     (  910): acquireWL(43e4fb70): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 4579): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/SystemReader( 4562): Cannot find support_harman, use default value instead
,W/SystemReader( 4562): Cannot find effect_manager_id, use default value instead
D/PMS     (  910): releaseWL(43e4fb70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4579/10074)
,E/Settings:HtcWrapHeaderInfo( 4562): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4562): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4562): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4562): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]support         :false
,I/IcingCorporaProvider( 2594): UpdateCorporaTask done [took 532 ms] updated apps [took 532 ms] 
,W/FingerprintManager( 4562): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4562): isSupportVoWifi: null
I/ActivityManager(  910): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4562): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4579/10074)
,D/Finsky  ( 4579): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4579): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4579): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4579, uid=10074, userID:0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4562): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4562): updateDevelopment, bPrefShow = true
,D/Ads     ( 4579): Skipping gmscore version check
,E/Settings:HtcUmcWidgetEnabler( 4562): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4562): [supportHomeButton]support         :false
,D/Finsky  ( 4579): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4579): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4579): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/FingerprintManager( 4562): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4562): isSupportVoWifi: null
I/ActivityManager(  910): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4562): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4579): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1970): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Process (  910): killProcessQuiet, pid=4314
,I/ActivityManager(  910): Killing 4314:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageBroadcastService( 1970): Null package name or gms related package.  Ignoreing.
,D/PMS     (  910): acquireWL(4378f458): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1970): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  910): Recipient 4314
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1254): loadItems() com.htc.launcher.pageview.WidgetManager@41b5eeb0 +
,I/Prism.WidgetManager( 1254): onLoadItems() +
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44132ad0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,E/Prism.WidgetManager( 1254): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1254): onLoadItems() -
,I/Prism.ItemManager( 1254): loadItems() com.htc.launcher.pageview.WidgetManager@41b5eeb0 -
,D/PhoneApp( 1222): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1222): -- N1 =0
,D/PhoneApp( 1222): -- N2 =0
,D/PhoneApp( 1222): -- N3 =0
,I/Icing   ( 1970): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1970): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(4378f458): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4535): mNeedToUpdateDate2 start
,D/MmsConfig( 4535): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4535): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4535): 
D/MmsAsyncWorkHandler( 4535): HM tk = 20001
,D/ReportIndicatorCache( 4535): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4535): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ad52c8
,I/Messaging( 4535): mccmnc> 
D/DraftCache( 4535): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4535): [DraftCache/1] refresh
,D/MmsConfig( 4535): networkCode: 
,D/Messaging( 4535): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/MmsSmsV2Provider( 1222):  phoneType = -1
,D/MmsSmsV2Provider( 1222): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4535): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4535): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4535): createReceiver
,D/MessageCustFlag( 4535): sense_version=6.0
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1222):  phoneType = -1
D/MmsSmsV2Provider( 1222): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Jerry   ( 4535): start to preload cursor >>>>>>>
,D/TelephUtils( 1222): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,V/MmsProvider( 1222): Update uri=content://mms, match=0
,V/MmsProvider( 1222): selection=st=129 AND m_type!=134
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1222):  phoneType = -1
,D/MmsSmsV2Provider( 1222): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4535): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4535): TransactionService is going to be woken up.
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1222):  phoneType = -1
,D/Messaging( 4535): mNeedToUpdateDate2: false
,V/TransactionService( 4535): 1-Creating TransactionService
V/TransactionService( 4535): onStartCommand: 1
D/MmsSystemEventReceiver( 4535): unRegisterForConnectionStateChanges
V/TransactionService( 4535): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4535): Loading previous transactions.
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1222): sku_id=99
D/Messaging( 4535): ViewCache CreatePreload
,D/Messaging( 4535): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/Cust_MMSMS( 4535): _has_set_default_values_2=true
,D/AccFlag ( 1222): device_type: 1
,D/DraftCache( 4535): [DraftCache/451] rebuildCache
D/TransactionService( 4535): Force set service start id to 1
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1222):  phoneType = -1
V/TransactionService( 4535): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSmsV2Provider( 1222): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MmsSystemEventReceiver( 4535): unRegisterForConnectionStateChanges
D/MsgPreferenceUtils( 4535): def_index: 0
D/TransactionService( 4535): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4535): Destroying TransactionService
,D/MsgPreferenceUtils( 4535): globalIndex = 1
,V/TransactionService( 4535): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 4535): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/Jerry   ( 1222): URI_DRAFT
D/MsgPreferenceUtils( 4535): phone state: true
D/MsgPreferenceUtils( 4535): sd state: false
,D/MsgPreferenceUtils( 4535): vIndex = 0
,D/DraftCache( 4535): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4535): [DraftCache/451] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4535): 
D/MmsAsyncWorkHandler( 4535): HM tk = 20002
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1222): sku_id=99
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1222): sku_id=99
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4512): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(4390f7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=124646, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4390f7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4374ea68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4374ea68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(437bf718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{438cd348: PendingIntentRecord{4250e860 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134791, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/PMS     (  910): releaseWL(437bf718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4365d680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c9ba30: PendingIntentRecord{424b6160 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=135752, Int=0
,D/PMS     (  910): acquireWL(4360e678): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): releaseWL(4365d680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(44029da0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(4360e678): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(44029da0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1324): service - mHandler: update timezone
,D/AutoSetting( 1324): service - handleMessage() stop self
,D/AutoSetting( 1324): service - handleMessage() quit looper
,D/AutoSetting( 1324): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=3839
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3839:com.htc.calendar/u0a13 (adj 15): empty #17
,D/AutoSetting( 4129): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4129): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4129): service - onCreate()
,D/AutoSetting( 4129): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4129): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4129): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 4129): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4129): service - mHandler: update timezone
,D/AutoSetting( 4129): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4129): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4129): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4129): service - showManualTimeZoneSelector() send notification (single)
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 3839
,D/DotMatrix( 1506): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1506): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1109): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b1a540 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.htc.htclocationservice 2 8 3 11
,D/PMS     (  910): acquireWL(43b66f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{4409f710: PendingIntentRecord{4271d5a8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=139833, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{42516880: PendingIntentRecord{42516518 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141172, Int=0
,D/PMS     (  910): acquireWL(4418a460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(440cf128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4418a460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(440cf128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440ab220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(440ab220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440a0ac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(44064de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440535f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1203): Vacuum at: now=1450201696886 tag=VacuumService
D/PMS     (  910): releaseWL(440a0ac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): acquireWL(44046128): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(43b66f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024,
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d49a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  910): releaseWL(44064de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(422115a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(422115a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4255bd48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/PMS     (  910): releaseWL(440535f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(4255bd48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4231e048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(4231e048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(423445d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(423445d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43fd00f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): acquireWL(43b5bc90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43fd00f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43b5bc90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(437cf290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(437cf290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(44046128): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1222): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1222): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43ffccc0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(43894ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43894ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4253dcd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c9ba30: PendingIntentRecord{424b6160 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=165774, Int=0
,D/PMS     (  910): acquireWL(441551c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
D/PMS     (  910): releaseWL(4253dcd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(41eb0400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=6 [33][2][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(424607d0): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 910 1000 WorkSource{10029}
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(441551c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(41eb0400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(431a4468): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/ActivityManager(  910): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1970): Failed to find provider info for com.android.contacts.metadata
,D/PMS     (  910): releaseWL(431a4468): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42612e40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(424607d0): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/SyncManager(  910): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 25524, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 165882, reason: UserStart
D/PMS     (  910): releaseWL(42612e40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43876038): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1518/10029)
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): releaseWL(43876038): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4129): service - handleMessage() stop self
,D/AutoSetting( 4129): service - onDestroy() END
,D/AutoSetting( 4129): service - handleMessage() quit looper
D/Process (  910): killProcessQuiet, pid=4368
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4368:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4368
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1222): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(43befd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=184647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43befd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43817a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(43817a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4409fee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c9ba30: PendingIntentRecord{424b6160 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=195833, Int=0
,D/PMS     (  910): acquireWL(438ccf90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): releaseWL(4409fee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4345ab00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(438ccf90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(4345ab00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(43fd8490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43fd8490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43841038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=244647, Int=0
I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43841038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43797500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(43797500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(4401b898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4401b898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(438115b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=304647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(438115b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4383fa98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(4383fa98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(441693f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(441693f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(437c64d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=364647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(437c64d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42403078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(42403078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(4378b628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4378b628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4579): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4579): [NET] getaddrinfo-,err=8
D/libc    ( 4579): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4579): [NET] getaddrinfo-, 1
,D/libc    ( 4579): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5df4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4579): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  910): acquireWL(4417fd18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=424646, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1254): Grow heap (frag case) to 12.650MB for 50416-byte allocation
,D/PMS     (  910): releaseWL(4417fd18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3912): Connected to the server!
I/jxcore-log( 3912): 
,I/chromium( 3912): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  910): acquireWL(4382db70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(4382db70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3912): --- start :testFindPeers.js---
I/jxcore-log( 3912): 
,I/jxcore-log( 3912): testFindPeers created [object Object]
I/jxcore-log( 3912): 
,I/jxcore-log( 3912): serverPort is 8876
I/jxcore-log( 3912): 
W/dalvikvm( 3912): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 3912): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 3912): threadid=1: thread exiting with uncaught exception (group=0x4169ae30)
E/AndroidRuntime( 3912): FATAL EXCEPTION: main
E/AndroidRuntime( 3912): Process: com.test.thalitest, PID: 3912
E/AndroidRuntime( 3912): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 3912): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 3912): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 3912): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 3912): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 3912): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 3912): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 3912): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 3912): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 3912): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 3912): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3912): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3912): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 3912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 3912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 3912): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  910): App crashed! Process: com.test.thalitest
W/ActivityManager(  910):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager(  910): Killing 4412:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4412
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 ,
D/Process ( 3912): killProcess, pid=3912
D/Process ( 3912): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  910): Recipient 4412
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3912
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Process com.test.thalitest (pid 3912) has died.
,I/WindowState(  910): WIN DEATH: Window{43248220 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 3912 uid 10389
,D/PMS     (  910): acquireWL(42339e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42339e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43b377c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=484647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b377c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(437afa70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(437afa70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(437a4038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(437a4038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1109): closing low battery warning: level=100
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43823500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=544646, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43823500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4362e968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4362e968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(425de360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425de360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(422fb360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=604647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(422fb360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4257d120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4257d120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1222): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1222): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1222): sku_id=99
D/ContactMessageStore( 1222): start background delete task...
,D/ContactMessageStore( 1222): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1222): size: 0 , 0
,D/ContactMessageStore( 1222): Background delete complete,
,D/PMS     (  910): acquireWL(440b9498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,I/BatteryService(  910): n_update end
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(440b9498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4410d1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=664646, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1254): Grow heap (frag case) to 12.663MB for 50416-byte allocation
D/PMS     (  910): releaseWL(4410d1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4400cb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/PMS     (  910): releaseWL(4400cb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4271da10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=724647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4271da10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43b31a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,D/PMS     (  910): releaseWL(43b31a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4376b728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(4376b728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(437b81b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=784647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(437b81b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430c6ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430c6ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(432cfb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=844647, Int=0
,I/dalvikvm-heap( 1254): Grow heap (frag case) to 12.662MB for 50416-byte allocation
D/PMS     (  910): releaseWL(432cfb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430e8828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430e8828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43787e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=904647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43787e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c61208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(43c61208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43769c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43769c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(438950b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=964647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(438950b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(426d1138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(426d1138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4303efa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  910): sending alarm PendingIntent{41d2d0b0: PendingIntentRecord{4245bff8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781989, Int=0
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4706 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
V/AlarmManager(  910): sending alarm PendingIntent{4237b3b0: PendingIntentRecord{425fb868 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450201767961, Int=10800000
,V/AlarmManager(  910): sending alarm PendingIntent{43bf2810: PendingIntentRecord{4271a6d8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450201812768, Int=1800000
V/AlarmManager(  910): sending alarm PendingIntent{423e4cb8: PendingIntentRecord{425d6750 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450202488197, Int=900000
,V/AlarmManager(  910): sending alarm PendingIntent{41e0ea50: PendingIntentRecord{43bfc180 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450202560890, Int=0
,D/PMS     (  910): acquireWL(4247afd0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43b33c88): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4247afd0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4718 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/EventLogService( 1970): Aggregate from 1450201663516 (log), 1450200012704 (data)
,W/ContextImpl( 4718): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4718): call getInstance()
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4706/10049)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
D/PMS     (  910): releaseWL(43b33c88): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4718): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4718): MY_DEBUG = false
D/PMS     (  910): acquireWL(43bce000): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4718 1000 null
D/PMS     (  910): releaseWL(4303efa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): releaseWL(43bce000): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  910): killProcessQuiet, pid=3853
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3853:com.android.settings:remote/1000 (adj 15): empty #17
D/PMS     (  910): acquireWL(4268b0d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4718 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4718): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4718): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4718): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4718): SettingOnTime = 1450245600000, randomSettingOnTime = 1450245177000
,D/SmartSyncScreenOnOffTimeReceiver( 4718): SettingOffTime = 1450231200000, randomSettingOffTime = 1450233964000
,D/SmartSyncScreenOnOffTimeReceiver( 4718): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4718): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4718): bNightModeTurnOffOnce = false
,D/PMS     (  910): releaseWL(4268b0d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  910): Recipient 3853
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/BluetoothSapService( 3958): onUnbind: android.bluetooth.IBluetoothSap
D/WifiService(  910): Client connection lost with reason: 4
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(437a3750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PMS     (  910): releaseWL(437a3750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/Process (  910): killProcessQuiet, pid=4433
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4433:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4433
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(42bf18d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{4255c8b8: PendingIntentRecord{425102a8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1009052, Int=0
,D/PMS     (  910): acquireWL(4271c258): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4271c258): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4268fa60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42bf18d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=8 [158][13][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): acquireWL(4240c7f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1340/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(4240c7f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(41d65678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4268fa60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1203): Scheduling Phenotype for one-off execution 8842 seconds from now (1450202564894)
,D/GetConfigurationSnapshotOperation( 1203): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,I/PhenotypeFlagCommitter( 1203): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1203): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1203): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1203): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1203): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1203): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/libc    ( 1203): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/libc    ( 1203): [NET] getaddrinfo-,err=8
D/libc    ( 1203): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1203): [NET] getaddrinfo-, 1
,D/libc    ( 1203): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1366 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1203): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1203): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
D/libc    ( 1203): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=20 [10][2][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(41d65678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4379ec88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(4379ec88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(437ab780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1340/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4017): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4017): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4017): nl80211: survey data missing!
E/wpa_supplicant( 4017): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4017): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025137
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025279
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025347
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025356
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025360
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026665
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026679
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029282
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360106643
,D/PMS     (  910): releaseWL(437ab780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(424f0b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1024647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1254): Grow heap (frag case) to 12.710MB for 50416-byte allocation
,D/PMS     (  910): releaseWL(424f0b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(440aa318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(440aa318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(438cdf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(438cdf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43bf7e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1084646, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43bf7e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43664340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43664340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43dc0dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43dc0dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43fdf180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1144647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43fdf180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(431a9d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(431a9d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43c12ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/PMS     (  910): releaseWL(43c12ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(425ef398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1204647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425ef398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4247bf80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(4247bf80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(430eb160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430eb160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1109): closing low battery warning: level=100
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44055af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1264647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44055af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43bef608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43bef608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(437b58d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1324646, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(437b58d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43a96bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43a96bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4312e0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1384646, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4312e0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(437da8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(437da8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(44161bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(44161bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43c35bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1444647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43c35bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(437c5cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(437c5cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43bae560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43bae560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(437e67c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1504647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(437e67c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43863e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PMS     (  910): releaseWL(43863e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(438e6848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(438e6848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43b31988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1564647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b31988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4255cc38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4255cc38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4382ddf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1624647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4382ddf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4240ff78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4240ff78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43794b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43794b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/DotMatrix( 1506): [EventService] reorderNotification, total:1
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 3958): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=98
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
W/ContextImpl( 4718): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4562): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4562): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4562): Cust_ConnectToPC   : Modem_Link>false
I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
D/        ( 4562): Cust_ConnectToPC   : spcsc>false
D/        ( 4562): Cust_ConnectToPC   : IPT>true
,D/        ( 4562): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4562): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4562): Index of the first 1 = -1
W/ContextImpl( 4562): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 4562): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4562): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4562): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4562): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4562): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4562): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  910): acquireWL(43fbdad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1684647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43fbdad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4257b460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=98
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(4257b460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(432a4228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(432a4228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(438e2a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1744647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(438e2a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4252a2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(4252a2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=98
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(438413e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1804646, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(438413e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42398a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42398a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=98
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:2 level:98 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  910): acquireWL(43910878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{422c94a0: PendingIntentRecord{420c04c8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1864647, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  910): Prepared write state in 33ms
,I/ProcessStatsService(  910): Prepared write state in 15ms,
,D/PMS     (  910): releaseWL(43910878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2015-12-15-05-01-16.bin
,D/PMS     (  910): acquireWL(4379a678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4379a678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(437b64d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1506): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1506): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=99
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(437b64d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1109): status:2 level:99 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4779): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4779): ====startRecUseTime====
D/htc.customization.log.level( 4779):  is 
W/CustomizationLogLevel( 4779): Level value is invalid, use default level 2
D/CustomizationManager( 4779):  Read ACC file spent 0.100 (s)
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4779): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4779): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4779): Parsing tag category name = system
I/CustomizationCIDLoader( 4779): Parsing tag category name = application
I/CustomizationCIDLoader( 4779): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4779): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4779): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4779): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4779): Parsing tag category name = Settings
D/CustomizationManager( 4779):  Read CID file spent 0.152 (s)
D/CustomizationManager( 4779):  All configurations done spent 0.152 (s)
W/HtcNativeFlag( 4779): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4779): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4779): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4779): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4779, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/asset   (  910): Copying FileAsset 0x67b30aa0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  910): Skipping PackageSetting{42289e90 com.example.hello/10397} due to missing metadata
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1506): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1506): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1506): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
D/PMS     (  910): acquireWL(437ba868): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1203): Ignoring removeGeofence because network location is disabled.
I/dalvikvm-heap( 3594): Grow heap (frag case) to 13.540MB for 1821008-byte allocation
D/PMS     (  910): releaseWL(437ba868): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1254): Deferring update until onResume
D/Launcher( 1254): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1278): Cleaning up data for package: com.test.thalitest
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
W/SystemReader( 1237): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/[PluginManager]RegisterService( 1324): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  910):   Scheme: "smsto"
D/Prism.PackageStateRece_( 1254): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/[PluginManager]RegisterService( 1324): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/IcingCorporaProvider( 2594): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ExternalAccountType( 1309): Unsupported attribute readOnly
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4793 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
D/PhoneApp( 1222): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  910): acquireWL(43c5aaf8): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43c5aaf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43c59cb0): PARTIAL_WAKE_LOCK  Icing 0x1 1970 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2594): UpdateCorporaTask done [took 286 ms] updated apps [took 286 ms] 
W/PackageManager(  910): Unable to load service info ResolveInfo{424688e0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4793): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4793): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4793): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4793): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4793): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4793): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4793): threadid=11: thread exiting with uncaught exception (group=0x4169ae30)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4793): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4793): Process: com.google.android.apps.docs, PID: 4793
E/AndroidRuntime( 4793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4793): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4793): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4793): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4793): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4793): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4793): 	at aho.run(AbstractDatabaseInstance.java:455)
E/SQLiteDatabase( 4793): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4793): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4793): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4793): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4793): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4793): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4793): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4793): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4793): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4793): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4793): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4793): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4793): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4793): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4793): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4793): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4793): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4793): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4793): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4793): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4793): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4793): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4793): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4793): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4793): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4793): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4793): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4793): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4793): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4793): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4793): Opened ClientFlag.db in read-only mode
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4793): killProcess, pid=4793
D/Process ( 4793): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4812 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/BroadcastQueue(  910): Skipping deliver [background] BroadcastRecord{43bf2fc0 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{437dd540 4793 com.google.android.apps.docs/10100/u0 remote:438477a8}: process crashing
I/ActivityManager(  910): Recipient 4793
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4793) has died.
D/PMS     (  910): acquireWL(4312e608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{41d2d0b0: PendingIntentRecord{4245bff8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1725586, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{41f12dc0: PendingIntentRecord{42595b48 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820703, Int=1800000
V/AlarmManager(  910): sending alarm PendingIntent{423b5660: PendingIntentRecord{4257bf18 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1846322, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{432c16b8: PendingIntentRecord{43fd81e0 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1861668, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{41e5b358: PendingIntentRecord{425102a8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1909127, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{423e4cb8: PendingIntentRecord{425d6750 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450203388197, Int=900000
W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4812): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4812): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4812): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4812): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4812): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4812): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4812): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4812): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4812): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4812): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4812): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4812): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4812): threadid=10: thread exiting with uncaught exception (group=0x4169ae30)
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4826 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  910): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4812): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4812): Process: com.android.keychain, PID: 4812
E/AndroidRuntime( 4812): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4812): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4812): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4812): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4812): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4812): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4812): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4812): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4812): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4812): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4812): killProcess, pid=4812
D/Process ( 4812): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450203464635.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  910): Recipient 4812
I/ActivityManager(  910): Process com.android.keychain (pid 4812) has died.
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4826): getInstance(Context context)
D/AppTag  ( 4826): getInstance(Context context)
D/AppTag  ( 4826): onCreate()
I/dalvikvm-heap( 3594): Grow heap (frag case) to 15.233MB for 1821008-byte allocation
W/dalvikvm( 4579): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PMS     (  910): acquireWL(424dcef0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3594 10160 null
D/PackageBroadcastService( 1970): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1970): Clearing selected account for com.test.thalitest
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/dalvikvm-heap( 3594): Grow heap (frag case) to 16.970MB for 1821008-byte allocation
D/PMS     (  910): releaseWL(424dcef0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  910): Resuming delayed broadcast
I/LocationSettingsChecker( 1970): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  910): Delay finish: com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
E/SQLiteLog( 1970): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1970): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65603b20
E/DriveAsyncService( 1970): disk I/O error (code 3850)
E/DriveAsyncService( 1970): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1970): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1970): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1970): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1970): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1970): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1970): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1970): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1970): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1970): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1970): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1970): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1970): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1970): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1970): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1970): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 1970): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1970): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1970): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1970): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1970): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1970): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1970): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 1970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1970): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1970): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1970): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 1970): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1970): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1970): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1970): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1970): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1970): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1970): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1970): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1970): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1970): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1970): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1970): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1970): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1970): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1970): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1970): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1970): threadid=48: thread exiting with uncaught exception (group=0x4169ae30)
E/ActivityManager(  910): App crashed! Process: com.google.android.gms
D/Process ( 1970): killProcess, pid=1970
D/Process ( 1970): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 1970): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1970): Process: com.google.android.gms, PID: 1970
E/AndroidRuntime( 1970): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1970): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1970): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1970): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1970): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1970): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1970): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1970): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1970): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1970): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1970): 	at android.os.HandlerThread.run(HandlerThread.java:61)
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
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  910): handleWLDeath(43c59cb0): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  910): Recipient 1970
I/ActivityManager(  910): Process com.google.android.gms (pid 1970) has died.
D/WifiService(  910): Client connection lost with reason: 4
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
I/ActivityManager(  910): Resuming delayed broadcast
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10997ms
I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1254): loadItems() com.htc.launcher.pageview.WidgetManager@41b5eeb0 +
I/Prism.WidgetManager( 1254): onLoadItems() +

```
