#### Test 5065027857de7f1_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  915): acquireWL(44053fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10074}
V/AlarmManager(  915): sending alarm PendingIntent{42584960: PendingIntentRecord{4256f7d8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449832297353, Int=0
I/ActivityManager(  915): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3877 uid=10078 gids={50078}
V/AlarmManager(  915): sending alarm PendingIntent{4237dd30: PendingIntentRecord{422ba3c0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449832303954, Int=60000
D/PMS     (  915): releaseWL(44053fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,--------- beginning of /dev/log/main
D/SMSBackup( 3877): SMSBackupAgentService started
D/SMSBackup( 3877): Checking restore status
D/SMSBackup( 3877): Restore complete
D/SMSBackup( 3877): cancelCheckAlarm
D/SMSBackup( 3877): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
D/Finsky  ( 3601): [374] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3601): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  915): killProcessQuiet, pid=3675
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3675:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
E/cutils-trace( 3892): Error opening trace file: No such file or directory (2)
I/ActivityManager(  915): Recipient 3675
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  915): Client connection lost with reason: 4
D/CustomizationManager( 3892): ====startRecUseTime====
D/htc.customization.log.level( 3892):  is 
W/CustomizationLogLevel( 3892): Level value is invalid, use default level 2
D/CustomizationManager( 3892):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3892): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3892): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3892): Parsing tag category name = system
I/CustomizationCIDLoader( 3892): Parsing tag category name = application
I/CustomizationCIDLoader( 3892): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3892): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3892): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3892): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3892): Parsing tag category name = Settings
D/CustomizationManager( 3892):  Read CID file spent 0.111 (s)
D/CustomizationManager( 3892):  All configurations done spent 0.111 (s)
W/HtcNativeFlag( 3892): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3892): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3892): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3892): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  915): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  915): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  915): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  915): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  915): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  915): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  915): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3892
D/PMS     (  915): acquireHCC(4370f670): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 915 1000 null
D/PMS     (  915): acquireHCC(4370d040): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 915 1000 null
W/asset   (  915): Copying FileAsset 0x6aae7708 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  915): @test_code: getHtcIntentFlag: 0 obj: 1131426144
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
D/PMS     (  915): acquireWL(43706700): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 915 1000 null
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bf7008
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
I/ActivityManager(  915): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3903 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1250): [trimMemory] 20
W/asset   ( 3903): Copying FileAsset 0x5c86a428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3903): Binding Chromium to main looper Looper (main, tid 1) {41b06a28}
I/LibraryLoader( 3903): Expected native library version number "",actual native library version number ""
I/chromium( 3903): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3903): Initializing chromium process, renderers=0
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  915): java.lang.Throwable: stack dump
D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423024b8:true
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3903): 1102171880: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  915): acquireWL(42453c88): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  915): acquireWL(4241e8b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  915): releaseWL(42453c88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3903): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3903): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3903): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3903): Local Branch: 
I/Adreno-EGL( 3903): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3903): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3903):                  aa63bbd948f41d15fc72f585e
W/chromium( 3903): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3903): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3903): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3903): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3903): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3903): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3903): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3903): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
V/LightsService(  915): setLight #0: color=#3e
W/dalvikvm( 3903): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3903): CordovaWebView is running on device made by: HTC
,V/LightsService(  915): setLight #0: color=#3b
V/LightsService(  915): setLight #0: color=#34
V/LightsService(  915): setLight #0: color=#2d
W/AwContents( 3903): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  915): Disable input method client, pid=1250
I/InputMethodManagerService(  915): Enable input method client, pid=3903
W/ResourceType( 3903): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3903): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b4e4b0, mServedView=org.apache.cordova.engine.SystemWebView{41b14200 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3903): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  915): Displayed com.test.thalitest/.MainActivity: +297ms
V/LightsService(  915): setLight #0: color=#27
D/PMS     (  915): releaseWL(43706700): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
V/LightsService(  915): setLight #0: color=#20
V/LightsService(  915): setLight #0: color=#19
V/LightsService(  915): setLight #0: color=#14
D/JsMessageQueue( 3903): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3903): JniHelper::setJavaVM(0x416c6010), pthread_self() = 1662442152
D/JX-Cordova( 3903): jxcore cordova android initializing
W/dalvikvm( 3903): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
I/SensorManager(  915): mEventCount = 900
,I/dalvikvm-heap( 3903): Grow heap (frag case) to 11.643MB for 144892-byte allocation
,I/dalvikvm-heap( 3903): Grow heap (frag case) to 11.758MB for 217334-byte allocation
,I/dalvikvm-heap( 3903): Grow heap (frag case) to 11.923MB for 325996-byte allocation
,I/dalvikvm-heap( 3903): Grow heap (frag case) to 12.198MB for 488990-byte allocation
,I/dalvikvm-heap( 3903): Grow heap (frag case) to 12.603MB for 733480-byte allocation
,I/dalvikvm-heap( 3903): Grow heap (frag case) to 14.108MB for 1650320-byte allocation
,I/dalvikvm-heap( 3903): Grow heap (frag case) to 15.466MB for 2475476-byte allocation
,W/CpuWake (  915): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  915): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  915): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  915): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  915): >>release mCpuPerf_Freq wakelock
W/CpuWake (  915): <<release mCpuPerf_Freq wakelock
D/PMS     (  915): releaseHCC(4370f670): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  915): releaseHCC(4370d040): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3903): Grow heap (frag case) to 17.583MB for 3713210-byte allocation
,W/jxcore-log( 3903): Initializing JXcore engine
,W/jxcore-log( 3903): JXcore engine is ready
,W/jxcore-log( 3903): Starting JXcore engine
,W/jxcore-log( 3903): Platform android
W/jxcore-log( 3903): 
,W/jxcore-log( 3903): Process ARCH arm
W/jxcore-log( 3903): 
,I/jxcore-log( 3903): JXcore Cordova bridge is ready!
I/jxcore-log( 3903): 
,W/jxcore-log( 3903): JXcore engine is started
,I/chromium( 3903): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/PMS     (  915): releaseWL(4241e8b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3903): Toggling radios to true
I/jxcore-log( 3903): 
,D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  915): checking for enable restriction...
,D/BluetoothManagerService(  915): checkBTEasState, ret=true
I/BluetoothManagerService(  915): isBluetoothRestricted(): false
,D/BluetoothManagerService(  915): enable(): region ID = 6
D/BluetoothManagerService(  915): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  915): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  915): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  915): Settings:Agentvalue: 1
W/Settings:Agent(  915): >> traceCallingStack()
W/Settings:Agent(  915): Process.myPid(): 915
,W/Settings:Agent(  915): Process.myTid(): 926
W/Settings:Agent(  915): Process.myUid(): 1000
W/Settings:Agent(  915): 
,W/Settings:Agent(  915): 
,W/System.err(  915): java.lang.Throwable: stack dump
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  915): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  915): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  915): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  915): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  915): 
,W/Settings:Agent(  915): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  915): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  915): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3903): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  915): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  915): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  915): Settings:Agentvalue: 2
W/Settings:Agent(  915): >> traceCallingStack()
W/Settings:Agent(  915): Process.myPid(): 915
W/Settings:Agent(  915): Process.myTid(): 1245
W/Settings:Agent(  915): Process.myUid(): 1000
W/Settings:Agent(  915): 
W/Settings:Agent(  915): 
,W/System.err(  915): java.lang.Throwable: stack dump
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  915): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  915): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  915): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  915): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  915): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  915): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  915): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  915): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  915): 
,W/Settings:Agent(  915): << traceCallingStack(): 0(ms)
D/WifiService(  915): setWifiEnabled: true pid=3903, uid=10389
E/WifiService(  915): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  915): New client listening to asynchronous messages
I/WifiService(  915): isSprintWifiRestricted(): false
I/WifiService(  915): isMdmWifiRestricted(): false
D/WifiSettingsStore(  915): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,I/ActivityManager(  915): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3949 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3903): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 3903): reconnect: Base Package Name=com.test.thalitest, uid=10389
,D/PMS     (  915): acquireWL(41bf5aa0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 915 1000 null
I/jxcore-log( 3903): Radios toggled
I/jxcore-log( 3903): 
D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3903): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3903): 
I/jxcore-log( 3903): Perf Test app loaded loaded
I/jxcore-log( 3903): 
,I/jxcore-log( 3903): check test folder
I/jxcore-log( 3903): 
,I/jxcore-log( 3903): found test : ./testFindPeers.js
I/jxcore-log( 3903): 
,I/jxcore-log( 3903): found test : ./testSendData.js
I/jxcore-log( 3903): 
,D/AdapterServiceConfig( 3949): Adding HeadsetService
D/AdapterServiceConfig( 3949): Adding A2dpService
D/AdapterServiceConfig( 3949): Adding HidService
D/AdapterServiceConfig( 3949): Adding HealthService
D/AdapterServiceConfig( 3949): Adding PanService
,D/AdapterServiceConfig( 3949): Adding GattService
,W/linker  ( 3949): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3949): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  915): java.lang.Throwable: stack dump
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43471160:true
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapterState( 3949): make
,I/BluetoothAdapterState( 3949): Entering OffState
,I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3949): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:1 len:14
D/BluetoothManagerService(  915): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  915): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  915): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  915): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  915): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapter( 1198): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41dc26c8
D/BluetoothAdapter( 1198): onBluetoothServiceUp done
D/BluetoothAdapter( 3903): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42643490
D/BluetoothAdapter( 3903): onBluetoothServiceUp done
D/BluetoothAdapter( 3949): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b1fdc8
,D/BluetoothAdapter( 3949): onBluetoothServiceUp done
D/BluetoothAdapter( 1110): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41cb88a8
D/BluetoothAdapter( 1110): onBluetoothServiceUp done
D/BluetoothAdapter(  915): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4211c0c0
,D/BluetoothAdapter(  915): onBluetoothServiceUp done
,D/BluetoothAdapter( 1225): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c39de8
,D/BluetoothAdapter( 1225): onBluetoothServiceUp done
,D/BluetoothAdapter( 1213): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41da8b08
D/BluetoothAdapter( 1213): onBluetoothServiceUp done
,D/BluetoothManagerService(  915): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3949): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3949): Setting state to 11
I/BluetoothAdapterState( 3949): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3949): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  915): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  915): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  915): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  915): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3949): make
,I/IntentController( 1110): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3949): StableState(): Entering Off State
D/PMS     (  915): acquireWL(433e75e8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1198 10029 null
D/PMS     (  915): releaseWL(433e75e8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  915): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3974 uid=10040 gids={50040, 3002, 3001}
,D/HeadsetService( 3949): Received start request. Starting profile...
D/HeadsetStateMachine( 3949): Version 1.6
,D/HeadsetStateMachine( 3949): make
,I/HeadsetStateMachine( 3949): setCurrentDevice, the latest mCurrentDevice is:null
,I/QuickSettingBluetooth( 1110): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,I/BluetoothAdapterState( 3949): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/A2dpService( 3949): Received start request. Starting profile...
V/Avrcp   ( 3949): make
,D/Avrcp   ( 3949): fillIntentFilter()
,D/A2dpStateMachine( 3949): make
,D/A2dpStateMachine( 3949): Enter Disconnected: -2
,D/HtcBtWidget_BTWidgetProvider( 3974): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3974): updateWidget(context) for widget: 
,D/HidService( 3949): Received start request. Starting profile...
,D/HealthService( 3949): Received start request. Starting profile...
,D/Process (  915): killProcessQuiet, pid=3366
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/Choreographer( 3903): Skipped 89 frames!  The application may be doing too much work on its main thread.
,D/PanService( 3949): Received start request. Starting profile...
,I/ActivityManager(  915): Killing 3366:com.google.android.music:main/u0a154 (adj 15): empty #17
D/BluetoothTethering(  915): supplyMessenger
D/BluetoothTethering(  915): supplyMessenger mAsyncChannel is null
D/PanService( 3949): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothTethering(  915): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  915): got CMD_CHANNEL_HALF_CONNECTED
D/BtGatt.DebugUtils( 3949): handleDebugAction() action=null
D/BtGatt.GattService( 3949): Received start request. Starting profile...
D/BtGatt.GattService( 3949): start()
V/BluetoothPbapService( 3949): Pbap Service onCreate
,V/BluetoothPbapService( 3949): Starting PBAP service
,D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 11
,D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 11
,E/BluetoothMasService( 3949): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 3949): Add permission for SmsProvider.
,V/BluetoothMasService( 3949): Starting MAS instances
,D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 11
,I/MailMessageReceiver( 3949): reg:com.android.bluetooth.btservice.AdapterApp@41b13330 with com.htc.util.mail.MailMessageReceiver@41b53678
I/MailManager( 3949): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b53678
,V/EmailUtils( 3949): Manager Instance is not NULL
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  915): Client com.google.android.music (pid 3366): Died!
I/ActivityManager(  915): Recipient 3366
,I/chromium( 3903): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  915): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3993 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  915): interfaceAdded wlan0
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
,D/Tethering(  915): wlan0 is not a tetherable iface, ignoring
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
,D/Tethering(  915): interfaceStatusChanged wlan0, false
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
,D/Tethering(  915): interfaceAdded p2p0
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
,D/Tethering(  915): p2p0 is not a tetherable iface, ignoring
D/Tethering(  915): interfaceLinkStateChanged p2p0, false
,D/Tethering(  915): interfaceStatusChanged p2p0, false
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/libc    (  915): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/PMS     (  915): releaseWL(41bf5aa0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,I/wpa_supplicant( 4008): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4008): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4008): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4008): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4008): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4008): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4008): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4008): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4008): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4008): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4008): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4008): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4008): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4008): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4008): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4008): update_config=1
D/wpa_supplicant( 4008): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4008): device_name='Android_1950'
D/wpa_supplicant( 4008): manufacturer='HTC'
D/wpa_supplicant( 4008): model_name='HTC_PHONE'
D/wpa_supplicant( 4008): model_number='1234'
D/wpa_supplicant( 4008): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4008): p2p_oper_reg_class=126
D/wpa_supplicant( 4008): p2p_oper_channel=36
D/wpa_supplicant( 4008): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4008): persistent_reconnect=1
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4008): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4008): nl80211: RFKILL status not available
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4008): nl80211: Using driver-based roaming
D/wpa_supplicant( 4008): nl80211: TDLS supported
D/wpa_supplicant( 4008): nl80211: TDLS external setup
D/wpa_supplicant( 4008): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4008): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4008): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4008): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4008): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4008): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4008): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4008): nl80211: Subscribe to mgmt frames with non-AP handle 0xb83f1758
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Re,gister frame type=0xd0 nl_handle=0xb83f1758
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4008): htc_wext_command_init +
E/wpa_supplicant( 4008): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4008): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4008): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4008): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4008): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4008): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4008): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4008): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4008): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  915): interfaceLinkStateChanged p2p0, false
D/Tethering(  915): interfaceStatusChanged p2p0, false
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/Tethering(  915): interfaceLinkStateChanged p2p0, false
D/Tethering(  915): interfaceStatusChanged p2p0, false
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/EmailUtils( 3949): ============NULL aList========
,V/EmailUtils( 3949): <-getEmailAccountIdList
,V/BluetoothMasService( 3949): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 11
V/BluetoothMasService( 3949): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3949): Manager Instance is not NULL
D/EmailUtils( 3949): ============NULL aList========
,V/EmailUtils( 3949): <-getEmailAccountIdList
,V/BluetoothSapService( 3949): Sap Service onCreate
V/BluetoothSapService( 3949): initBinder
V/BluetoothSapService( 3949): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b58a68
,V/BluetoothSapReceiver( 3949): BluetoothSapReceiver init
,D/BluetoothSapService( 3949): setSapService()
V/BluetoothSapService( 3949): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3949): state: 12
,D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 11
D/BluetoothAdapterService( 3949): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3949): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3949): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3949): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3949): Profile still not running:com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 3949): Profile still not running:com.android.bluetooth.gatt.GattService
,D/PanService( 3949): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothAdapterState( 3949): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false,
,D/BluetoothTethering(  915): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  915): killProcessQuiet, pid=3349
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  915): Killing 3349:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/BluetoothMasReceiver( 3949): Bluetooth STATE CHANGED to 11
,I/qcom-bluetooth( 4013): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  915): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4015 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4031): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4032): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/WifiMonitor(  915): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,I/qcom-bluetooth( 4034): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/IntentController( 1110): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  915): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4015): Received state change = 11
D/WIFI_ICON( 1110): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/qcom-bluetooth( 4035): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4038): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/ActivityManager(  915): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4036 uid=10050 gids={50050}
I/qcom-bluetooth( 4046): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/WifiService(  915): New client listening to asynchronous messages
,I/ActivityManager(  915): Recipient 3349
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  915): killProcessQuiet, pid=3537
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1335): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  915): Killing 3537:com.google.android.talk/u0a111 (adj 15): empty #17
,I/QuickSettingWifi( 1110): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/HtcWiFiWidget_WiFiWidgetProvider( 4036): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4036): updateWidget(context) for widget: 
,D/Process (  915): killProcessQuiet, pid=3715
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  915): Killing 3715:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 3715
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 4008): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4008):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4008):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 4008):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4008): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4008): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4008): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4008): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4008): nl80211: Flush PMKIDs
E/wpa_supplicant( 4008): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4008): State: DISCONNECTED -> INACTIVE
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 3537
,D/wpa_supplicant( 4008): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4008): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4008): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4008): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4008): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4008): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4008): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4008): Using existing control interface directory.
D/wpa_supplicant( 4008): ctrl_iface bind(PF_UNIX) failed: Address already in use
,D/wpa_supplicant( 4008): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4008): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
,D/wpa_supplicant( 4008): P2P: Own listen channel: 6
,D/wpa_supplicant( 4008): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4008): P2P: Add operating class 81
,I/wpa_supplicant( 4008): State: INACTIVE -> DISCONNECTED
,D/wpa_supplicant( 4008): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4008): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4008): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4008): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4008): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4008): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4008): disable_scan_offload=1
D/wpa_supplicant( 4008): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4008): update_config=1
D/wpa_supplicant( 4008): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4008): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4008): manufacturer='HTC'
D/wpa_supplicant( 4008): model_name='HTC Desire 820'
D/wpa_supplicant( 4008): model_number='HTC Desire 820'
D/wpa_supplicant( 4008): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4008): persistent_reconnect=1
D/wpa_supplicant( 4008): p2p_disabled=1
D/wpa_supplicant( 4008): hs20=1
D/wpa_supplicant( 4008): interworking=1
D/wpa_supplicant( 4008): Line: 18 - start of a new network block
D/wpa_supplicant( 4008): key_mgmt: 0x2
D/wpa_supplicant( 4008): priority=1 (0x1)
,D/wpa_supplicant( 4008): signinfail=0 (0x0)
,I/qcom-bluetooth( 4053): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4054): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 4008): Priority group 1
D/wpa_supplicant( 4008):    id=0 ssid='NG700'
I/wpa_supplicant( 4008): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4008): nl80211: RFKILL status not available
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4008): nl80211: Using driver-based roaming
D/wpa_supplicant( 4008): nl80211: TDLS supported
D/wpa_supplicant( 4008): nl80211: TDLS external setup
D/wpa_supplicant( 4008): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4008): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4008): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4008): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4008): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4008): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4008): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4008): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8401718
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4008): htc_wext_command_init +
I/wpa_supplicant( 4008): htc_wext_command_init -
I/wpa_supplicant( 4008): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4008): Don't set 00 to countryID.conf
D/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4008): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4008): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4008): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4008): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4008): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4008): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4008): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4008): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
D/Tethering(  915): interfaceStatusChanged wlan0, false
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
,I/bt-btu  ( 3949): btu_task pending for preload complete event
,I/wpa_supplicant( 4008): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4008):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4008):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4008):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4008): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4008): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4008): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4008): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4008): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4008): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4008): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4008): TDLS: Driver uses external link setup
D/wpa_supplicant( 4008): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4008): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4008): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4008): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4008): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4008): Using existing control interface directory.
,I/wpa_supplicant( 4008): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4008): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4008): Auto country group 1: ch36
I/wpa_supplicant( 4008): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4008): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4008): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4008): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4008): random: Got 18/20 bytes from /dev/random
I/wpa_supplicant( 4008): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_915-2
,D/wpa_supplicant( 4008): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4008): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4008): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4008): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4008): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4008): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4008): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4008): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4008): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4008): nl80211: Event message available
D/wpa_supplicant( 4008): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4008): nl80211: Regulatory domain change
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4008): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4008): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4008): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4008): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4008): P2P: Add operating class 81
D/wpa_supplicant( 4008): P2P: Add operating class 115
D/wpa_supplicant( 4008): P2P: Add operating class 116
D/wpa_supplicant( 4008): P2P: Add operating class 117
D/wpa_supplicant( 4008): P2P: Update channel list
D/wpa_supplicant( 4008): p2p0: Updating hw mode
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4008): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4008): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4008): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4008): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4008): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 4008): random: Got 2/2 bytes from /dev/random
V/RegulatoryObserver(  915): uevent:,
V/RegulatoryObserver(  915): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
D/WifiNative-wlan0(  915): doBoolean: SET_WIFI_ON 1
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
,D/wpa_supplicant( 4008): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4008): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4008): set wifi ON
V/RegulatoryObserver(  915): Regulatory Country Code:DE
V/RegulatoryObserver(  915): Start wifi-crda service to run crda.
V/RegulatoryObserver(  915): Country Code is DE
V/RegulatoryObserver(  915): Send broadcast country code message.
I/RegulatoryObserver(  915): Broadcast intent for crda country code: DE
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
I/wpa_supplicant( 4008): wpa_supplicant_scan enter
I/wpa_supplicant( 4008): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4008): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4008): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4008): Scan req (ret=0) - timeout 10 secs
D/wpa_supplicant( 4008): nl80211: Event message available
D/wpa_supplicant( 4008): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  915):    returned true
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
D/WifiNative-wlan0(  915): doString: DRIVER MACADDR
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  915): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiConfigStore(  915): Loading config and enabling all networks
D/WifiNative-wlan0(  915): doString: LIST_NETWORKS
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): list_network_info: ret=0x1, pos=0xb8404117 buf=0xb84040e8
I/wpa_supplicant( 4008): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4008): 0	NG700	any	
D/WifiNative-wlan0(  915):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  915): 0	NG700	any	
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 ssid
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 bssid
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 priority
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WIFI_ICON( 1110): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1110): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 psk
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4008): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 proto
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  915): Failed to look-up a string: W
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  915): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 group
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  915): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  915): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  915): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  915): ***WAPI : readNetworkVariables WAPI_CERT index null
D/HtcWiFiWidget_WiFiWidgetProvider( 4036): onWiFiStateChanged() for widget: 
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  915): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  915): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 limited
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 eap
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 phase2
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 identity
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/HtcWiFiWidget_WiFiWidgetProvider( 4036): updateWidget(context) for widget: 
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 password
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 engine
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 key_id
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  915): doString: GET_NETWORK 0 private_key
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4008): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  915): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  915): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4008): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4008): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SET manufacturer HTC
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4008): manufacturer='HTC'
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4008): model_name='HTC Desire 820'
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4008): model_number='HTC Desire 820'
D/WifiNative-wlan0(  915):    returned true
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4008): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SET auto_interworking 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4008): auto_interworking=0
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: RECONNECT
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doString: STATUS
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  915): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): SET_SCREEN_ON:On
I/wpa_supplicant( 4008): htc_wext_set_keepalive +
I/wpa_supplicant( 4008): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4008): getPrivFuncNum +	
I/wpa_supplicant( 4008): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4008): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4008): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4008): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4008): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SET ps 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4008): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  915):    returned true
W/Settings(  915): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  915): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): SETBAND: 0
D/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4008): P2P: Add operating class 81
D/wpa_supplicant( 4008): P2P: Add operating class 115
D/wpa_supplicant( 4008): P2P: Add operating class 116
D/wpa_supplicant( 4008): P2P: Add operating class 117
D/wpa_supplicant( 4008): P2P: Update channel list
I/wpa_supplicant( 4008): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4008): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4008): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4008): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4008): p2p_oper_reg_class=126
D/wpa_supplicant( 4008): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4008): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 4008): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4008): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4008): p2p_oper_channel=36
E/wpa_supplicant( 4008): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4008): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4008): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4008): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4008): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: BSS_FLUSH 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  915): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  915): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SCAN
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiMonitor(  915): startMonitoring(p2p0) with mConnected = true
D/WifiNative-wlan0(  915):    returned false
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  915): doBoolean: SET pno 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4008): wpa_supplicant_scan enter
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-p2p0(  915): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4008): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4008): persistent_reconnect=1
I/wpa_supplicant( 4008): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doBoolean: SET device_name Android_1950
W/WifiHW  (  915): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 4008): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 4008): device_name='Android_1950'
I/wpa_supplicant( 4008): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  915): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 4008): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 4008): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4008): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 4008): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  915): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4008): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4008): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiP2pService(  915): P2pEnablingState
D/WifiP2pService(  915): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2p socket connection successful
D/WifiStateMachine(  915): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  915): P2pEnabledState
D/WifiP2pService(  915): sending p2p connection changed broadcast
D/WifiDisplayController(  915): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  915): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
W/WifiHW  (  915): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4008): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4008): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4008): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  915): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4008): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4008): Single channel concurrency preference: sta
I/wpa_supplicant( 4008): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doString: STATUS
W/WifiHW  (  915): QCOM Debug wifi_send_command "STATUS"
I/QuickSettingWifi( 1110): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  915): doBoolean: P2P_FLUSH
W/WifiHW  (  915): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4008): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4008): P2P: Stopping find
D/wpa_supplicant( 4008): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4008): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4008): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  915): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4008): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4008): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doString: LIST_NETWORKS
W/WifiHW  (  915): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4008): list_network_info: ret=0x22, pos=0xb840410a buf=0xb84040e8
I/wpa_supplicant( 4008): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4008): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  915):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  915): doBoolean: AP_SCAN 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  915):    returned false
D/WifiNative-p2p0(  915): doBoolean: SET wifi_display 1
D/WifiDisplayController(  915): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  915): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiP2pService(  915): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  915): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  915):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  915):  primary type: 10-0050F204-5
D/WifiDisplayController(  915):  secondary type: null
D/WifiDisplayController(  915):  wps: 0
D/WifiDisplayController(  915):  grpcapab: 0
D/WifiDisplayController(  915):  devcapab: 0
D/WifiDisplayController(  915):  status: 3
D/WifiDisplayController(  915):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  915):  WFD CtrlPort: 0
D/WifiDisplayController(  915):  WFD MaxThroughput: 0
D/WifiP2pService(  915): sending p2p persistent groups changed broadcast
D/WifiP2pService(  915): InactiveState
D/WifiP2pService(  915): InactiveState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  915):  WFD CtrlPort: 7236
D/WifiP2pService(  915):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  915):  WFD CtrlPort: 7236
D/WifiP2pService(  915):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 4008): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4008): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
W/WifiHW  (  915): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4008): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4008): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4008): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4008): WFD: Update WFD IE
I/wpa_supplicant( 4008): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4008): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  915):    returned true
D/WifiNative-p2p0(  915): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  915): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4008): WFD: Set subelement 0
D/wpa_supplicant( 4008): WFD: Update WFD IE
I/wpa_supplicant( 4008): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4008): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  915):    returned true
D/Tethering(  915): interfaceLinkStateChanged p2p0, false
D/Tethering(  915): interfaceStatusChanged p2p0, false
D/Tethering(  915): [isWifi] getHotspotEnabled: false
V/AudioService(  915): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  915):     Client/Owner: Client
V/AudioService(  915):     GroupId: 
V/AudioService(  915):     Passphrase: 
V/AudioService(  915):     SessionId: 0
V/AudioService(  915):     IP Address: }
D/HtcEffectManagerBase(  915): onEventChanged id=5 status=false
D/HtcEffectManager(  915): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  915): convertEffect before=902
D/HtcEffectManager(  915): convertEffect after=902
D/WifiDisplayController(  915): Successfully set WFD info.
I/WifiDisplayController(  915): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  915): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  915):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  915):  primary type: 10-0050F204-5
D/WifiDisplayController(  915):  secondary type: null
D/WifiDisplayController(  915):  wps: 0
D/WifiDisplayController(  915):  grpcapab: 0
D/WifiDisplayController(  915):  devcapab: 0
D/WifiDisplayController(  915):  status: 3
D/WifiDisplayController(  915):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  915):  WFD CtrlPort: 7236
D/WifiDisplayController(  915):  WFD MaxThroughput: 50
D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
,D/wpa_supplicant( 4008): EAPOL: disable timer tick
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4008): nl80211: Event message available
D/wpa_supplicant( 4008): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4008): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4008): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 4008): nl80211: Survey data missing
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4008): Sorted scan results
I/wpa_supplicant( 4008): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 4008): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 4008): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 4008): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 4008): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 4008): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-92
D/wpa_supplicant( 4008): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 4008): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4008): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4008): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4008): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4008): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4008): Add randomness: count=7 entropy=5
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4008): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4008): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4008): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4008): wpa_supplicant_pick_network+
I/wpa_supplicant( 4008): Selecting BSS from priority group 1
I/wpa_supplicant( 4008): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4008): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4008): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4008): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4008): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4008):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4008):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 4008): Start print parameters
I/wpa_supplicant( 4008): wpa_s->wpa_state is 3
I/wpa_supplicant( 4008): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4008): isConcurrentMode() is 0
I/wpa_supplicant( 4008): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4008): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4008): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4008): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4008): wpa_s->reassociate is 0
I/wpa_supplicant( 4008): wpa_s->is_screen_on 1
I/wpa_supplicant( 4008): wpa_s->ifname wlan0
I/wpa_supplicant( 4008): End print parameters
I/wpa_supplicant( 4008): selected network = 2
D/wpa_supplicant( 4008): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid,: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84024e8  current_ssid=0x0
D/wpa_supplicant( 4008): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4008): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4008): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4008): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4008): check if in concurrent case
I/wpa_supplicant( 4008): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  915): doString: LIST_DONGLES
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 4008): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4008): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4008): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4008): RSN: PMKSA cache search - network_ctx=0xb84024e8 try_opportunistic=0
D/wpa_supplicant( 4008): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4008): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4008): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4008): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4008): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4008): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4008): nl80211: Unsubscribe mgmt frames handle 0xb8401718 (mode change)
D/wpa_supplicant( 4008): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8401718
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
,D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Register frame type=0xd0 nl_handle=0xb8401718
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4008): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4008):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4008):   * freq=2412
,D/wpa_supplicant( 4008):   * Auth Type 0
D/wpa_supplicant( 4008):   * WPA Versions 0x2
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4008): nl80211: Connect request send successfully
D/wpa_supplicant( 4008): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4008): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4008): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 4008): RSN: Ignored PMKID candidate without preauth flag
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  915): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4008): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4008): reply (779) for get BSS: id=0
I/wpa_supplicant( 4008): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4008): freq=5220
I/wpa_supplicant( 4008): level=-50
I/wpa_supplicant( 4008): tsf=0000000104272021
I/wpa_supplicant( 4008): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4008): ssid=NG7005g
I/wpa_supplicant( 4008): ====
I/wpa_supplicant( 4008): id=1
I/wpa_supplicant( 4008): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4008): freq=2412
I/wpa_supplicant( 4008): level=-60
I/wpa_supplicant( 4008): tsf=0000000104272043
I/wpa_supplicant( 4008): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4008): ssid=01ABC
I/wpa_supplicant( 4008): ====
I/wpa_supplicant( 4008): id=2
I/wpa_supplicant( 4008): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4008): freq=2412
I/wpa_supplicant( 4008): level=-60
I/wpa_supplicant( 4008): tsf=0000000104272053
I/wpa_supplicant( 4008): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4008): ssid=NG700
I/wpa_supplicant( 4008): ====
I/wpa_supplicant( 4008): id=3
I/wpa_supplicant( 4008): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4008): freq=2427
I/wpa_supplicant( 4008): level=-80
I/wpa_supplicant( 4008): tsf=0000000104272065
I/wpa_supplicant( 4008): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4008): ssid=Gonzos
I/wpa_supplicant( 4008): ====
I/wpa_supplicant( 4008): id=4
I/wpa_supplicant( 4008): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 4008): freq=2462
I/wpa_supplicant( 4008): level=-90
I/wpa_supplicant( 4008): tsf=0000000104272075
I/wpa_supplicant( 4008): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4008): ssid=UPC5999698
I/wpa_supplicant( 4008): ====
I/wpa_supplicant( 4008): id=5
I/wpa_supplicant( 4008): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 4008): freq=2462
I/wpa_supplicant( 4008): level=-92
I/wpa_supplicant( 4008): tsf=0000000104272088
I/wpa_supplicant( 4008): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 4008): ssid=UPC Wi-Free
I/wpa_supplicant( 4008): ####
,D/WirelessDisplayService(  915): getDiscoveryDongleList
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/WifiStateMachine(  915): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 104272021, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 104272043, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 104272053, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  915): == begin of scan result ==
D/WifiStateMachine(  915): == (6) end of scan result ==
,D/WifiManager( 1198): getScanResults enter 
,D/WirelessDisplayService(  915): getDiscoveryDongleList
D/WifiStateMachine(  915): == begin of scan result ==
,D/WifiStateMachine(  915): == (6) end of scan result ==
D/WifiStateMachine(  915): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 104272065, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 104272075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 104272088, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): add 6 to mScanResults
D/WifiNotificationController(  915): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,I/bt-btu  ( 3949): btu_task received preload complete event
,D/bt-btm  ( 3949): btm_acl_device_down
D/bt-btm  ( 3949): btm_acl_reset_paging
,D/bt-btm  ( 3949): btm_acl_set_discing
,I/bt-btm  ( 3949): btm_reset_complete
,I/bt-btm  ( 3949): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3949): Start reading local supported commands
,D/bt-btm  ( 3949): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3949): BTM reads next extended features page (1)
,D/bt-btm  ( 3949): BTM reads next extended features page (2)
,D/bt-btm  ( 3949): BTM reached last extended features page (2)
,D/bt-btm  ( 3949): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3949): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3949): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3949): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3949): btm_read_ble_wl_size 
D/bt-btm  ( 3949): btm_read_white_list_size_complete 
,D/bt-btm  ( 3949): btm_get_ble_buffer_size 
D/bt-btm  ( 3949): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3949): btm_read_ble_local_supported_features 
D/bt-btm  ( 3949): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3949): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3949): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3949): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3949): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3949): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3949): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3949):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3949): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3949): BTM_SetInquiryMode
I/bt-btm  ( 3949): BTM_SetPageScanType
I/bt-btm  ( 3949): BTM_SetInquiryScanType
D/bt-btm  ( 3949): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3949): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3949): BTM_BleLoadLocalKeys
D/bt-btm  ( 3949): BTM_BleLoadLocalKeys
I/bt-btm  ( 3949): BTM_Sec: application registered
E/bt-btm  ( 3949): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fa4941 
I/bt-btm  ( 3949): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3949): SMP_Register state=0
E/bt-btm  ( 3949): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fa4941 
I/bt-btm  ( 3949): BTM_Sec: application registered
D/bt-btm  ( 3949): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3949): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3949): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3949): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3949): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3949): BTM_RegBusyLevelNotif
I/bt-att  ( 3949): GATT_Register
,D/bt-att  ( 3949): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3949): allocated gatt_if=3
I/bt-att  ( 3949): GATT_StartIf gatt_if=3
D/bt-att  ( 3949): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3949): gatt_find_the_connected_bda found=0 found_idx=7
,E/bt-btif ( 3949): Calling BTA_HhEnable
,E/bt-btif ( 3949): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3949): HAL bt_hal_cbacks->adapter_properties_cb
D/wpa_supplicant( 4008): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4008): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4008): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4008): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4008): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4008): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4008): nl80211: if_removed already cleared - ignore event
I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:2 len:6
D/wpa_supplicant( 4008): nl80211: Event message available
D/wpa_supplicant( 4008): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4008): nl80211: Connect event
D/wpa_supplicant( 4008): nl80211: Associated on 2412 MHz
,D/wpa_supplicant( 4008): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4008): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4008): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4008): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 4008): Add randomness: count=8 entropy=6
I/wpa_supplicant( 4008): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4008): TDLS: Remove peers on association
D/wpa_supplicant( 4008): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4008): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4008): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4008): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4008): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4008): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4008): htc_wext_set_keepalive +
I/wpa_supplicant( 4008): htc_wext_set_keepalive: enable=1, type=1, interval=30
,D/wpa_supplicant( 4008): getPrivFuncNum +	
I/wpa_supplicant( 4008): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4008): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4008): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4008): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4008): Get randomness: len=32 entropy=7
,D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  915): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
,D/Tethering(  915): interfaceStatusChanged wlan0, false
D/WifiMonitor(  915): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/HTCRequest(  915): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/BluetoothAdapterProperties( 3949): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:1 len:14
D/HTCRequest(  915): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  915): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  915): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  915): handleAssociatedWithEvent. bLFR =false
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3949): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/Tethering(  915): interfaceLinkStateChanged wlan0, true
D/Tethering(  915): interfaceStatusChanged wlan0, true
D/WifiMonitor(  915): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3949): BTM_AllocateSCN
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:4
D/WifiStateMachine(  915): Enter handleAssociatedWithEvent
D/bt-btm  ( 3949): BTM_AllocateSCN
,I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
D/WifiStateMachine(  915): Setting MAC Address to c0:ff:d4:d3:aa:48
I/bt-btm  ( 3949): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
D/WifiStateMachine(  915): Associated
I/bt-btm  ( 3949):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
,I/bt-btm  ( 3949):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3949):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3949):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3949):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
,I/bt-btm  ( 3949):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 3949): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3949):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3949):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3949): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3949): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
D/bt-avp  ( 3949): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3949): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btm  ( 3949): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 3949): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3949):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
,I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: b0:c5:59:3f:75:69
D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
,D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
,D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
,D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
,D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3949): BTM_GetHCIConnHandle
I/bt-btm  ( 3949): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 3949): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3949): GATT_Register
D/bt-att  ( 3949): UUID=[0x0000454c205245564f20484820415442]
,I/bt-att  ( 3949): allocated gatt_if=4
I/bt-att  ( 3949): GATT_StartIf gatt_if=4
D/bt-att  ( 3949): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3949): gatt_find_the_connected_bda found=0 found_idx=7
I/wpa_supplicant( 4008): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84019f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4008):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 11
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4008): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4008): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa2b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4008):    broadcast key
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4008): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4008): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4008): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4008): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 4008): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 4008): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4008): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4008): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4008): set send_ind_to_ndc = 0
I/wpa_supplicant( 4008): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4008): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4008): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4008): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4008): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 4008): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4008): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4008): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4008): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4008): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4008): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4008): EAPOL authentication completed successfully
I/wpa_supplicant( 4008): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 79
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 4008): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
D/wpa_supplicant( 4008): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4008): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  915): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  915): interfaceLinkStateChanged wlan0, true
D/Tethering(  915): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  915): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  915): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  915): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  915): updateConnectedAP...
I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:7 len:4
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/BluetoothAdapterProperties( 3949): Scan Mode:20
I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3949): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:8 len:54
D/BluetoothAdapter( 3949): getBluetoothService(): entry
D/BluetoothAdapter( 3949): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002,
D/BluetoothAdapter( 3949): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b63958
D/BluetoothDevice( 3949): getService : Register callback
,D/WifiApDatabaseHandler(  915): updateConnectedAP...
,D/BluetoothAdapterProperties( 3949): Adding bonded device:B0:C5:59:3F:75:69
,D/WifiStateMachine(  915): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/BluetoothAdapterProperties( 3949): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 3949): Adding bonded device:80:01:84:8A:B3:68
D/WifiApDatabaseHandler(  915): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  915): This record is existed, only update it...
,D/BluetoothAdapterProperties( 3949): Adding bonded device:14:B4:84:21:3B:49
,D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/BluetoothAdapterProperties( 3949): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 3949): Adding bonded device:7C:F9:0E:34:8A:A0
,D/WifiApDatabaseHandler(  915): updateConnectedAP...
,D/BluetoothAdapterProperties( 3949): Adding bonded device:90:E7:C4:F6:69:77
,D/BluetoothAdapterProperties( 3949): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 3949): Adding bonded device:38:94:96:B5:06:DC
I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BluetoothRemoteDevices( 3949): Remote class is:5898764
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  915): updateConnectedAP...
,E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BluetoothRemoteDevices( 3949): Remote class is:5898764
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/WifiStateMachine(  915): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  915): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/BluetoothRemoteDevices( 3949): Remote class is:5898764
,D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  915): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  915): This record is existed, only update it...
,D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  915): updateConnectedAP...
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  915): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  915): Provision feature enable=false
,D/ConnectivityService(  915): mActiveDefaultNetwork: -1
,I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WISPrService( 3313): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  915): updateConnectedAP...
,E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3313): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/BluetoothRemoteDevices( 3949): Remote class is:5898764
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/WifiService(  915): New client listening to asynchronous messages
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
,D/BluetoothRemoteDevices( 3949): Remote class is:5898764
,D/DhcpStateMachine(  915): [StoppedState] Start DHCP
D/WifiStateMachine(  915): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/BluetoothRemoteDevices( 3949): Remote class is:5898764
,D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  915):    returned true
D/WifiStateMachine(  915): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  915): doBoolean: MOBILE_TYPE Unknown
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED -1 -> 3
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4008): WiFioffload: update mobile network = Unknown
D/WifiNative-wlan0(  915):    returned true
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  915):    returned true
,D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): Power_Mode_Type mode = 1
I/wpa_supplicant( 4008): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  915):    returned true
E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/WifiNative-wlan0(  915): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  915):    returned null
E/WifiStateMachine(  915): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  915): doString: DRIVER WLS_BATCHING STOP
D/BluetoothRemoteDevices( 3949): Remote class is:5898764
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  915): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  915): acquireWL(436b4d70): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 915 1000 null
,D/WifiStateMachine(  915): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  915):    returned null
E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3949): Remote class is:5898764
,I/bt-btif ( 3949): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3949): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,D/BluetoothRemoteDevices( 3949): Remote class is:5898764
D/WifiP2pService(  915): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4363bc30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  915): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4363bc30 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3949): BTA_JvEnable
I/bt-btm  ( 3949): BTM_ReadConnectability
I/bt-btm  ( 3949): BTM_ReadDiscoverability
I/bt-btm  ( 3949): BTM_SetDiscoverability
I/bt-btm  ( 3949): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3949): br_edr_supported=0x2
I/bt-btm  ( 3949): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3949): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3949): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3949): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3949): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3949): BTM_SetConnectability
I/bt-btm  ( 3949): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3949): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3949): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3949): BTM_SetDiscoverability
I/bt-btm  ( 3949): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3949): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3949): br_edr_supported=0x0
I/bt-btm  ( 3949): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3949): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3949): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3949): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3949): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3949): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3949): BTM_SetConnectability
I/bt-btm  ( 3949): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3949): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3949): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3949): bta_pan_co_init
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3949): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3949):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3949):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3949): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3949):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3949): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3949):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/QuickSettingWifi( 1110): receive.wifiConnect:false wifiAPname:null elapse:0
E/bt_mct  ( 3949): hci lib postload completed
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btif ( 3949): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3949): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3949): ScanMode =  20
D/BluetoothAdapterProperties( 3949): State =  11
I/bt-btm  ( 3949): BTM_SetDiscoverability
I/bt-btm  ( 3949): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3949): btm_ble_set_discoverability, (BREDR not sup)flag=0x4
D/bt-btm  ( 3949): br_edr_supported=0x0
I/bt-btm  ( 3949): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3949): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3949): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3949): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3949): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3949): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3949): BTM_SetConnectability
I/bt-btm  ( 3949): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3949): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3949): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3949): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3949): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3949): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3949): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3949): Setting state to 12
I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:7 len:4
I/BluetoothAdapterState( 3949): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3949): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  915): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  915): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  915): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  915): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset(  915): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3949): Scan Mode:21
I/bt-btif ( 3949): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3949): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3949): Discoverable Timeout:120
I/BluetoothAdapterState( 3949): Entering On State
D/BluetoothA2dp(  915): onBluetoothStateChange: up=true
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset(  915): Proxy object connected
,D/BluetoothPan(  915): onBluetoothStateChange(on) call bindService
D/BluetoothAdapterService(1102172760)( 3949): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3949): getBondedDevices: length=9
,D/BluetoothAdapter(  915): 1112032280: getState(). Returning 12
,D/BluetoothHeadset( 1213): onBluetoothStateChange: up=true
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,D/BluetoothHeadset( 1213): Proxy object connected
,D/BluetoothHeadset( 1213): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  915): Proxy object connected
,D/BluetoothAdapter(  915): 1112032280: getState(). Returning 12
,D/BluetoothHeadset( 1213): Proxy object connected
,D/BluetoothPhoneService( 1213): BluetoothHeadset onServiceConnected
D/BluetoothHeadset( 1110): onBluetoothStateChange: up=true
,D/BluetoothPan(  915): BluetoothPAN Proxy object connected
,D/BluetoothAdapter( 1213): 1103353248: getState(). Returning 12
D/BluetoothAdapterService(1102172760)( 3949): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3949): getBondedDevices: length=9
,D/BluetoothHeadset( 1110): Proxy object connected
I/QuickSettingMiniLite( 1110): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e19c08
,D/BluetoothManagerService(  915): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  915): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  915): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  915): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/IntentController( 1110): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,V/BluetoothPbapReceiver( 3949): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3949): ***********state = 12
,D/BluetoothMasReceiver( 3949): Bluetooth STATE CHANGED to 12
V/BluetoothSapReceiver( 3949): SapReceiver onReceive 
,V/BluetoothSapReceiver( 3949): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3949):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 3949): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  915): acquireWL(43b892f0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1198 10029 null
D/PMS     (  915): releaseWL(43b892f0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/PMS     (  915): acquireWL(440fad18): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3313 1000 null
D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 12
D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 12
V/BluetoothMasService( 3949): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3949): Manager Instance is not NULL
W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/HtcBtWidget_BTWidgetProvider( 3974): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3974): updateWidget(context) for widget: 
D/EmailUtils( 3949): ============NULL aList========
,V/EmailUtils( 3949): <-getEmailAccountIdList
V/BluetoothSapService( 3949): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3949): state: 12
,D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 12
,W/ContextImpl( 3949): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
,V/BluetoothSapService( 3949): Starting SAP server process
V/BluetoothPbapService( 3949): Handler(): got msg=1
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43927098:true
,W/System.err(  915): java.lang.Throwable: stack dump
,V/BluetoothPbapService( 3949): Pbap Service startRfcommSocketListener
D/PMS     (  915): releaseWL(440fad18): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  915): acquireWL(436fd568): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3313 1000 null
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
V/BluetoothPbapService( 3949): Pbap Service initSocket
V/BluetoothMasService( 3949): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 3949): BluetoothMns: isEmailEnabled: true
D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothMasService( 3949): Map_prev 1
D/BluetoothAdapter( 3949): getBluetoothService(): entry
D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3949): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3949): getBluetoothService(): entry
W/BluetoothAdapter( 3949): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3949): SOCK FLAG = 1 ***********************
I/bt-btif ( 3949): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
E/BluetoothServiceJni( 3949): SOCK FLAG = 3 ***********************
I/bt-btif ( 3949): BTA_JvRfcommStartServer
I/bt-btm  ( 3949): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btif ( 3949): BTA_JvCreateRecordByUser
I/bt-btm  ( 3949):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btif ( 3949): BTA_JvRfcommStartServer
I/bt-btm  ( 3949): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3949):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3949): Succeed to create listening socket 
V/BluetoothPbapService( 3949): Accepting socket connection...
D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3949): getBluetoothService(): entry
W/BluetoothAdapter( 3949): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3949): SOCK FLAG = 3 ***********************
I/bt-btif ( 3949): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btif ( 3949): BTA_JvRfcommStartServer
I/bt-btm  ( 3949): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3949):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,I/LocationAgent( 3313): new LocationAgent instance!!
,D/HtcTagManager( 3313): HtcTagManager construction complete
,D/BluetoothSapService( 3949): Sap_prev 1
,V/BluetoothSapService( 3949): SAP Service startRfcommListenerThread
V/BluetoothSapService( 3949): Sap Service initRfcommSocket
,D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
D/BluetoothAdapter( 3949): getBluetoothService(): entry
,W/BluetoothAdapter( 3949): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3949): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3949): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
,I/bt-btif ( 3949): BTA_JvRfcommStartServer
I/bt-btm  ( 3949): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3949):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3949): Succeed to create listening socket 
,V/BluetoothSapService( 3949): Accepting socket connection...
,D/BluetoothAdapter( 1110): 1104893032: getState(). Returning 12
,D/BluetoothInputDevice( 3313): BluetoothInputDevice()
D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  915): Registered receivers: 7
D/BluetoothAdapter( 1110): 1104893032: getState(). Returning 12
D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
,D/BluetoothInputDevice( 3313): BluetoothInputDevice(): Binding service...
,I/QuickSettingBluetooth( 1110): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1110): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothPan( 3313): BluetoothPan()
D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  915): Registered receivers: 8
D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
,D/BluetoothPan( 3313): BluetoothPan(): Binding service...
W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,D/BluetoothMap( 3313): Create BluetoothMap proxy object
,D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  915): Registered receivers: 9
E/BluetoothMap( 3313): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothSap( 3313): BluetoothSap() call bindService
,D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  915): Registered receivers: 10
,D/BluetoothPbap( 3313): BluetoothPbap()
,D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  915): Registered receivers: 11
D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
,D/BluetoothPbap( 3313): BluetoothPbap(): Binding service...
W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothA2dp( 3313): BluetoothA2dp()
,D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  915): Registered receivers: 12
I/BluetoothFtpService( 3949): Ftp Service onCreate
,D/BluetoothAdapter( 3949): getBluetoothService(): entry
D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
,D/BluetoothA2dp( 3313): BluetoothA2dp(): Binding service...
,D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 12
,D/BluetoothMasReceiver( 3949): Bluetooth STATE CHANGED to 12
,W/BluetoothAdapter( 3949): getBluetoothService() called with no BluetoothManagerCallback
W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothHeadset( 3313): BluetoothHeadset()
V/TAG     ( 3949): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3949): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b5a1a8
D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothAdapter( 1110): 1104893032: getState(). Returning 12
E/BluetoothServiceJni( 3949): SOCK FLAG = 0 ***********************
I/bt-btif ( 3949): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btif ( 3949): BTA_JvRfcommStartServer
I/bt-btm  ( 3949): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3949):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
I/BtOppRfcommListener( 3949): Accept thread started.
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4015): Received state change = 12
D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
D/BluetoothHeadset( 3313): BluetoothHeadset(): Binding service...
V/BluetoothPbapService( 3949): Pbap Service onBind
D/BluetoothManagerService(  915): Registered receivers: 13
I/QuickSettingMiniLite( 1110): updateLiteState:no connect device!
,D/BluetoothFtpService( 3949): Ftp_prev 1
,D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothAdapter( 3949): getBluetoothService(): entry
W/BluetoothAdapter( 3949): getBluetoothService() called with no BluetoothManagerCallback
,D/HtcTagManager( 3313): startProxy
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4015): onCreate: going to find gatt base service first.
,W/ContextImpl( 3313): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/System.err(  915): java.lang.Throwable: stack dump
,W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43bbd1d0:true
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/LocalBluetoothProfileManager( 3313): LocalBluetoothProfileManager construction complete
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3836): new LocationAgent instance!!
D/DockEventReceiver( 3313): finishStartingService: stopping service
D/BluetoothPan( 3313): BluetoothPAN Proxy object connected
D/PanProfile( 3313): Bluetooth service connected
D/BluetoothInputDevice( 3313): Proxy object connected
D/HidProfile( 3313): Bluetooth service connected
E/BluetoothServiceJni( 3949): SOCK FLAG = 1 ***********************
I/bt-btif ( 3949): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3949): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3949): Write Extended Inquiry Response to controller
I/bt-btif ( 3949): BTA_JvRfcommStartServer
I/bt-btm  ( 3949): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3949):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/HtcTagManager( 3836): HtcTagManager construction complete
V/BluetoothFtpService:RfcommSocketAcceptThread( 3949): Run Accept thread
W/System.err(  915): java.lang.Throwable: stack dump
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothAdapter( 3949): 1102190936: getState(). Returning 12
V/BluetoothMasService( 3949): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3949): Manager Instance is not NULL
D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4240d758:true
D/[HTC_BLE][Constants]( 4015):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4015):  + enableOnBonded = false
D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
D/[HTC_BLE][Constants]( 4015):  + discoverServicesOnBonded = false
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
D/BluetoothA2dp( 3313): Proxy object connected
D/A2dpProfile( 3313): Bluetooth service connected
D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
D/BluetoothInputDevice( 3836): BluetoothInputDevice()
D/EmailUtils( 3949): ============NULL aList========
V/EmailUtils( 3949): <-getEmailAccountIdList
D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothMasService( 3949): Map_prev 1
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  915): Registered receivers: 14
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
D/BluetoothInputDevice( 3836): BluetoothInputDevice(): Binding service...
D/SapServerProfile( 3313): Bluetooth service connected
D/BluetoothPbap( 3313): Proxy object connected
D/PbapServerProfile( 3313): Bluetooth service connected
D/B,luetoothHeadset( 3313): Proxy object connected
D/HeadsetProfile( 3313): Bluetooth service connected
,D/BluetoothAdapter( 3313): 1103779800: getState(). Returning 12
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4015):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4015): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b250c8
D/[HTC_BLE][Constants]( 4015): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4015): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4015): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4015): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4015): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
D/[HTC_BLE][Constants]( 4015): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
D/BluetoothPan( 3836): BluetoothPan()
D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4015): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4015): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b250c8
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4015): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b250c8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4015): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b250c8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b301c0
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4015): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b250c8
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/BluetoothPan( 3836): BluetoothPan(): Binding service...
D/PMS     (  915): releaseWL(436fd568): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothMap( 3836): Create BluetoothMap proxy object
D/BluetoothManagerService(  915): registerStateChangeCallback+
E/BluetoothMap( 3836): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  915): registerStateChangeCallback+
,D/BluetoothSap( 3836): BluetoothSap() call bindService
,D/BluetoothPbap( 3836): BluetoothPbap()
,D/RingtoneManager( 4015): getExternalStorageState=mounted
,D/BluetoothManagerService(  915): registerStateChangeCallback+
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/BluetoothPbap( 3836): BluetoothPbap(): Binding service...
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/wpa_supplicant( 4008): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4008): EAPOL: disable timer tick
,D/BluetoothA2dp( 3836): BluetoothA2dp()
,D/BluetoothManagerService(  915): registerStateChangeCallback+
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/BluetoothA2dp( 3836): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3836): BluetoothHeadset()
,D/BluetoothManagerService(  915): registerStateChangeCallback+
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/BluetoothHeadset( 3836): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3836): startProxy
,W/ContextImpl( 3836): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3836): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
D/LocalBluetoothProfileManager( 3836): setBluetoothStateOn
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
D/HtcTagManager( 3836): startProxy
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
D/BluetoothAdapterService(1102172760)( 3949): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3949): getBondedDevices: length=9
D/BluetoothAdapter( 3836): getBluetoothService(): entry
D/BluetoothAdapter( 3836): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3836): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b5d6c0
D/BluetoothDevice( 3836): getService : Register callback
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[8]: Olive
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[13]: Wintergreen
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4015):  + mAlertUri: content://settings/system/alarm_alert
E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4015): BleProfilesStateMachine is initialized...
D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4015): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4015): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4015): initScanModeInterface: true
D/HtcTagManager( 3836): addHtcTagProfiles
,W/System.err(  915): java.lang.Throwable: stack dump
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4015): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4015):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE][Constants]( 4015):  + defaultServices = 0,
D/[HTC_BLE][Constants]( 4015):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4015):  + discoverServicesOnBonded = false
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4015): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b301c0
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4015): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3313): onServiceConnected
D/HtcTagProfile( 3313): setup proxy
D/HtcPxpProfile( 3313): setup proxy
,D/HtcFmpProfile( 3313): setup proxy
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,D/BluetoothManagerService(  915): Registered receivers: 15
E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  915): Registered receivers: 16
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  915): Registered receivers: 17
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  915): Registered receivers: 18
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  915): Registered receivers: 19
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  915): Registered receivers: 20
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423d24f0:true
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,D/BluetoothInputDevice( 3836): Proxy object connected
D/HidProfile( 3836): Bluetooth service connected
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/AuthorizationBluetoothService( 1335): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1335): Proximity feature is not enabled.
D/BluetoothPan( 3836): BluetoothPAN Proxy object connected
,D/PanProfile( 3836): Bluetooth service connected
D/SapServerProfile( 3836): Bluetooth service connected
D/BluetoothPbap( 3836): Proxy object connected
D/PbapServerProfile( 3836): Bluetooth service connected
,D/BluetoothA2dp( 3836): Proxy object connected
,D/A2dpProfile( 3836): Bluetooth service connected
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/BluetoothHeadset( 3836): Proxy object connected
,D/HeadsetProfile( 3836): Bluetooth service connected
,D/BluetoothAdapter( 3836): 1102201264: getState(). Returning 12
,D/HtcTagManager( 3836): onServiceConnected
D/HtcTagProfile( 3836): setup proxy
D/HtcPxpProfile( 3836): setup proxy
,D/HtcFmpProfile( 3836): setup proxy
,I/PMS     (  915): Going to sleep due to screen timeout...
,I/ActivityManager(  915): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  915): setLight #2: color=#0
D/qdlights(  915): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  915): setLight #0: color=#0
,I/SensorManager(  915): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421835f0
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  915): disable: get sensor name = CM36282 Light sensor
W/SensorService(  915): pid=915, uid=1000
,W/SensorService(  915): Active sensors: size = 2
W/SensorService(  915): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2),
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421835f0, eanble = 0, strlen(mName) = 59
,W/SensorService(  915): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  915): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f42608,
W/SensorService(  915): Listener[1] = com.htc.smartdim.sensor_eye@42739760
,W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  915): Couldn't get kernel wake lock stats
,D/WirelessDisplayService(  915): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  915): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  915): mWirelessDisplayManager is null
,D/SurfaceControl(  915): Excessive delay in blankDisplay() while turning screen off: 319ms
D/PMS     (  915): nativeSetInteractive:false
,D/NfcService( 1225): ScreenObserver: OFF,
D/NfcService( 1225): applyRouting - 0
D/PMS     (  915): nativeSetInteractive:false done,
D/PMS     (  915): nativeSetAutoSuspend:true
D/PMS     (  915): nativeSetAutoSuspend:true done
D/HABCtrl (  915): TPE algorithm. remove timeout.,
D/PMS     (  915): OOBE c monitor 11
,I/InputManager(  915): Cancel all due to getting PMS screen off broadcast
V/KeyguardServiceDelegate(  915): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@440a7590)
,I/IntentController( 1110): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1225): applyRouting -2
W/ResourceType( 3903): No package identifier when getting name for resource number 0x00000064
V/KeyguardServiceDelegate(  915): **** SHOWN CALLED ****
,I/InputMethodManager( 3903): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b14200 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMN     (  915): wakingUp
D/PMS     (  915): acquireWL(41c0a4d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
I/InputMethodManagerService(  915): screenObserver, isScreenOn=false
I/InputMethodManagerService(  915): Disable input method client, pid=3903
D/PMS     (  915): acquireWL(436f9530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
D/PMS     (  915): releaseWL(436f9530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  915): No lock screen! windowToken=null
D/PMS     (  915): releaseWL(41c0a4d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  915): onScreenOn
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
,I/HtcPowerSaver(  915): >> updateStatus
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  915): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  915): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  915): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
D/MtpService( 2146): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2146): [MTP][onReceive]-
D/NfcService( 1225): applyRouting - 0
,D/NfcService( 1225): applyRouting -2
,D/AutoSetting( 1302): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  915): acquireWL(43c9d5b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
D/AlarmManager(  915): ACTION_SCREEN_ON
I/AlarmManager(  915): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  915): [AlarmQueuing] done recovering
I/AlarmManager(  915): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  915): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  915): releaseWL(43c9d5b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  915): batLight: Full, plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c800
D/qdlights(  915): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  915): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  915): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  915): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  915): onReceive: action=android.intent.action.SCREEN_ON
,I/ClockThread( 1110): stop update clock
D/TetherSettings( 3313): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3313): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3313): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3313): Cust_ConnectToPC   : spcsc>false
D/        ( 3313): Cust_ConnectToPC   : IPT>true
D/        ( 3313): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3313): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3313): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3313): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3313): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
D/WifiNative-wlan0(  915): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1302): service - onCreate()
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 4008): Change stage from stage0 to stage3
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
I/PSReceiver( 3313): onReceive:android.intent.action.USER_PRESENT
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/AutoSetting( 1302): service - AddressCache: using context: com.htc.Weather
,D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  915):    returned true
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): SET_SCREEN_ON:On
I/wpa_supplicant( 4008): htc_wext_set_keepalive +
I/wpa_supplicant( 4008): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4008): getPrivFuncNum +	
I/wpa_supplicant( 4008): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4008): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4008): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4008): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4008): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  915):    returned true
W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/AutoSetting( 1302): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/SmartNS_PSService( 3313): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3313): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/LocationManagerService(  915): request 424905b0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
I/SmartNS_PSService( 3313):  defaultType:0
D/LocationManagerService(  915): provider request: passive ProviderRequest[ON interval=0]
V/NotificationService(  915): batLight: Full, plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c800
D/qdlights(  915): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
,D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  369): ParamSet string: screen_state=on
,D/WirelessDisplayService(  915): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  915): updateScreenOn: false
W/ActivityManager(  915): Disable JIT of com.htc.bgp
,I/ActivityManager(  915): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4108 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  915): acquireWL(436fbf38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(436fbf38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(422c6b30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4015): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4015): onScreenOn: 1449832312427
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4015): onScreenOn: 1449832312427
,D/PMS     (  915): releaseWL(422c6b30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  915): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f42608
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 2
W/SensorService(  915): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f42608, eanble = 0, strlen(mName) = 91
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  915): Listener[0] = com.htc.smartdim.sensor_eye@42739760
,W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  915): goingToSleep
,D/PMS     (  915): acquireWL(4369f540): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 915 1000 null
,D/AlarmManager(  915): ACTION_SCREEN_OFF
I/AlarmManager(  915): [AlarmQueuing] screen off now: 
I/AlarmManager(  915): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  915): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  915): stopDataStallAlarm: current tag=23223 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  915): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): SET_SCREEN_ON:Off
I/wpa_supplicant( 4008): htc_wext_set_keepalive +
I/wpa_supplicant( 4008): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4008): getPrivFuncNum +	
I/wpa_supplicant( 4008): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4008): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4008): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 4008): get_ip_address source addr = 02000000
I/wpa_supplicant( 4008): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 4008): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  915):    returned true
I/AlarmManager(  915): [AlarmQueuing] wifi connection: true
D/PMS     (  915): acquireWL(4241ae68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 915 1000 null
D/PMS     (  915): releaseWL(4369f540): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  915): releaseWL(4241ae68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  369): ParamSet string: screen_state=off
,I/CalendarProvider2( 4108): Created com.android.providers.calendar.CalendarAlarmManager@41b46b50(com.android.providers.calendar.HtcCalendarProvider@41b2eed8)
,D/NetworkPolicy(  915): updateScreenOn: false
D/ContactMessageStore( 1213): start background delete task...
D/CalendarProvider2( 4108): wait start:true
D/ContactMessageStore( 1213): size: 0 , 0
D/ContactMessageStore( 1213): Background delete complete
,D/CalendarProvider2( 4108): wait end:false
,I/ActivityManager(  915): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4127 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] getTotalRam: 1873 Mb
D/PMS     (  915): acquireWL(425a21a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(425a21a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4127): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  915): acquireWL(433e9008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(433e9008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4127): isEpsOn(), nState = 0
D/PMS     (  915): acquireWL(437086b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4127 1000 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4015): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4015): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4015): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4015): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4015): onScreenOff
,D/AutoSetting( 1302): service - mHandler: cancel location update
,D/AutoSetting( 1302): service -           changes count: 0
D/libc    (  915): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  915): releaseWL(437086b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4127): getMobilePolicyEnabled, result = true
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4127): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4127): isEpsOn(), nState = 0
D/SmartSyncUtils( 4127): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4127): getMobilePolicyEnabled, result = true
D/WifiService(  915): New client listening to asynchronous messages
I/SensorManager(  915): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42739760
,W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  915): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 1
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42739760, eanble = 0, strlen(mName) = 36
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 0
W/SensorService(  915): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42739760, eanble = 0, strlen(mName) = 36
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  915): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42739760
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  915): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42739da0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  915): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42739da0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  915): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  915): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  915): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  915): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  915): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  915): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  915): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  915): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  915): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  915): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  915): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  915): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  915): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  915): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  915): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  915): 	at dalvik.system.NativeStart.main(Native Method)
,D/libc    (  915): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  915): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  915):    returned true
,D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4008): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4008): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  915):    returned true
,D/WifiStateMachine(  915): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  915): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  915): releaseWL(436b4d70): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4008): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  915):    returned true
,D/WifiStateMachine(  915): gateway: /192.168.1.1
D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  915): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4008): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 4008): htc_wext_set_keepalive +
I/wpa_supplicant( 4008): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4008): getPrivFuncNum +	
I/wpa_supplicant( 4008): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4008): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4008): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4008): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4008): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  915):    returned true
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  915): VerifyingLinkState enter
D/WifiStateMachine(  915): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  915): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  915): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  915): WAN detection
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,V/NetworkPolicy(  915): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/ConnectivityService(  915): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  915): Provision feature enable=false
D/ConnectivityService(  915): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  915): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  915): default: teardown()
D/MDST    (  915): default: setTeardownRequested(true)
D/MDST    (  915): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WISPrService( 3313): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/MDST    (  915): default: setTeardownRequested(true)
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  915): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  915): Unexpected mtu value: android.net.wifi.WifiStateTracker@4248a018
,D/ConnectivityService(  915): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
D/WifiStateMachine(  915): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  915): syncGetConfiguredNetworks
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  915): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  915): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  915): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  915): handleConnectivityChange: resetting
D/Nat464Xlat(  915): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  915): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  915): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  915): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  915): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  915): acquireWL(431218c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 915 1000 null
,D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
D/WirelessDisplayService(  915): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WirelessDisplayService(  915):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/QuickSettingWifi( 1110): receive.wifiConnect:true wifiAPname:NG700 elapse:4
,I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
,I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  915): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/PMS     (  915): releaseWL(431218c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CalendarProvider2( 4108): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4108): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3822): ---------------------------------------------------
,D/ProviderChangeReceiver( 3822): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3822): start to updateAlertNotification!
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3822): No fired or scheduled alerts
,D/HtcAlertUtils( 3822): -- cancelReminderNotification --
,D/HtcAlertUtils( 3822): broadcastExistReminder!
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  915): [AlarmQueuing] connectivity wifi: true
V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/ActivityManager(  915): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4185 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(43ca8e78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 915 1000 null
D/GpsLocationProvider(  915): [handleMessage] UPDATE_NETWORK_STATE
,V/Tethering(  915): bSetPropertyMultiRAB:false
D/Tethering(  915): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  915): NoActiveNetworkState
D/GpsLocationProvider(  915): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/Tethering(  915): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  915): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  915): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  915): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  915): Found interface wlan0
,D/Tethering(  915): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
,I/ConnectivityHelper( 1250): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckState
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1533/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.docs (3747/10100)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.htc.launcher (1250/10076)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.musicenhancer (3389/10053)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/libc    (  915): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-,err=8
D/libc    (  915): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  915): [NET] getaddrinfo-, 1
D/libc    (  915): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =4988 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=50 [2][1][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.docs (3747/10100)
D/PMS     (  915): acquireWL(425abf10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  915): getAGpsConnectionInfo connType - 4
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
,D/GpsLocationProvider(  915): ignore wifi update if we are not in OPENING or CLOSING
D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 148
D/libc    (  362): [NET]res_nsend:resplen=104
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  915): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(4272e168): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,I/MusicStore( 4185): Database version: 95
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4185): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
I/IntentController( 1110): receive(android.intent.action.TIME_SET,4,false)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1521): [EventService] EVENT_RESET_THEME_TIMESTAMP
I/FeedActionBar( 1250): updateLastUpdatedTime(in String) LAST UPDATED 12:10
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/DotMatrix( 1521): [EventService] isTheSameDay:false,timestamp is early than today:true
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  915): acquireWL(42ba4750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/jxcore-log( 3903): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3903): 
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4185): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0,][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/PMS     (  915): acquireWL(42665078): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 915 1000 WorkSource{10029}
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): acquireWL(439e4e48): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 915 1000 WorkSource{10029}
,D/PMS     (  915): acquireWL(424d6020): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 915 1000 WorkSource{10029}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4185): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
D/PMS     (  915): releaseWL(425abf10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(4349a890): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 915 1000 WorkSource{10029}
,W/dalvikvm( 1198): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1198): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1198): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1198): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1198): Using platform SSLCertificateSocketFactory
D/PMS     (  915): acquireWL(43fb72c8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 915 1000 WorkSource{10096}
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4185): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  915): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4219 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/GpsLocationProvider(  915): [handleMessage] INJECT_NTP_TIME
,W/ContextImpl( 4185): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/GpsLocationProvider(  915): NTP server returned: 1449832315032 (Fri Dec 11 12:11:55 CET 2015) reference: 107561 certainty: 7 system time offset: -150
,D/GpsLocationProvider(  915): reportAGpsStatus with type = 12090status = 30767ipAddr = [B@43c605a8ssid = nullpassword = null
,D/GpsLocationProvider(  915): xtraDownloadRequest
D/PMS     (  915): releaseWL(4272e168): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(43c60578): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(43c60578): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4185, uid=10154, userID:0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(434418a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(434418a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(43be0378): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,W/dalvikvm( 1966): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/GpsLocationProvider(  915): [handleMessage] INJECT_NTP_TIME_FINISHED
D/GpsLocationProvider(  915): [handleMessage] REPORT_AGPS_STATUS
D/GpsLocationProvider(  915): handleReportAgpsStatus with type = 12090status = 30767ipAddr = [B@43c605a8ssid = password = null
D/GpsLocationProvider(  915): getAGpsConnectionInfo connType - 12090
D/GpsLocationProvider(  915): reportAGpsStatus agpsConnInfo is null for type 12090
D/GpsLocationProvider(  915): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  915): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  915): releaseWL(43be0378): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PhenotypeConfigurator( 1198): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(435769b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/libc    (  915): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-,err=8
D/libc    (  915): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  915): [NET] getaddrinfo-, 1
D/libc    (  915): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =daac +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/PMS     (  915): releaseWL(435769b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
D/PMS     (  915): acquireWL(438b6da0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
I/ActivityManager(  915): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1966): Failed to find provider info for com.android.contacts.metadata
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/PMS     (  915): releaseWL(439e4e48): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/MediaRouterService(  915): Client com.google.android.music (pid 4185): Registered
,D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,I/MediaRouter( 4185): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/NetworkMonitor( 4185): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.music (4185/10154)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
D/libc    (  915): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
I/global  (  915): call createSocket() return a new socket.
D/libc    (  915): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,E/Auth.Api.Credentials( 1966): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  915): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4242 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/MediaRouter( 4185): getSelectedRoute
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 4185): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 1198): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.google.android.music (4185/10154)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): acquireWL(43c5fae0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 915 1000 WorkSource{10029}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4185, uid=10154, userID:0
D/PMS     (  915): releaseWL(438b6da0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,I/IntentController( 1110): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/GpsLocationProvider(  915): [handleDownloadXtraData] calling native_inject_xtra_data
,D/Process (  915): killProcessQuiet, pid=3747
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  915): acquireWL(4403b290): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
I/ActivityManager(  915): Killing 3747:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/PMS     (  915): releaseWL(4349a890): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/libc    ( 1198): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1198): [NET] getaddrinfo-, 1
D/libc    ( 1198): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =d49c +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
D/SyncManager(  915): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 27543, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  915): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 107940, reason: UserStart
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 3747
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1533/10029)
D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 1496
D/libc    (  362): [NET]res_nsend:resplen=45
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=1
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1198): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/PhoneStatusBar( 1110): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=50 [2][1][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ACRA    ( 4242): ACRA is enabled for com.facebook.katana, intializing...
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ACRA    ( 4242): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4242): Looking for error files in /data/data/com.facebook.katana/app_minidumps
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1323): Unsupported attribute readOnly
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/PMS     (  915): releaseWL(4403b290): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  915): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  915): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  915):  [handleDownloadXtraData]inject done.
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(4392eab0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/PMS     (  915): releaseWL(42665078): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): acquireWL(422ba8f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 915 1000 WorkSource{10029}
,D/PMS     (  915): releaseWL(4392eab0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/SystemClassLoaderAdder( 4242): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4219): Delaying sync.
V/DexLibLoader( 4242): Preparing secondary program dexes.
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4242): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4242): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4242): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4242): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4242): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(43706058): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(43706058): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(424ae7f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
W/DexLibLoader( 4242): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4242): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4242): Dex already copied
D/OdexVerifier( 4242): Odex verification is skipped.
V/DexLibLoader( 4242): Creating class loader
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
V/DexLibLoader( 4242): Finished creating class loader
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4242): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4242): Dex already copied
D/OdexVerifier( 4242): Odex verification is skipped.
V/DexLibLoader( 4242): Creating class loader
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCO,M Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
V/DexLibLoader( 4242): Finished creating class loader
V/DexLibLoader( 4242): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
V/DexLibLoader( 4242): Dex already copied
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/OdexVerifier( 4242): Odex verification is skipped.
,V/DexLibLoader( 4242): Creating class loader,
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): releaseWL(424ae7f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(435c5918): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(435c5918): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,V/DexLibLoader( 4242): Finished creating class loader
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
V/DexLibLoader( 4242): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
V/DexLibLoader( 4242): Dex already copied
D/OdexVerifier( 4242): Odex verification is skipped.
V/DexLibLoader( 4242): Creating class loader
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  915): acquireWL(43c43388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
V/DexLibLoader( 4242): Finished creating class loader
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4242): Verifying classes from secondary dexes.
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  915): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): releaseWL(43c43388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(4408c360): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(4408c360): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/Process (  915): killProcessQuiet, pid=3771
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/PMS     (  915): acquireWL(43472a58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(43fb72c8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/ActivityManager(  915): Killing 3771:com.htc.backup/1000 (adj 15): empty #17
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 3771
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  915): releaseWL(43472a58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/DexLibLoader( 4242): DexLibLoader.ensureDexLoaded took 143 ms
,W/DriveInitializer( 1966): Awaiting to be initialized
,W/DriveInitializer( 1966): Background init thread started
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 1966): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,E/BTIF_CORE( 3949): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3949): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3949): Wake lock released
,D/libc    ( 1198): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,W/DriveInitializer( 1966): Background init thread ended
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(42630748): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,D/PMS     (  915): releaseWL(43c5fae0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL,
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): acquireWL(43907cd0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 915 1000 WorkSource{10096}
D/PMS     (  915): releaseWL(42630748): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(43637138): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  915): releaseWL(422ba8f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): acquireWL(440fe5b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 915 1000 WorkSource{10029}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
D/PMS     (  915): releaseWL(43637138): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(439c6660): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(424d6020): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): releaseWL(439c6660): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(4405f858): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/DelayedSyncController( 4219): Delaying sync.
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): releaseWL(4405f858): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(43909cf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(43909cf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(44077088): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(43907cd0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50,
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/PMS     (  915): acquireWL(425b9598): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 915 1000 WorkSource{10029}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,W/PhenotypeConfigurator( 1198): Server returned 404
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): releaseWL(44077088): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  915): acquireWL(4260d390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(431213f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
D/PMS     (  915): releaseWL(431213f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/PMS     (  915): releaseWL(42ba4750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43fb7520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(42618508): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,W/AlarmManager(  915): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{43ff74c0: PendingIntentRecord{4356d6c0 com.google.android.gms startService}}) : type=2 triggerAtTime=315360108693 win=-1 tElapsed=315360108693 maxElapsed=551880108691 interval=0 standalone=false
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  915): releaseWL(425b9598): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/PMS     (  915): acquireWL(43c70928): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 915 1000 WorkSource{10160}
D/PMS     (  915): releaseWL(42618508): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  915): releaseWL(4260d390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(42f1eb20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): acquireWL(43bed5a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(42f1eb20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/PMS     (  915): acquireWL(4262d6d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(43bed5a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(434303a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43c70928): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/PMS     (  915): acquireWL(43c4bd98): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 915 1000 WorkSource{10160}
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
D/PMS     (  915): releaseWL(4262d6d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(43098e28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(43098e28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  915): releaseWL(43fb7520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(434303a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(4393b048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(43459268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/PMS     (  915): releaseWL(440fe5b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  915): releaseWL(4393b048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(4348e8b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 915 1000 WorkSource{10029}
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): acquireWL(43bec668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43459268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(43c69710): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(43c69710): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(43924c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(43c4bd98): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/PMS     (  915): releaseWL(43924c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  915): acquireWL(438c82c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(44054428): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(4348e8b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1110): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  915): releaseWL(44054428): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,I/VacuumService( 1198): Vacuum at: now=1449832316354 tag=VacuumService
,D/PMS     (  915): acquireWL(44014208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(438c82c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43bec668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(440118f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(44014208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneStatusBar( 1110): removeIcon slot=sync_active index=7 viewIndex=0
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/PMS     (  915): releaseWL(440118f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(4367e810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/PMS     (  915): releaseWL(4367e810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(436f5740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  915): releaseWL(436f5740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4242): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4242): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4242): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4242): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4242): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4242): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4242): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  915): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  915): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
,W/dalvikvm( 4242): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  915): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-,err=8
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  915): [NET] getaddrinfo-, 1
,D/libc    (  915): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =62a1 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,W/dalvikvm( 4242): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  915): Find DNS Address www.htc.com/23.59.123.86
,E/FbInjectorInitializer( 4242): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4242): Verify
,D/WifiService(  915): New client listening to asynchronous messages
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4242): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4242): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,I/ActivityManager(  915): Killing 3788:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  915): killProcessQuiet, pid=3788
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  915): Recipient 3788
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1302): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  915): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4296 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1302): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1302): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1302/10055)
,D/AutoSetting( 1302): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1302): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1302/10055)
,W/fb4a(:<default>):UserScope( 4242): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4242): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4242): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4296): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4296): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4296): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4296): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4296/10079)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4296/10079),
D/PMS     (  915): acquireWL(438e1680): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4310 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  915): killProcessQuiet, pid=3734,
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 3734:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4296/10079)
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 3734
,D/PMS     (  915): acquireWL(43caf460): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449796471211 min interval config: 0 actual interval: 35846251
D/PMS     (  915): releaseWL(438e1680): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checking schedule, now: 1449832317476 next: 1449796501166
,I/CheckinService( 1966): active receiver: enabled
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1966, uid=10029, userID:0
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/GAV2    ( 4310): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 4310): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4310): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4310): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4310): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1449831011995
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 9.954MB for 84664-byte allocation
E/dalvikvm( 4242): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4242): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 9.970MB for 28144-byte allocation
,E/dalvikvm( 4242): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4242): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4242): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4242): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4242): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4242): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4242): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4242): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4242): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4242): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/dalvikvm( 4242): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4242): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4242): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4242): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4242): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4242): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4310/10151)
,V/WebViewChromiumFactoryProvider( 4310): Binding Chromium to main looper Looper (main, tid 1) {41b077d8}
,I/LibraryLoader( 4310): Expected native library version number "",actual native library version number ""
,I/chromium( 4310): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4310): Initializing chromium process, renderers=0
,D/PMS     (  915): acquireWL(436abb28): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,E/AudioManagerAndroid( 4310): BLUETOOTH permission is missing!
D/PMS     (  915): acquireWL(42c258f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  915): releaseWL(436abb28): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4310): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4310): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4310): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4310): Local Branch: 
I/Adreno-EGL( 4310): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4310): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4310):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 10.036MB for 39954-byte allocation
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
D/WifiService(  915): New client listening to asynchronous messages
I/ActivityManager(  915): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 10.112MB for 79892-byte allocation
,I/NSApplication( 4310): Starting up...
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4310/10151)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4310/10151)
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [3][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (3580/10160)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (3580/10160)
,D/Process (  915): killProcessQuiet, pid=3506
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  915): Killing 3506:com.google.android.gm/u0a107 (adj 15): empty #17
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
,I/iu.SyncManager( 1966): SYNC; picasa accounts
,D/NetworkLogImpl( 1966): Loaded NetworkSpeedPredictor
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 1966): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,I/iu.UploadsManager( 1966): num queued entries: 0
,I/iu.UploadsManager( 1966): num updated entries: 0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
I/iu.SyncManager( 1966): NEXT; no task
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/wpa_supplicant( 4008): nl80211: survey data missing!
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 10.276MB for 75760-byte allocation
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,I/ActivityManager(  915): Recipient 3506
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43652948 u0 ReceiverList{436e7788 4242 com.facebook.katana/10027/u0 remote:436e73e8}}
,W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{436382f0 u0 ReceiverList{43638290 4242 com.facebook.katana/10027/u0 remote:43637ec0}}
,D/AlertReceiver( 3822): beginStartingService
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/PMS     (  915): acquireWL(42c08988): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3822 10013 null
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/PMS     (  915): acquireWL(433fe2d8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1335): [NET] getaddrinfo-, 1
D/libc    ( 1335): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =29f +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/AlertService( 3822): start to updateAlertNotification!
V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 221
D/libc    (  362): [NET]res_nsend:resplen=79
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1335): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  915): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4361 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/ContactMessageStore( 1213): notify MmsSms
D/AccFlag ( 1213): sense_version=6.0
,D/AccFlag ( 1213): sku_id=99
,D/AlertService( 3822): No fired or scheduled alerts
,D/HtcAlertUtils( 3822): -- cancelReminderNotification --
,D/HtcAlertUtils( 3822): broadcastExistReminder!
,W/WeatherRequest( 1110): request cur loc, but there is no sys cur
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  915): acquireWL(441a0188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10029}
V/AlarmManager(  915): sending alarm PendingIntent{43c8e2f8: PendingIntentRecord{43feaf50 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
D/PMS     (  915): releaseWL(441a0188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
,W/AlertReceiver( 3822): stopSelfResult true
D/PMS     (  915): releaseWL(42c08988): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/PMS     (  915): acquireWL(440109e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4376 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,D/AccFlag ( 1213): sku_id=99
D/PMS     (  915): releaseWL(440109e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/WeatherUtility( 4361): can't get weather sync account
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 43
,D/AccFlag ( 1213): sku_id=99
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1335): [NET] getaddrinfo-, 1
,D/libc    ( 1335): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =2485 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/ConnectivityService(  915): getNetworkInfo networkType=9 called by com.google.android.gms (1966/10029)
,W/WeatherRequest( 4361): request cur loc, but there is no sys cur
,W/Settings( 4361): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  915): acquireWL(4370d040): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4376 10071 null
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 67
,D/AccFlag ( 1213): sku_id=99
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [8][0][0]
D/PMS     (  915): acquireWL(43708270): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4376 10071 null
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/PMS     (  915): releaseWL(4370d040): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1335): [NET] getaddrinfo_proxy-, success
,D/TodoTaskshortcut( 4376): update TASK shortcut>
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
I/ActivityManager(  915): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4397 uid=10090 gids={50090, 3003, 5012, 1028}
,D/AppWidgetHostView( 1250): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1250): com.htc.widget.weatherclock (true,33751552)
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 68
,D/AccFlag ( 1213): sku_id=99
,I/RemoteViews.Performance( 1250): com.htc.widget.weatherclock 1 8 17
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
,I/TodoTaskNotifyService( 4376): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  915): acquireWL(42428378): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/TodoTaskNotifyService( 4376): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/WorldClock.Global( 4397): isHtcDevice = true
D/PMS     (  915): releaseWL(42428378): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43708270): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1335): [NET] getaddrinfo-,err=8
,W/NotifyReceiver( 4376): stopSelfResult true
,I/WorldClock.Global( 4397): isHtcDevice = true
,D/Process (  915): killProcessQuiet, pid=3601
D/PMS     (  915): acquireWL(42bf5640): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,I/ActivityManager(  915): Killing 3601:com.android.vending/u0a74 (adj 15): empty #17
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/WorldClock.AlarmUtils( 4397): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/GCM     ( 1335): GCM config loaded
,I/WorldClock.AlarmUtils( 4397): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4397): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1110): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1335): [NET] getaddrinfo-, 1
D/libc    ( 1335): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =a735 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1335): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
,D/PMS     (  915): acquireWL(425eeae8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
I/ActivityManager(  915): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4422 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=7 [14][1][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
,D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 3601
,D/PMS     (  915): acquireWL(42579cc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  915): killProcessQuiet, pid=3877
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
I/ActivityManager(  915): Killing 3877:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/TimeService( 4422): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832318265
I/ActivityManager(  915): Recipient 3877
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  915): releaseWL(433fe2d8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1335/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  915): handleInetConditionChange: starting a change hold
,D/PMS     (  915): releaseWL(42579cc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  915): killProcessQuiet, pid=4036
,I/ActivityManager(  915): Killing 4036:com.htc.widget.process2/u0a50 (adj 15): empty #17
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  915): acquireWL(433d2fc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(4262cc40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1335/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/PMS     (  915): releaseWL(4262cc40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): handleInetConditionChange: currently in hold - not setting new end evt
I/ActivityManager(  915): Recipient 4036
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1335/10029)
D/PMS     (  915): acquireWL(42610ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: currently in hold - not setting new end evt
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449796471211 min interval config: 0 actual interval: 35847100
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/PMS     (  915): acquireWL(43117c70): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1966 10029 null
,D/PMS     (  915): releaseWL(433d2fc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43bcde38): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(425eeae8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/PMS     (  915): releaseWL(43117c70): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  915): releaseWL(43bcde38): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42610ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43c64380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/PMS     (  915): releaseWL(43c64380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1966): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
,W/dalvikvm( 1966): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 1966): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
,D/PMS     (  915): acquireWL(42626620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4443 uid=10041 gids={50041}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=20 [10][2][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/PMS     (  915): releaseWL(42626620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  915): killProcessQuiet, pid=3974
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  915): Killing 3974:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 3974
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): acquireWL(440388a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
D/PMS     (  915): acquireWL(4404ce08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4376 10071 null
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
D/PMS     (  915): acquireWL(425bd870): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4376 10071 null
D/PMS     (  915): acquireWL(43537a98): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4376 10071 null
D/PMS     (  915): releaseWL(4404ce08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  915): Delay finish: com.htc.task/.notification.NotifyReceiver
E/TodoTaskNotifyService( 4376): java.lang.NullPointerException
W/System.err( 4376): java.lang.NullPointerException
,W/System.err( 4376): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4376): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4376): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4376): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4376): stopSelfResult true
D/PMS     (  915): acquireWL(425bd870): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4376 10071 null
D/PMS     (  915): releaseWL(43537a98): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  915): releaseWL(425bd870): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  915): releaseWL(440388a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  915): Resuming delayed broadcast
D/PMS     (  915): acquireWL(4345f3d0): PARTIAL_WAKE_LOCK  GCMSEND 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
I/ActivityManager(  915): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4459 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/PMS     (  915): releaseWL(4345f3d0): PARTIAL_WAKE_LOCK  GCMSEND 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4459): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4459): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4459): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4459): install
,I/MultiDex( 4459): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4459): loading existing secondary dex files
,I/MultiDex( 4459): load found 3 secondary dex files
,I/MultiDex( 4459): install done
,W/dalvikvm( 4459): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4459): VFY: unable to resolve instance field 36
,W/dalvikvm( 4459): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4459): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4459): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4459): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/WearableService( 1198): callingUid 10029, callindPid: 1198
,W/dalvikvm( 4459): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/ConnectivityService(  915): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/dalvikvm( 4459): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4459): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4459): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4459): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/LocationInitializer( 1966): Restart initialization of location
,W/dalvikvm( 4459): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,E/MDM     ( 1198): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1335): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1335): Proximity feature is not enabled.
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1198): No location to return for getLastLocation()
,W/FusedLocationProvider( 1198): location=null
D/PMS     (  915): acquireWL(43bafc40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43bafc40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4242): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4242): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4242): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/ActivityManager(  915): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4482 uid=10078 gids={50078}
I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4459): Install completed successfully. count=14 extracted=0
,D/SMSBackup( 4482): Got a database change event
,W/dalvikvm( 4459): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/Process (  915): killProcessQuiet, pid=3993
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,W/dalvikvm( 4459): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4459): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/ActivityManager(  915): Killing 3993:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
W/dalvikvm( 4459): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4459): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 4459): Using platform SSLCertificateSocketFactory
I/ActivityManager(  915): Recipient 3993
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 4459): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4459): [NET] getaddrinfo-,err=8
D/libc    ( 4459): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4459): [NET] getaddrinfo-, 1
,D/libc    ( 4459): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =ed36 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/WVCdm   (  369): PrepareKeyRequest: nonce=1933204403
,D/Process (  915): killProcessQuiet, pid=4127
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4127:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 4127
,D/WifiService(  915): Client connection lost with reason: 4
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 290
D/libc    (  362): [NET]res_nsend:resplen=86
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4459): [NET] getaddrinfo_proxy-, success
,I/WVCdm   (  369): CdmEngine::CloseSession
,I/Icing   ( 1966): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/Icing   ( 1966): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/PMS     (  915): releaseWL(42bf5640): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4459): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4459): [NET] getaddrinfo-,err=8
D/libc    ( 4459): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4459): [NET] getaddrinfo-,err=8
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  369): PrepareKeyRequest: nonce=4216564607
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,W/fb4a(:<default>):UserScope( 4242): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4242): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  915): acquireWL(42578f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=112530, Int=0
,D/PMS     (  915): releaseWL(42578f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=9 [31][3][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/PMS     (  915): acquireWL(43bb2c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10014}
,V/AlarmManager(  915): sending alarm PendingIntent{426c96f8: PendingIntentRecord{4258fad8 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=112616, Int=0
,D/PMS     (  915): acquireWL(42bb1ef8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4108 10014 null
,D/PMS     (  915): releaseWL(43bb2c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/PMS     (  915): releaseWL(42bb1ef8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4242): Called registerBroadcastReceiver twice.
,D/PMS     (  915): releaseWL(43ca8e78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  915): acquireWL(43c94018): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4185 10154 null
,W/ContextImpl( 4185): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4185, uid=10154, userID:0
I/MusicLeanback( 4185): Conditions not met for autocaching.
,I/MusicLeanback( 4185): Stop autocaching.
,W/ContextImpl( 4185): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  915): releaseWL(43c94018): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,W/Settings( 4459): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4242/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (4459/10029)
,I/Adreno-EGL( 4459): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4459): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4459): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4459): Local Branch: 
I/Adreno-EGL( 4459): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4459): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4459):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4459): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4459): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4459): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4459): Local Branch: 
I/Adreno-EGL( 4459): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4459): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4459):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4459): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4459): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4459): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4459): Local Branch: 
I/Adreno-EGL( 4459): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4459): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4459):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  915): releaseWL(42c258f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1966): [NET] getaddrinfo-,err=8
D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 1966): [NET] getaddrinfo-, 1
D/libc    ( 1966): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =39dc +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1966): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1966): Sending checkin request (12365 bytes)
,I/CheckinResponseProcessor( 1966): From server: 2 gservices updates and 0 deletes
,I/CertBlacklister(  915): Certificate blacklist changed, updating...
,I/CertBlacklister(  915): Certificate blacklist updated
,I/GservicesProvider( 1335): main difference update completed
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  915): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4517 uid=10016 gids={50016, 3003, 5012, 2001}
I/ActivityManager(  915): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4296/10079)
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4517): Update started
,E/UpdateRequestReceiver( 4517): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  915): getAllNetworkInfo called by  (2146/10021)
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4517): Update started
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getNetworkInfo networkType=9 called by com.google.android.gms (1966/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=5 [17][1][0]
,E/UpdateRequestReceiver( 4517): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/DownloadManager( 2146): Download 199 starting
,E/UpdateRequestReceiver( 4517): Received malformed URL while handling Gservices.CHANGED_ACTION
D/PMS     (  915): acquireWL(42455038): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2146 10021 WorkSource{10016}
D/ConnectivityService(  915): getAllNetworkInfo called by  (2146/10021)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,W/ActivityThread( 2146): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/UpdateRequestReceiver( 4517): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
I/ActivityManager(  915): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4547 uid=10032 gids={50032, 3003, 5012}
D/ConnectivityService(  915): getAllNetworkInfo called by  (2146/10021)
D/Process (  915): killProcessQuiet, pid=3313
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3313:com.android.settings/1000 (adj 15): empty #17
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
D/PMS     (  915): acquireWL(43904a50): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2146 10021 WorkSource{10016}
I/DownloadManager( 2146): Download 200 starting
D/ConnectivityService(  915): getAllNetworkInfo called by  (2146/10021)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
D/libc    ( 2146): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2146): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2146): [NET] getaddrinfo-,err=8
D/libc    ( 2146): [NET] getaddrinfo-,err=8
D/libc    ( 2146): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2146): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2146): [NET] getaddrinfo-, 1
D/libc    ( 2146): [NET] getaddrinfo-, 1
D/libc    ( 2146): [NET] getaddrinfo_proxy+
D/libc    ( 2146): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  362): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =146b +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] +++++ res_nsend xid =50d1 +++++
D/libc    (  362): [NET] NOT IN CACHE
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  915): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [2][0][0]
I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/ActivityManager(  915): Recipient 3313
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/CheckinService( 1966): Checking schedule, now: 1449832321778 next: 1450355258755
I/CheckinService( 1966): active receiver: disabled
D/WifiService(  915): Client connection lost with reason: 4
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11
D/libc    (  362): [NET]res_nsend:resplen=49
D/libc    (  362): [NET]res_queryN: exit 3, ancount=1
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET]res_nsend:resplen=49
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET]res_queryN: exit 3, ancount=1
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    ( 2146): [NET] getaddrinfo_proxy-, success
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2146): [NET] getaddrinfo_proxy-, success
,D/PMS     (  915): acquireWL(434b3bb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4547, uid=10032, userID:0
,D/CheckinService( 1966): Recording last checkin time for package unspecified as 1449832321799
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4547, uid=10032, userID:0
D/PMS     (  915): releaseWL(434b3bb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4547, uid=10032, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4547, uid=10032, userID:0
D/PMS     (  915): releaseWL(43caf460): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4547, uid=10032, userID:0
I/ActivityManager(  915): Resuming delayed broadcast
,D/PMS     (  915): acquireWL(43ca0ec0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43ca0ec0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43b58be0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43b58be0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2146): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  915): acquireWL(43bac2e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43bac2e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/ContactAccountLoggerTas( 2572): canRun() : Opted Out
,I/Search.GservicesUpdateTask( 2572): Updating Gservices keys
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
,D/PMS     (  915): acquireWL(4364d3f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(4364d3f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(438fff30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(438fff30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
,D/PMS     (  915): acquireWL(440e7130): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Resuming delayed broadcast
,D/Process (  915): killProcessQuiet, pid=4242
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  915): releaseWL(440e7130): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  915): Killing 4242:com.facebook.katana/u0a27 (adj 15): empty #17
,I/DownloadManager( 2146): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  915): acquireWL(44078528): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 3580): Grow heap (frag case) to 13.625MB for 1821008-byte allocation
,I/DownloadManager( 2146): Download 200 finished with status SUCCESS
D/PMS     (  915): acquireWL(43c84db8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/PMS     (  915): releaseWL(44078528): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43904a50): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3580, uid=10160, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3580, uid=10160, userID:0
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449832321799 min interval config: 0 actual interval: 225
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 3580): Grow heap (frag case) to 15.318MB for 1821008-byte allocation
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3580, uid=10160, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3580, uid=10160, userID:0
I/CheckinService( 1966): Checking schedule, now: 1449832322048 next: 1450355258755
,I/CheckinService( 1966): active receiver: disabled
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3580, uid=10160, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3580, uid=10160, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3580, uid=10160, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3580, uid=10160, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3580, uid=10160, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3580, uid=10160, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3580, uid=10160, userID:0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3580, uid=10160, userID:0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,I/SystemUpdateService( 1966): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/Process (  915): killProcessQuiet, pid=3389
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3389:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/PMS     (  915): acquireWL(4273cdb8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43c84db8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  915): Recipient 3389
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ContactAccountLoggerTas( 2572): canRun() : Opted Out
I/ContactAccountLoggerTas( 2572): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2572): canRun() : Opted Out
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  915): Client connection lost with reason: 4
,I/ActivityManager(  915): Recipient 4242
,I/DownloadManager( 2146): Download 199 finished with status SUCCESS
,D/PMS     (  915): releaseWL(42455038): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/SystemUpdateService( 1966): onCreate
D/SystemUpdateService( 1966): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 1966): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
I/SystemUpdateService( 1966): cancelUpdate (empty URL)
,I/SystemUpdateService( 1966): active receiver: disabled
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1335): [NET] getaddrinfo-, 1
,D/libc    ( 1335): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =e26a +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1335): [NET] getaddrinfo_proxy-, success
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
,D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
,D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/PMS     (  915): releaseWL(4273cdb8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 4310): Thread[GAThread,5,main]: No campaign data found.
,D/SystemUpdateService( 1966): onDestroy
,E/DynamiteModule( 1966): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1966): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1966): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1966): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1966): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1966): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1966): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1966): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1966): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1966): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1966): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1966): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 1966): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 1966): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 1966): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 1966): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1966): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1966): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 1966): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 1966): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1966): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1966): Selected local version of com.google.android.gms.flags
,D/PMS     (  915): acquireWL(43ff80f0): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,D/SystemEventReceiver( 1966): Received GSERVICES_CHANGED broadcast
,W/SQLiteConnectionPool( 1966): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/OcrUtils( 1966): Updating ocr activity enabled=false
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1966, uid=10029, userID:0
,D/PMS     (  915): releaseWL(43ff80f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1198, uid=10029, userID:0
,W/ActivityManager(  915): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(43baa650): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,I/IntentController( 1110): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  915): acquireWL(4350fd50): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 915 1000 WorkSource{10029}
D/PMS     (  915): releaseWL(43baa650): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1966, uid=10029, userID:0
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/OcrModelManager( 1966): Updating downloaded model state (gservices changed)
,D/PMS     (  915): acquireWL(43c6b5f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/GCM     ( 1335): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/PMS     (  915): releaseWL(43c6b5f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1110): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(43c5ed78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,I/IntentController( 1110): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  915): releaseWL(4350fd50): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  915): releaseWL(43c5ed78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1110): removeIcon slot=sync_active index=7 viewIndex=0
,I/ContactAccountLoggerTas( 2572): canRun() : Opted Out
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,E/dalvikvm( 1198): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1198): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,W/dalvikvm( 1198): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  915): acquireWL(440d3258): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,W/AlarmManager(  915): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{43c47728: PendingIntentRecord{43c93758 com.google.android.gms startService}}) : type=2 triggerAtTime=315360115736 win=-1 tElapsed=315360115736 maxElapsed=551880115735 interval=0 standalone=false
,I/GCoreUlr( 1198): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1198): DispatchingService.onCreate()
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/PMS     (  915): acquireWL(43f3dc80): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/GCoreUlr( 1198): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/PMS     (  915): acquireWL(43c61a28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43c61a28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/ctxmgr  ( 1198): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
D/ConnectivityService(  915): getAllNetworkInfo called by  (2146/10021)
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DownloadManager( 2146): Download 201 starting
D/PMS     (  915): acquireWL(4241ae68): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2146 10021 WorkSource{10016}
D/ConnectivityService(  915): getAllNetworkInfo called by  (2146/10021)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [3][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
,W/ctxmgr  ( 1198): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1198): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,D/PMS     (  915): releaseWL(440d3258): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
I/DownloadManager( 2146): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  915): acquireWL(42602ef0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
D/PMS     (  915): releaseWL(42602ef0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getAllNetworkInfo called by  (2146/10021)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): acquireWL(43117270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,I/DownloadManager( 2146): Download 202 starting
D/PMS     (  915): acquireWL(42449a70): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2146 10021 WorkSource{10016}
D/PMS     (  915): releaseWL(43117270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getAllNetworkInfo called by  (2146/10021)
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  915): acquireWL(43632e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,I/DownloadManager( 2146): Download 201 finished with status SUCCESS
,I/DownloadManager( 2146): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  915): releaseWL(43632e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(4241ae68): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=3 [30][1][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (2146/10021)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,I/GCoreUlr( 1198): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1198): Unbound from all location providers
,I/GCoreUlr( 1198): Place inference reporting - stopped
D/PMS     (  915): acquireWL(4393a600): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(4393a600): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43f3dc80): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4517): Update downloaded, starting installation
,I/UpdateFetcherService( 4517): Started installation
,I/GCoreUlr( 1198): DispatchingService.onDestroy()
,I/GCoreUlr( 1198): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1198): Unbound from all location providers
,I/GCoreUlr( 1198): Place inference reporting - stopped
D/PMS     (  915): acquireWL(4374fa08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(4374fa08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2146): Download 202 finished with status SUCCESS
,D/PMS     (  915): releaseWL(42449a70): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/DownloadManager( 2146): Download 202 already finished; skipping
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4517): Update downloaded, starting installation
,I/UpdateFetcherService( 4517): Started installation
,D/PMS     (  915): acquireWL(4367cdb8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(4367cdb8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(426b8a50): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,I/ConfigUpdateInstallReceiver(  915): Not installing, new version is <= current version
,D/PMS     (  915): releaseWL(426b8a50): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  915): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Process (  915): killProcessQuiet, pid=4219
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4219:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4219
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3580): Grow heap (frag case) to 17.068MB for 1821008-byte allocation
,I/GAV2    ( 3580): Thread[GAThread,5,main]: No campaign data found.
,I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  915): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4634 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1250): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
I/Launcher( 1250): Deferring update until onResume
,D/Launcher( 1250): waitUntilResume // bindAppsUpdated
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,E/ExternalAccountType( 1323): Unsupported attribute readOnly,
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4634): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4634): MmsConfig.loadMmsSettings
,W/dalvikvm( 4634): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4634): VFY: unable to resolve instance field 36
,W/dalvikvm( 4634): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4634): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4634, uid=10111, userID:0
,W/PackageManager(  915): Unable to load service info ResolveInfo{4238b178 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  915): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  915): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  915): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  915): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  915): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  915): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  915): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  915): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  915): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  915): 	at dalvik.system.NativeStart.main(Native Method)
,W/Settings( 4634): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  915): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4657 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4634, uid=10111, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4634, uid=10111, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4634, uid=10111, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4634, uid=10111, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4634, uid=10111, userID:0
,D/PMS     (  915): acquireWL(4356e358): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4634 10111 null
,D/MessageFrequencyProvider( 4657): onCreate
,I/ProviderInstaller( 4634): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  915): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
D/MmsCustomizationProvider( 4657): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4657): GetPrviateResource
,V/GetPrviateResource( 4657): GetPrviateResource
I/[PluginManager]RegisterService( 1302): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1302): handle notify Blinkfeed plugin client changed
I/ActivityManager(  915): Waited long enough for: ServiceRecord{42629f18 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
I/ActivityManager(  915): Resuming delayed broadcast
,I/IcingCorporaProvider( 2572): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  915): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  915): acquireWL(43c61a28): PARTIAL_WAKE_LOCK  AsyncService 0x1 3580 10160 null
,D/MmsCustomizationProvider( 4657): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/PMS     (  915): releaseWL(43c61a28): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  915): Resuming delayed broadcast
D/PMS     (  915): releaseWL(4356e358): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  915): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4683 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  915): acquireWL(43b97380): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  915): killProcessQuiet, pid=3822
,I/ActivityManager(  915): Killing 3822:com.htc.calendar/u0a13 (adj 15): empty #17
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  915): killProcessQuiet, pid=4310
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  915): releaseWL(43b97380): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  915): Killing 4310:com.google.android.apps.magazines/u0a151 (adj 15): empty #18
,I/ActivityManager(  915): Recipient 3822
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/RemoteDisplayProvider(  915): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  915): start
,I/ActivityManager(  915): Recipient 4310
,D/MessageCustFlag( 4657): sense_version=6.0
I/Babel   ( 4634): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4634): MmsConfig.loadFromDatabase
,D/BTAccessoryUtil( 4657): createReceiver
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Babel   ( 4634): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4634): MmsConfig.loadFromResources
,D/BTAccessoryUtil( 4657): registerReceiver return intent = null
E/Babel   ( 4634): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4634): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4657): sku_id=99
,W/SystemReader( 4657): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4657): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4657): networkCode: 
,D/MessageCustFlag( 4657): sku_id=99
D/MmsConfig( 4657): SIE smsPri: null
,D/MmsConfig( 4657): networkCode: 
D/PMS     (  915): acquireWL(426c7a38): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/HtcFingerPrintQuickLaunchProvider( 4683): -onCreate()
,I/GCoreNlp( 1198): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/HtcTelephonyCapability( 4657): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4657): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4657): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4657): Cannot find qct_8960_interface, use default value instead
,V/Settings:HtcSettingsApplication( 4683): [4683/4683] onCreate()
,I/ActivityManager(  915): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4701 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  915): killProcessQuiet, pid=4361
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 4361:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4361
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): acquireWL(423f6a68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(423f6a68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  915): applying state to connected service
,D/LocationProviderProxy(  915): applying state to connected service
,D/PMS     (  915): acquireWL(43c5dcc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43c5dcc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(42c235c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42c235c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(436a7558): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(436a7558): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/Settings:HtcWirelessFeatureFlags( 4683): id/is att sku: 99/false
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/SystemReader( 4683): Cannot find devicepolicy_lower_fp_quality, use default value instead
D/PMS     (  915): releaseWL(426c7a38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(424d7540): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4701, uid=10074, userID:0,
,W/SystemReader( 4683): Cannot find support_harman, use default value instead,
,W/SystemReader( 4683): Cannot find effect_manager_id, use default value instead
,D/PMS     (  915): releaseWL(424d7540): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/Finsky  ( 4701): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/Settings:HtcWrapHeaderInfo( 4683): no such activity!
D/ConnectivityService(  915): getAllNetworkInfo called by com.android.vending (4701/10074)
,D/PMS     (  915): acquireWL(42463b18): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4683): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4683): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4683): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]support         :false
D/PMS     (  915): releaseWL(42463b18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(42234a38): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,W/FingerprintManager( 4683): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4683): isSupportVoWifi: null
I/ActivityManager(  915): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4683): Failed to find provider info for com.htc.vowifi
,D/PMS     (  915): releaseWL(42234a38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(424d0ca0): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/PMS     (  915): releaseWL(424d0ca0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getAllNetworkInfo called by com.android.vending (4701/10074)
,D/PMS     (  915): acquireWL(424dba20): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 4701): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/PMS     (  915): releaseWL(424dba20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(436ada20): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,W/Settings( 4701): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4701): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  915): releaseWL(436ada20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/PMS     (  915): acquireWL(425984a8): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 4701): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/PMS     (  915): releaseWL(425984a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4683): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4683): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4683): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4683): [supportHomeButton]support         :false
,W/FingerprintManager( 4683): hasFingerprint() - sSensorCode = 0
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,E/Settings:HtcVoWifiWidgetEnabler( 4683): isSupportVoWifi: null
I/ActivityManager(  915): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4683): Failed to find provider info for com.htc.vowifi
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4701, uid=10074, userID:0
,I/IcingCorporaProvider( 2572): UpdateCorporaTask done [took 656 ms] updated apps [took 656 ms] 
,D/Ads     ( 4701): Skipping gmscore version check
,D/Finsky  ( 4701): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4701): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4701): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4701): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/Process (  915): killProcessQuiet, pid=4397
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  915): Killing 4397:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 4397
D/PMS     (  915): acquireWL(4402e6a0): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b99dd8 +
,I/Prism.WidgetManager( 1250): onLoadItems() +
,E/Prism.WidgetManager( 1250): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1250): onLoadItems() -
,I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b99dd8 -
,D/PhoneApp( 1213): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1213): -- N1 =0
,D/PhoneApp( 1213): -- N2 =0
,D/PhoneApp( 1213): -- N3 =0
,I/Icing   ( 1966): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1966): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1966): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  915): releaseWL(4402e6a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4657): mNeedToUpdateDate2 start
,D/MmsConfig( 4657): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4657): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4657): 
D/MmsAsyncWorkHandler( 4657): HM tk = 20001
,D/ReportIndicatorCache( 4657): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4657): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b11338
,I/Messaging( 4657): mccmnc> 
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1213):  phoneType = -1
D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4657): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4657): [DraftCache/1] refresh
,D/MmsConfig( 4657): networkCode: 
,D/Messaging( 4657): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4657): sense_version=6.0
,D/Messaging( 4657): mNeedToUpdateDate2: false
,D/Jerry   ( 4657): start to preload cursor >>>>>>>
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 43
,D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4657): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4657): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4657): createReceiver
,D/TelephUtils( 1213): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
V/MmsProvider( 1213): Update uri=content://mms, match=0
,V/MmsProvider( 1213): selection=st=129 AND m_type!=134
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/Messaging( 4657): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4657): TransactionService is going to be woken up.
,V/TransactionService( 4657): 1-Creating TransactionService
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1213): sku_id=99
D/Messaging( 4657): ViewCache CreatePreload
,D/Messaging( 4657): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 4657): onStartCommand: 1
,D/MmsSystemEventReceiver( 4657): unRegisterForConnectionStateChanges
V/TransactionService( 4657): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4657): Loading previous transactions.
,D/Cust_MMSMS( 4657): _has_set_default_values_2=true
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/DraftCache( 4657): [DraftCache/454] rebuildCache
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/AccFlag ( 1213): device_type: 1
,D/MsgPreferenceUtils( 4657): def_index: 0
,D/Messaging( 4657): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TransactionService( 4657): Force set service start id to 1
V/TransactionService( 4657): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4657): unRegisterForConnectionStateChanges
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/Jerry   ( 1213): URI_DRAFT
D/MsgPreferenceUtils( 4657): globalIndex = 1
V/TransactionService( 4657): Destroying TransactionService
,D/TransactionService( 4657): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4657): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 4657): phone state: true
D/MsgPreferenceUtils( 4657): sd state: false
,D/MsgPreferenceUtils( 4657): vIndex = 0
D/DraftCache( 4657): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4657): [DraftCache/454] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4657): 
D/MmsAsyncWorkHandler( 4657): HM tk = 20002
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1213): sku_id=99
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1213): sku_id=99
,W/PackageSettings(  915): Skipping PackageSetting{4222bb48 com.example.hello/10396} due to missing metadata
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4634): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  915): acquireWL(430b8878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(430b8878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
,D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus,
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(43fe4980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  915): sending alarm PendingIntent{439142b0: PendingIntentRecord{424b3cc8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136067, Int=0
,D/PMS     (  915): releaseWL(43fe4980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/PMS     (  915): acquireWL(43932658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41d29330: PendingIntentRecord{424eea18 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=137709, Int=0
,D/PMS     (  915): acquireWL(436fef60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 915 1000 null
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): releaseWL(43932658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(439151b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(436fef60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  915): releaseWL(439151b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1302): service - has update message, not stop
,D/AutoSetting( 1302): service - mHandler: update timezone
,D/AutoSetting( 4108): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4108): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  915): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4108): service - onCreate()
W/ActivityManager(  915): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4108): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4108): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4108): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 4108): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4108): service - mHandler: update timezone
,D/AutoSetting( 4108): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4108): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4108): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4108): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1521): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1521): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1110): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41eb0868 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.htclocationservice 2 14 5 11
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  915): Waited long enough for: ServiceRecord{437325c0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  915): acquireWL(43c8e908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(43c8e908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(439c5848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41d29330: PendingIntentRecord{424eea18 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=167727, Int=0
,D/PMS     (  915): acquireWL(42c7e390): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 915 1000 null
D/PMS     (  915): releaseWL(439c5848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(42680108): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=11 [18][2][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/PMS     (  915): acquireWL(43633290): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 915 1000 WorkSource{10029}
,D/PMS     (  915): releaseWL(42c7e390): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  915): releaseWL(42680108): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(43253a28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(43253a28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  915): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1966): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(4260a578): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/SyncManager(  915): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 27510, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  915): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 167824, reason: UserStart
D/PMS     (  915): releaseWL(43633290): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  915): releaseWL(4260a578): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(435dff00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1533/10029)
,D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  915): releaseWL(435dff00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1323): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1302): service - handleMessage() stop self
,D/AutoSetting( 1302): service - handleMessage() quit looper
,D/AutoSetting( 1302): service - onDestroy() END
,D/AutoSetting( 4108): service - handleMessage() stop self
,D/AutoSetting( 4108): service - handleMessage() quit looper
,D/AutoSetting( 4108): service - onDestroy() END
,D/Process (  915): killProcessQuiet, pid=3836
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3836:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 3836
,D/WifiService(  915): Client connection lost with reason: 4
V/BluetoothSapService( 3949): onUnbind: android.bluetooth.IBluetoothSap
,D/PMS     (  915): acquireWL(436e3fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=172530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(436e3fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1213): switchBindHtcMsgCursor: null
,D/PMS     (  915): acquireWL(440e22e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): releaseWL(440e22e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1335): disconnect managed GoogleApiClient
,D/PMS     (  915): acquireWL(436cbe98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41d29330: PendingIntentRecord{424eea18 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=197791, Int=0
,D/PMS     (  915): acquireWL(4403b728): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 915 1000 null
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): releaseWL(436cbe98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43655498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(4403b728): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  915): releaseWL(43655498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  915): acquireWL(436e62f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(436e62f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43935d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=232530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43935d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(42c30688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(42c30688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  915): acquireWL(438e7580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(438e7580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4393bd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=292530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(4393bd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(4392e480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4392e480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3903): Connected to the server!
I/jxcore-log( 3903): 
,I/chromium( 3903): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Process (  915): killProcessQuiet, pid=4422
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4422:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4422
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): acquireWL(438da600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/PowerUI ( 1110): closing low battery warning: level=100
D/UsbnetService(  915): onReceive BATTERY_CHANGED
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PMS     (  915): releaseWL(438da600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  915): acquireWL(43924910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=352530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43924910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(4264d5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
I/BatteryService(  915): n_update end
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): releaseWL(4264d5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  915): acquireWL(43575ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43575ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(436dd328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=412530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(436dd328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1335): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4701): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4701): [NET] getaddrinfo-,err=8
D/libc    ( 4701): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4701): [NET] getaddrinfo-, 1
,D/libc    ( 4701): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =f97e +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE,
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4701): [NET] getaddrinfo_proxy-, success
,D/PMS     (  915): acquireWL(426ca8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(426ca8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4315e9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4315e9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  915): acquireWL(43444008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=472530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43444008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(432560e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(432560e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  915): acquireWL(43c81668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=532530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43c81668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(43c8dce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/PMS     (  915): releaseWL(43c8dce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  915): onReceive BATTERY_CHANGED
,D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43671a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43671a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43c79d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=592530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43c79d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43ca4420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43ca4420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1213): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1213): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1213): sku_id=99
D/ContactMessageStore( 1213): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1213): start background delete task...
D/ContactMessageStore( 1213): size: 0 , 0
,D/ContactMessageStore( 1213): Background delete complete
,D/PMS     (  915): acquireWL(43625b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): releaseWL(43625b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43fe5a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=652530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43fe5a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43cb4160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
I/BatteryService(  915): n_update end
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PMS     (  915): releaseWL(43cb4160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4362ab30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4362ab30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(436f4f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=712530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(436f4f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43f89070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43f89070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(436d4568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=772530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(436d4568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4346e908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/PMS     (  915): releaseWL(4346e908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4367d6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4367d6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43ff5218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=832530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43ff5218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43927638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43927638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(4349c050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(4349c050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
,I/HtcPowerSaver(  915): >> updateStatus
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(435e08c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=892530, Int=0
,D/PMS     (  915): releaseWL(435e08c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(42636408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/BatteryService(  915): n_update end
D/PMS     (  915): releaseWL(42636408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(435e73e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/PMS     (  915): releaseWL(435e73e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
,D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(435fd980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=952530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(435fd980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(42680ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(42680ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(440ca230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{41d5b188: PendingIntentRecord{424947d0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783386, Int=0
,D/ConnectivityService(  915): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  915): Done.
,D/ConnectivityService(  915): Setting timer for 720seconds
,I/ActivityManager(  915): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4811 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  915): sending alarm PendingIntent{42409d68: PendingIntentRecord{42515e88 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449832419911, Int=10800000
,V/AlarmManager(  915): sending alarm PendingIntent{4245a018: PendingIntentRecord{42734b20 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449832812058, Int=1800000
V/AlarmManager(  915): sending alarm PendingIntent{41ef94f0: PendingIntentRecord{41e4cd10 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449833140231, Int=900000
,V/AlarmManager(  915): sending alarm PendingIntent{42734fa0: PendingIntentRecord{4390ef18 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449833212703, Int=0
,D/PMS     (  915): acquireWL(440471a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(44082fd0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(440471a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4823 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/EventLogService( 1966): Aggregate from 1449832317582 (log), 1449831011995 (data)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.aurora (4811/10049)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,D/PMS     (  915): releaseWL(44082fd0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  915): killProcessQuiet, pid=4376
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4376:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4376
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4823): call getInstance()
,D/PMS     (  915): acquireWL(440ed170): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4823 1000 null
D/PowerUsageList:PowerUsageHelper( 4823): MY_DEBUG = false
,D/SmartSyncUtils( 4823): isEpsOn(), nState = 0
D/PMS     (  915): releaseWL(440ca230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): releaseWL(440ed170): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  915): acquireWL(4404b880): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4823 1000 null
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,D/SmartSyncScreenOnOffTimeReceiver( 4823): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4823): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4823): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4823): SettingOnTime = 1449900000000, randomSettingOnTime = 1449898983000
,D/SmartSyncScreenOnOffTimeReceiver( 4823): SettingOffTime = 1449885600000, randomSettingOffTime = 1449888536000
,D/SmartSyncScreenOnOffTimeReceiver( 4823): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4823): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4823): bNightModeTurnOffOnce = false
,D/PMS     (  915): releaseWL(4404b880): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,D/Process (  915): killProcessQuiet, pid=4482
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4482:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4482
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): acquireWL(439028f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(439028f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(42c28c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  915): sending alarm PendingIntent{43914258: PendingIntentRecord{42611b28 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1010854, Int=0
,D/PMS     (  915): acquireWL(42c054c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42c054c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42c28c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(436f41a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=23 [233][55][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,D/PMS     (  915): acquireWL(425eba68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43c5e560): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1335 10029 WorkSource{0 com.google.android.gms}
,D/PMS     (  915): acquireWL(438e6440): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,I/GCM     ( 1966): Message from null null
,E/GCM     ( 1966): Dropping message from null
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1335/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1335/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,D/PMS     (  915): releaseWL(436f41a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
,D/PMS     (  915): releaseWL(425eba68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43c5e560): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{0 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1198): Scheduling Phenotype for one-off execution 7989 seconds from now (1449833218802)
,D/GetConfigurationSnapshotOperation( 1198): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1198): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1198): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  915): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1198): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1198): [NET] getaddrinfo-, 1
D/libc    ( 1198): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =3796 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1198): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1198): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=18 [11][2][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
,E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
,D/PMS     (  915): acquireWL(42c08eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,D/PMS     (  915): releaseWL(438e6440): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1012530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  915): acquireWL(43716240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,D/PMS     (  915): releaseWL(43716240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42c08eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(436dd588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4008): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1335/10029)
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4008): nl80211: survey data missing!
E/wpa_supplicant( 4008): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4008): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026975
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027135
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027201
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027204
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027207
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360027211
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028476
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028488
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030951
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360108693
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360115736
,D/PMS     (  915): releaseWL(436dd588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43910c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  915): n_update end
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(43910c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4365cce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): releaseWL(4365cce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43944248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1072530, Int=0
,D/PMS     (  915): releaseWL(43944248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4391bae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4391bae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43c27518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1132530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43c27518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(438ddb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(438ddb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4348f3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1192530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1250): Grow heap (frag case) to 12.640MB for 50416-byte allocation
,D/PMS     (  915): releaseWL(4348f3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(42625c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(42625c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  915): acquireWL(43130358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43130358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43625410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1252530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43625410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4363f2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4363f2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(4360cb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/PMS     (  915): releaseWL(4360cb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(426e3000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1312530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(426e3000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(432563a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(432563a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(436380d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(436380d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(42f20140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1372530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(42f20140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(435e7ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(435e7ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43ca45c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1432530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43ca45c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43679c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43679c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  915): updateBatteryInfo
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  915): runPSCheck
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(44008400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(44008400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
,I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43909170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1492530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1250): Grow heap (frag case) to 12.640MB for 50416-byte allocation
,D/PMS     (  915): releaseWL(43909170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(41afe370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(41afe370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(438dc240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(438dc240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(434a0680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1552529, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(434a0680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43927618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43927618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4350f860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(4350f860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43b8eef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1612530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43b8eef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43a125f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/BatteryService(  915): n_update end
D/PMS     (  915): releaseWL(43a125f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4392f910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4392f910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43c4fa38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1672529, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43c4fa38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4252cae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4252cae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED,
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo,
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(42c26360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(42c26360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43565808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1732530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43565808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(44010280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  915): n_update end
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PMS     (  915): releaseWL(44010280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43c85728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,D/ConnectivityService(  915): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  915): sending alarm PendingIntent{41d5b188: PendingIntentRecord{424947d0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1725262, Int=0
,V/AlarmManager(  915): sending alarm PendingIntent{41d29330: PendingIntentRecord{424eea18 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1768535, Int=0
,D/PMS     (  915): acquireWL(43b1acb0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 915 1000 null
,D/PMS     (  915): releaseWL(43c85728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(43b8a260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(43b1acb0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  915): releaseWL(43b8a260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): Done.
,D/ConnectivityService(  915): Setting timer for 720seconds
,D/PMS     (  915): acquireWL(43470790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43470790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43c2a3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000},
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1792530, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43c2a3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,D/PMS     (  915): acquireWL(441acb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,I/BatteryService(  915): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(441acb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  915): acquireWL(43917850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41b08dd8: PendingIntentRecord{41d7def8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1852530, Int=0
,I/ProcessStatsService(  915): Prepared write state in 41ms
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43917850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  915): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-09-38.bin
,D/PMS     (  915): acquireWL(4390ee60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/PMS     (  915): releaseWL(4390ee60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
,I/HtcPowerSaver(  915): >> updateStatus
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4878): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4878): ====startRecUseTime====
D/htc.customization.log.level( 4878):  is 
W/CustomizationLogLevel( 4878): Level value is invalid, use default level 2
D/CustomizationManager( 4878):  Read ACC file spent 0.091 (s)
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4878): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4878): Parsing tag category name = system
I/CustomizationCIDLoader( 4878): Parsing tag category name = application
I/CustomizationCIDLoader( 4878): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4878): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4878): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4878): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4878): Parsing tag category name = Settings
D/CustomizationManager( 4878):  Read CID file spent 0.138 (s)
D/CustomizationManager( 4878):  All configurations done spent 0.139 (s)
W/HtcNativeFlag( 4878): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4878): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4878): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4878): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  915): deletePackageAsUser: pkg=com.test.thalitest, pid=4878, uid=2000 user=0
I/ActivityManager(  915): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  915): killProcessQuiet, pid=3903
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  915): Killing 3903:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  915): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  915):   Force finishing activity ActivityRecord{4238adf8 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  915): Copying FileAsset 0x67f3cda8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  915): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  915): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  915): Got RemoteException sending setActive(false) notification to pid 3903 uid 10389
E/JavaBinder( 1186): !!! FAILED BINDER TRANSACTION !!!
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  915): WIN DEATH: Window{42454b30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  915): Client connection lost with reason: 4
W/PackageSettings(  915): Skipping PackageSetting{4222bb48 com.example.hello/10396} due to missing metadata
I/ActivityManager(  915): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1521): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1521): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1521): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  915): acquireWL(435a0b30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  915): releaseWL(435a0b30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "sms"
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1277): Cleaning up data for package: com.test.thalitest
I/Launcher( 1250): Deferring update until onResume
D/Launcher( 1250): waitUntilResume // bindAppsRemoved
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "smsto"
W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mms"
I/[PluginManager]RegisterService( 1302): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/[PluginManager]RegisterService( 1302): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1250): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/IcingCorporaProvider( 2572): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/InputMethodManagerService(  915): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/ExternalAccountType( 1323): Unsupported attribute readOnly
I/ActivityManager(  915): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4894 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  915): acquireWL(43c9d4a8): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(43c98218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
D/PMS     (  915): releaseWL(43c9d4a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43c98218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  915): acquireWL(43c862c8): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2572): UpdateCorporaTask done [took 375 ms] updated apps [took 375 ms] 
E/SQLiteDatabase( 4894): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4894): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4894): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4894): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4894): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4894): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4894): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4894): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4894): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4894): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4894): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4894): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4894): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4894): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4894): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4894): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4894): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4894): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4894): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4894): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4894): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4894): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4894): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4894): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4894): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4894): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4894): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4894): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4894): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4894): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4894): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4894): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4894): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4894): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4894): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4894): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4894): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4894): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4894): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4894): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4894): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4894): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4894): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4894): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4894): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4894): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4894): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4894): threadid=11: thread exiting with uncaught exception (group=0x416d7e30)
E/ActivityManager(  915): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4894): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4894): Process: com.google.android.apps.docs, PID: 4894
E/AndroidRuntime( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4894): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4894): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4894): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4894): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4894): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  915): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  915): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  915): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  915): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  915): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  915): 	... 5 more
D/Process ( 4894): killProcess, pid=4894
D/Process ( 4894): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  915): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4912 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  915): Recipient 4894
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Process com.google.android.apps.docs (pid 4894) has died.
W/ContextImpl( 4912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  915): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4925 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4912): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4912): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4912): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4912): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4912): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4912): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4912): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4912): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4912): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4912): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4912): threadid=10: thread exiting with uncaught exception (group=0x416d7e30)
E/ActivityManager(  915): App crashed! Process: com.android.keychain
D/PMS     (  915): acquireWL(41fb6878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{41fa2f28: PendingIntentRecord{425d6170 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1824146, Int=1800000
V/AlarmManager(  915): sending alarm PendingIntent{42547b28: PendingIntentRecord{425fab78 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1847793, Int=0
V/AlarmManager(  915): sending alarm PendingIntent{4258ec68: PendingIntentRecord{43ca69c8 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1863116, Int=0
V/AlarmManager(  915): sending alarm PendingIntent{42375fb0: PendingIntentRecord{42611b28 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1910991, Int=0
E/AndroidRuntime( 4912): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4912): Process: com.android.keychain, PID: 4912
E/AndroidRuntime( 4912): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4912): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4912): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4912): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4912): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4912): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4912): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4912): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4912): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/AlarmManager(  915): sending alarm PendingIntent{41ef94f0: PendingIntentRecord{41e4cd10 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449834040231, Int=900000
D/ErrorReport(  915): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4925): getInstance(Context context)
D/Process ( 4912): killProcess, pid=4912
D/Process ( 4912): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  915): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  915): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449834118588.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  915): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  915): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  915): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  915): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  915): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  915): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  915): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  915): 	... 4 more
I/ActivityManager(  915): Recipient 4912
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Process com.android.keychain (pid 4912) has died.
D/AppTag  ( 4925): getInstance(Context context)
D/AppTag  ( 4925): onCreate()
W/ActivityManager(  915): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  915): acquireWL(43bcdfb0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3580 10160 null
D/PMS     (  915): releaseWL(43bcdfb0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4701): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1966): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1966): Module APK com.google.android.play.games already loaded
I/ActivityManager(  915): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1966): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1966): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1966): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1966): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1966): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x5ca79078
E/SQLiteDBG( 1966): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x617eb000
E/DriveAsyncService( 1966): disk I/O error (code 3850)
E/DriveAsyncService( 1966): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1966): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1966): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1966): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1966): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1966): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1966): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1966): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1966): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1966): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 1966): threadid=36: thread exiting with uncaught exception (group=0x416d7e30)
E/AndroidRuntime( 1966): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1966): Process: com.google.android.gms, PID: 1966
E/AndroidRuntime( 1966): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1966): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1966): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1966): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1966): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1966): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1966): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1966): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1966): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1966): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1966): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1966): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1966): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  915): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 1966): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1966): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1966): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1966): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1966): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1966): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1966): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1966): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1966): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1966): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1966): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1966): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  915): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  915): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  915): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  915): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  915): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  915): 	... 5 more
W/SQLiteOpenHelper( 1966): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1966): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1966): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/Process ( 1966): killProcess, pid=1966
E/SQLiteLog( 1966): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1966): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1966): threadid=50: thread exiting with uncaught exception (group=0x416d7e30)
D/Process ( 1966): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  915): Recipient 1966
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  915): Client connection lost with reason: 4
D/PMS     (  915): handleWLDeath(43c862c8): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  915): Process com.google.android.gms (pid 1966) has died.
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
I/ActivityManager(  915): Resuming delayed broadcast
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41b99dd8 +
I/Prism.WidgetManager( 1250): onLoadItems() +
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20984ms
E/SQLiteLog( 1335): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1335): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x64004338
W/dalvikvm( 1335): threadid=1: thread exiting with uncaught exception (group=0x416d7e30)
E/AndroidRuntime( 1335): FATAL EXCEPTION: main
E/AndroidRuntime( 1335): Process: com.google.process.gapps, PID: 1335
E/AndroidRuntime( 1335): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1335): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1335): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1335): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1335): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1335): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1335): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1335): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1335): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1335): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1335): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1335): 	... 10 more
E/ActivityManager(  915): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  915): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  915): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  915): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  915): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  915): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  915): 	... 5 more
D/Process ( 1335): killProcess, pid=1335
D/Process ( 1335): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  915): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4954 uid=10098 gids={50098, 3003, 5012}
W/PackageManager(  915): Unable to load service info ResolveInfo{420c42f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  915): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  915): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  915): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  915): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  915): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  915): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  915): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  915): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  915): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  915): 	at dalvik.system.NativeStart.main(Native Method)
D/WifiService(  915): Client connection lost with reason: 4
I/ActivityManager(  915): Recipient 1335
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 4954): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4954 dbg=false s=true
I/DeviceManagement( 4954): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4954): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/ActivityManager(  915): Process com.google.process.gapps (pid 1335) has died.
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20796ms
I/DeviceManagement( 4954): WorkflowService: Starting workflow service
I/DeviceManagement( 4954): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b33e20] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4954): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4954): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4954): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4954): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  915): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4968 uid=10099 gids={50099, 3003, 5012}

```
