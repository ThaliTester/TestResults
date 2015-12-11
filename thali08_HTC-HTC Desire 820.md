#### Test 5065027857de7f1_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  903): acquireWL(43b3eb28): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  903): releaseWL(43b3eb28): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  903): acquireWL(43b0ae90): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  903): releaseWL(43b0ae90): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  903): acquireWL(43ad57e0): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  903): releaseWL(43ad57e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,--------- beginning of /dev/log/main
E/cutils-trace( 3861): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3861): ====startRecUseTime====
D/htc.customization.log.level( 3861):  is 
W/CustomizationLogLevel( 3861): Level value is invalid, use default level 2
D/CustomizationManager( 3861):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3861): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3861): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3861): Parsing tag category name = system
I/CustomizationCIDLoader( 3861): Parsing tag category name = application
I/CustomizationCIDLoader( 3861): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3861): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3861): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3861): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3861): Parsing tag category name = Settings
D/CustomizationManager( 3861):  Read CID file spent 0.089 (s)
D/CustomizationManager( 3861):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 3861): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3861): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3861): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3861): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3861
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1138035224
D/PMS     (  903): acquireHCC(43aaf470): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(43aa4860): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@424a7910
D/PMS     (  903): acquireWL(43a892f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3872 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1247): [trimMemory] 20
W/asset   ( 3872): Copying FileAsset 0x5c83c428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,V/WebViewChromiumFactoryProvider( 3872): Binding Chromium to main looper Looper (main, tid 1) {41e01678}
,I/LibraryLoader( 3872): Expected native library version number "",actual native library version number ""
I/chromium( 3872): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3872): Initializing chromium process, renderers=0
,D/PMS     (  903): acquireWL(43fc7f90): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  903): acquireWL(43f7acd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427e6bb8:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapter( 3872): 1105293488: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  903): releaseWL(43f7acd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3872): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3872): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3872): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3872): Local Branch: 
I/Adreno-EGL( 3872): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3872): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3872):                  aa63bbd948f41d15fc72f585e
,W/chromium( 3872): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 3872): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 3872): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3872): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,W/dalvikvm( 3872): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 3872): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 3872): CordovaWebView is running on device made by: HTC
,W/AwContents( 3872): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  903): Disable input method client, pid=1247
W/ResourceType( 3872): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3872): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e48638, mServedView=org.apache.cordova.engine.SystemWebView{41e0e3c8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  903): Enable input method client, pid=3872
,W/AwContents( 3872): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +421ms
,D/PMS     (  903): releaseWL(43a892f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3872): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3872): JniHelper::setJavaVM(0x419be010), pthread_self() = 1662459712
,D/JX-Cordova( 3872): jxcore cordova android initializing
,W/dalvikvm( 3872): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 11.552MB for 96598-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 11.632MB for 144892-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 11.748MB for 217334-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 11.922MB for 325996-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 12.197MB for 488990-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 13.205MB for 1100216-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 14.086MB for 1650320-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 15.461MB for 2475476-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 17.521MB for 3713210-byte allocation
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(43aaf470): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(43aa4860): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3872): Initializing JXcore engine
,W/jxcore-log( 3872): JXcore engine is ready
,W/jxcore-log( 3872): Starting JXcore engine
,W/jxcore-log( 3872): Platform android
W/jxcore-log( 3872): 
,W/jxcore-log( 3872): Process ARCH arm
W/jxcore-log( 3872): 
,I/jxcore-log( 3872): JXcore Cordova bridge is ready!
I/jxcore-log( 3872): 
,W/jxcore-log( 3872): JXcore engine is started
,I/chromium( 3872): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 3872): Skipped 138 frames!  The application may be doing too much work on its main thread.
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3918 uid=10077 gids={50077}
,D/PMS     (  903): acquireWL(43a9b798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10077}
,V/AlarmManager(  903): sending alarm PendingIntent{42589aa8: PendingIntentRecord{42636a40 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449832333203, Int=60000
,D/PMS     (  903): releaseWL(43a9b798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3918): SMSBackupAgentService started
,D/SMSBackup( 3918): Checking restore status
,D/SMSBackup( 3918): Restore complete
,D/SMSBackup( 3918): cancelCheckAlarm
,D/SMSBackup( 3918): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  903): killProcessQuiet, pid=1481
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 1481:com.htc.bgp/u0a14 (adj 15): empty #17
,D/PMS     (  903): releaseWL(43fc7f90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 1481
,I/jxcore-log( 3872): Toggling radios to true
I/jxcore-log( 3872): 
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  903): checking for enable restriction...
D/BluetoothManagerService(  903): checkBTEasState, ret=true
I/BluetoothManagerService(  903): isBluetoothRestricted(): false
D/BluetoothManagerService(  903): enable(): region ID = 6
D/BluetoothManagerService(  903): enable():  mBluetooth =null mBinding = false
,W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 1
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1439
,W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  903): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  903): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3872): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1304
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
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
,W/Settings:Agent(  903): << traceCallingStack(): 1(ms)
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: true pid=3872, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/ActivityManager(  903): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3933 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3872): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 3872): reconnect: Base Package Name=com.test.thalitest, uid=10348
,I/jxcore-log( 3872): Radios toggled
I/jxcore-log( 3872): 
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3872): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 3872): 
D/PMS     (  903): acquireWL(427b3460): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
,I/jxcore-log( 3872): Perf Test app loaded loaded
I/jxcore-log( 3872): 
,I/Choreographer( 3872): Skipped 81 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3872): check test folder
I/jxcore-log( 3872): 
,I/jxcore-log( 3872): found test : ./testFindPeers.js
I/jxcore-log( 3872): 
,D/AdapterServiceConfig( 3933): Adding HeadsetService
D/AdapterServiceConfig( 3933): Adding A2dpService
D/AdapterServiceConfig( 3933): Adding HidService
D/AdapterServiceConfig( 3933): Adding HealthService
D/AdapterServiceConfig( 3933): Adding PanService
,D/AdapterServiceConfig( 3933): Adding GattService
,W/linker  ( 3933): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/jxcore-log( 3872): found test : ./testSendData.js
I/jxcore-log( 3872): 
,D/BluetoothAdapterService( 3933): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42582900:true
,D/BluetoothAdapterState( 3933): make
,I/BluetoothAdapterState( 3933): Entering OffState
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3933): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  903): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  903): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  903): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapter( 3933): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41e1ade8
,D/BluetoothAdapter( 3933): onBluetoothServiceUp done
,D/BluetoothAdapter( 1743): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42413bc8
,D/BluetoothAdapter( 1743): onBluetoothServiceUp done
D/BluetoothAdapter( 1216): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41ecd928
D/BluetoothAdapter( 1216): onBluetoothServiceUp done
D/BluetoothAdapter(  903): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42573be0
,D/BluetoothAdapter(  903): onBluetoothServiceUp done
D/BluetoothAdapter( 1391): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4207dc60
,D/BluetoothAdapter( 1391): onBluetoothServiceUp done
,D/BluetoothAdapter( 1107): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4225d058
,D/BluetoothAdapter( 1107): onBluetoothServiceUp done
,D/BluetoothAdapter( 1228): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f3b160
,D/BluetoothAdapter( 1228): onBluetoothServiceUp done
,D/BluetoothAdapter( 3872): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@429465d8
D/BluetoothAdapter( 3872): onBluetoothServiceUp done
,D/BluetoothManagerService(  903): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3933): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3933): Setting state to 11
I/BluetoothAdapterState( 3933): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3933): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  903): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  903): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3933): make
,I/BluetoothBondStateMachine( 3933): StableState(): Entering Off State
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/HeadsetService( 3933): Received start request. Starting profile...
D/HeadsetStateMachine( 3933): Version 1.6
,D/HeadsetStateMachine( 3933): make
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3959 uid=10037 gids={50037, 3002, 3001}
,I/HeadsetStateMachine( 3933): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3933): Received start request. Starting profile...
,V/Avrcp   ( 3933): make
,D/Avrcp   ( 3933): fillIntentFilter()
,I/BluetoothAdapterState( 3933): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/A2dpStateMachine( 3933): make
,D/HtcBtWidget_BTWidgetProvider( 3959): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3959): updateWidget(context) for widget: 
,I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/A2dpStateMachine( 3933): Enter Disconnected: -2
,D/Process (  903): killProcessQuiet, pid=3065
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HidService( 3933): Received start request. Starting profile...
,D/HealthService( 3933): Received start request. Starting profile...
,I/ActivityManager(  903): Killing 3065:com.android.defcontainer/u0a19 (adj 15): empty #17
D/PanService( 3933): Received start request. Starting profile...
D/BluetoothTethering(  903): supplyMessenger
D/BluetoothTethering(  903): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  903): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  903): got CMD_CHANNEL_HALF_CONNECTED
D/PanService( 3933): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BtGatt.DebugUtils( 3933): handleDebugAction() action=null
D/BtGatt.GattService( 3933): Received start request. Starting profile...
,D/BtGatt.GattService( 3933): start()
D/HeadsetPhoneState( 3933): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/BluetoothPbapService( 3933): Pbap Service onCreate
,V/BluetoothPbapService( 3933): Starting PBAP service
I/ActivityManager(  903): Recipient 3065
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 11
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 11
E/BluetoothMasService( 3933): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3933): Add permission for SmsProvider.
V/BluetoothMasService( 3933): Starting MAS instances
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 11
I/MailMessageReceiver( 3933): reg:com.android.bluetooth.btservice.AdapterApp@41e0e350 with com.htc.util.mail.MailMessageReceiver@41e4fc10
I/MailManager( 3933): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41e4fc10
V/EmailUtils( 3933): Manager Instance is not NULL
,I/ActivityManager(  903): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3978 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,I/chromium( 3872): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Tethering(  903): interfaceAdded wlan0
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/Tethering(  903): wlan0 is not a tetherable iface, ignoring
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/Tethering(  903): interfaceAdded p2p0
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/Tethering(  903): p2p0 is not a tetherable iface, ignoring
D/Tethering(  903): interfaceLinkStateChanged p2p0, false
,D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/PMS     (  903): releaseWL(427b3460): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/libc    (  903): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 3933): ============NULL aList========
,V/EmailUtils( 3933): <-getEmailAccountIdList
,V/BluetoothMasService( 3933): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 11
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3933): Manager Instance is not NULL
D/EmailUtils( 3933): ============NULL aList========
,V/EmailUtils( 3933): <-getEmailAccountIdList
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
V/BluetoothSapService( 3933): Sap Service onCreate
V/BluetoothSapService( 3933): initBinder
V/BluetoothSapService( 3933): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41e552a0
,V/BluetoothSapReceiver( 3933): BluetoothSapReceiver init
,D/BluetoothSapService( 3933): setSapService()
V/BluetoothSapService( 3933): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3933): state: 12
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 11
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.pan.PanService
,D/PanService( 3933): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/Process (  903): killProcessQuiet, pid=3391
,D/BluetoothTethering(  903): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  903): Killing 3391:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 11
,I/qcom-bluetooth( 3997): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  903): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3998 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4015): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4016): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3998): Received state change = 11
,I/qcom-bluetooth( 4018): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4019): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4020): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4022): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  903): New client listening to asynchronous messages
,I/wpa_supplicant( 4023): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4023): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4023): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4023): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 4023): Get randomness: len=20 entropy=1
D/Process (  903): killProcessQuiet, pid=3373
D/wpa_supplicant( 4023): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4023): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4023): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4023): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4023): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4023): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4023): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4023): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4023): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4023): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4023): update_config=1
D/wpa_supplicant( 4023): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4023): device_name='Android_63cc'
D/wpa_supplicant( 4023): manufacturer='HTC'
D/wpa_supplicant( 4023): model_name='HTC_PHONE'
D/wpa_supplicant( 4023): model_number='1234'
D/wpa_supplicant( 4023): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4023): p2p_oper_reg_class=126
D/wpa_supplicant( 4023): p2p_oper_channel=36
D/wpa_supplicant( 4023): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4023): persistent_reconnect=1
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4023): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4023): nl80211: RFKILL status not available
I/ActivityManager(  903): Killing 3373:com.htc.mediamanager/u0a32 (adj 15): empty #17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4023): nl80211: Using driver-based roaming
D/wpa_supplicant( 4023): nl80211: TDLS supported
D/wpa_supplicant( 4023): nl80211: TDLS external setup
D/wpa_supplicant( 4023): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4023): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4023): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4023): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4023): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4023): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4023): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb776f758
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb776f758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4023): htc_wext_command_init +
E/wpa_supplicant( 4023): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4023): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4023): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 95
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4023): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4023): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4023): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4023): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4023): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4023): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  903): interfaceLinkStateChanged p2p0, false
D/Tethering(  903): interfaceStatusChanged p2p0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged p2p0, false
D/Tethering(  903): interfaceStatusChanged p2p0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
I/ActivityManager(  903): Recipient 3373
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3391
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  903): Client com.google.android.music (pid 3391): Died!
,D/WifiMonitor(  903): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  903): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4027 uid=10048 gids={50048}
,I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/HtcWiFiWidget_WiFiWidgetProvider( 4027): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4027): updateWidget(context) for widget: 
,D/Process (  903): killProcessQuiet, pid=3500
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  903): Killing 3500:com.google.android.gm/u0a107 (adj 15): empty #17
I/wpa_supplicant( 4023): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4023):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4023):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4023):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): nl80211: Flush PMKIDs
E/wpa_supplicant( 4023): send_and_recv error -22 - cmd 54
I/wpa_supplicant( 4023): State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 4039): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
I/ActivityManager(  903): Recipient 3500
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/qcom-bluetooth( 4040): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3933): btu_task pending for preload complete event
,D/wpa_supplicant( 4023): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4023): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4023): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4023): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
,D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4023): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4023): Using existing control interface directory.
D/wpa_supplicant( 4023): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4023): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4023): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0',
D/wpa_supplicant( 4023): P2P: Own listen channel: 6
D/wpa_supplicant( 4023): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4023): P2P: Add operating class 81,
,I/wpa_supplicant( 4023): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4023): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4023): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf',
D/wpa_supplicant( 4023): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4023): ctrl_interface='/data/misc/wifi/sockets',
D/wpa_supplicant( 4023): disable_scan_offload=1
D/wpa_supplicant( 4023): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4023): update_config=1
D/wpa_supplicant( 4023): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4023): device_name='a51ul_htc_europe'
,D/wpa_supplicant( 4023): manufacturer='HTC'
D/wpa_supplicant( 4023): model_name='HTC Desire 820'
D/wpa_supplicant( 4023): model_number='HTC Desire 820'
,D/wpa_supplicant( 4023): config_methods='physical_display virtual_push_button',
D/wpa_supplicant( 4023): persistent_reconnect=1
D/wpa_supplicant( 4023): p2p_disabled=1
,D/wpa_supplicant( 4023): hs20=1
D/wpa_supplicant( 4023): interworking=1
D/wpa_supplicant( 4023): Line: 18 - start of a new network block
D/wpa_supplicant( 4023): key_mgmt: 0x2,
D/wpa_supplicant( 4023): priority=1 (0x1)
,D/wpa_supplicant( 4023): signinfail=0 (0x0),
,D/wpa_supplicant( 4023): Priority group 1
D/wpa_supplicant( 4023):    id=0 ssid='NG700'
I/wpa_supplicant( 4023): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4023): nl80211: RFKILL status not available
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4023): nl80211: Using driver-based roaming
D/wpa_supplicant( 4023): nl80211: TDLS supported
D/wpa_supplicant( 4023): nl80211: TDLS external setup
D/wpa_supplicant( 4023): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4023): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4023): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4023): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4023): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4023): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4023): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb777f718
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4023): htc_wext_command_init +
I/wpa_supplicant( 4023): htc_wext_command_init -
I/wpa_supplicant( 4023): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4023): Don't set 00 to countryID.conf
D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4023): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4023): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4023): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4023): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4023): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4023): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4023): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4023): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 4023): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4023):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4023):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 4023):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0,
E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12,
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0,
E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12,
,D/wpa_supplicant( 4023): nl80211: Flush PMKIDs,
,E/wpa_supplicant( 4023): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4023): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4023): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4023): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4023): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4023): Using existing control interface directory.
,I/wpa_supplicant( 4023): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4023): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4023): Auto country group 1: ch36
I/wpa_supplicant( 4023): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4023): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4023): Get randomness: len=20 entropy=0
V/RegulatoryObserver(  903): uevent:
V/RegulatoryObserver(  903): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4423, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
D/wpa_supplicant( 4023): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4023): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_903-2
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4023): nl80211: Event message available
D/wpa_supplicant( 4023): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4023): nl80211: Regulatory domain change
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4023): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4023): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4023): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4023): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4023): P2P: Add operating class 81
D/wpa_supplicant( 4023): P2P: Add operating class 115
D/wpa_supplicant( 4023): P2P: Add operating class 116
D/wpa_supplicant( 4023): P2P: Add operating class 117
D/wpa_supplicant( 4023): P2P: Update channel list
D/wpa_supplicant( 4023): p2p0: Updating hw mode
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4023): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4023): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4023): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4023): nl80211: Added 802.11b mode based on 802.11g information
V/RegulatoryObserver(  903): Regulatory Country Code:DE
V/RegulatoryObserver(  903): Start wifi-crda service to run crda.
V/RegulatoryObserver(  903): Country Code is DE
V/RegulatoryObserver(  903): Send broadcast country code message.
I/RegulatoryObserver(  903): Broadcast intent for crda country code: DE
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiNative-wlan0(  903): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): set wifi ON
D/WifiNative-wlan0(  903):    returned true
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WifiNative-wlan0(  903): doString: DRIVER MACADDR
D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiConfigStore(  903): Loading config and enabling all networks
,D/WifiNative-wlan0(  903): doString: LIST_NETWORKS
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): list_network_info: ret=0x1, pos=0xb7782117 buf=0xb77820e8
,I/wpa_supplicant( 4023): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4023): 0	NG700	any	
D/WifiNative-wlan0(  903):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  903): 0	NG700	any	
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 ssid
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 bssid
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
,D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'bssid',
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 priority
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/HtcWiFiWidget_WiFiWidgetProvider( 4027): onWiFiStateChanged() for widget: 
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/HtcWiFiWidget_WiFiWidgetProvider( 4027): updateWidget(context) for widget: 
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
,D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
,D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_psk
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 psk
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4023): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 proto
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  903): Failed to look-up a string: W
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 pairwise
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  903): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 group
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  903): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
,D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 limited
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 eap
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 phase2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 identity
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 password
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
I/wpa_supplicant( 4023): wpa_supplicant_scan enter
I/wpa_supplicant( 4023): State: DISCONNECTED -> SCANNING
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4023): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4023): wpa_supplicant_trigger_scan +
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4023): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'subject_match'
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 4023): nl80211: Event message available
D/wpa_supplicant( 4023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 engine
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 key_id
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
,D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 private_key
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  903): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  903): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4023): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4023): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET manufacturer HTC
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4023): manufacturer='HTC'
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'model_name'='HTC Desire 820'
,D/wpa_supplicant( 4023): model_name='HTC Desire 820'
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4023): model_number='HTC Desire 820'
D/WifiNative-wlan0(  903):    returned true
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
,D/wpa_supplicant( 4023): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET auto_interworking 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4023): auto_interworking=0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SCAN_INTERVAL 15
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: STATUS
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4023): SET_SCREEN_ON:On
I/wpa_supplicant( 4023): htc_wext_set_keepalive +
I/wpa_supplicant( 4023): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4023): getPrivFuncNum +	
I/wpa_supplicant( 4023): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET ps 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiP2pService(  903): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  903): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  903): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETBAND 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): SETBAND: 0
D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4023): P2P: Add operating class 81
D/wpa_supplicant( 4023): P2P: Add operating class 115
D/wpa_supplicant( 4023): P2P: Add operating class 116
D/wpa_supplicant( 4023): P2P: Add operating class 117
D/wpa_supplicant( 4023): P2P: Update channel list
I/wpa_supplicant( 4023): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
,I/wpa_supplicant( 4023): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4023): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4023): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4023): p2p_oper_reg_class=126
D/wpa_supplicant( 4023): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4023): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 4023): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4023): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4023): p2p_oper_channel=36
E/wpa_supplicant( 4023): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4023): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4023): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4023): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4023): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: BSS_FLUSH 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/libc    (  903): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  903):    returned false
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  903): doBoolean: SET pno 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4023): wpa_supplicant_scan enter
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): Wifi band: 0, ScanBroadCastCounter: 0
I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiMonitor(  903): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  903): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4023): persistent_reconnect=1
I/wpa_supplicant( 4023): Recv Cmd 2: SET persistent_reconnect=1,
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET device_name Android_63cc
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 4023): device_name='Android_63cc'
I/wpa_supplicant( 4023): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 4023): p2p_ssid_postfix='-Android_63cc'
,D/wpa_supplicant( 4023): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 4023): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4023): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4023): config_methods='virtual_push_button physical_display keypad'
,I/wpa_supplicant( 4023): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: P2P_SET conc_pref sta
D/WifiP2pService(  903): P2pEnablingState
D/WifiP2pService(  903): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2p socket connection successful
D/WifiP2pService(  903): P2pEnabledState
D/WifiDisplayController(  903): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  903): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiP2pService(  903): sending p2p connection changed broadcast
D/WifiDisplayController(  903): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  903): mWfdEnabled :false, networkInfo.isConnected() :false
W/WifiHW  (  903): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4023): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4023): Single channel concurrency preference: sta
,I/wpa_supplicant( 4023): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doString: STATUS
W/WifiHW  (  903): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  903): doBoolean: P2P_FLUSH
W/WifiHW  (  903): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4023): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4023): P2P: Stopping find
D/wpa_supplicant( 4023): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4023): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4023): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  903):    returned true
,D/WifiNative-p2p0(  903): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  903): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4023): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4023): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doString: LIST_NETWORKS
W/WifiHW  (  903): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4023): list_network_info: ret=0x22, pos=0xb778210a buf=0xb77820e8
I/wpa_supplicant( 4023): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4023): Recv Cmd 2: LIST_NETWORKS
,D/WifiNative-p2p0(  903):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  903): doBoolean: AP_SCAN 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "AP_SCAN 1"
,D/WifiNative-p2p0(  903):    returned false
D/WifiNative-p2p0(  903): doBoolean: SET wifi_display 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4023): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4023): WFD: Update WFD IE
I/wpa_supplicant( 4023): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4023): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  903): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4023): WFD: Set subelement 0
D/wpa_supplicant( 4023): WFD: Update WFD IE
I/wpa_supplicant( 4023): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4023): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  903):    returned true
D/WifiP2pService(  903): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  903): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  903):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  903):  primary type: 10-0050F204-5
D/WifiDisplayController(  903):  secondary type: null
D/WifiDisplayController(  903):  wps: 0
D/WifiDisplayController(  903):  grpcapab: 0
D/WifiDisplayController(  903):  devcapab: 0
D/WifiDisplayController(  903):  status: 3
D/WifiDisplayController(  903):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  903):  WFD CtrlPort: 0
D/WifiDisplayController(  903):  WFD MaxThroughput: 0
D/WifiP2pService(  903): sending p2p persistent groups changed broadcast
D/WifiP2pService(  903): InactiveState
D/WifiP2pService(  903): InactiveState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  903):  WFD CtrlPort: 7236
D/WifiP2pService(  903):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-12ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  903):  WFD CtrlPort: 7236
D/WifiP2pService(  903):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  903): Successfully set WFD info.
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  903): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  903):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  903):  primary type: 10-0050F204-5
D/WifiDisplayController(  903):  secondary type: null
D/WifiDisplayController(  903):  wps: 0
D/WifiDisplayController(  903):  grpcapab: 0
D/WifiDisplayController(  903):  devcapab: 0
D/WifiDisplayController(  903):  status: 3
D/WifiDisplayController(  903):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  903):  WFD CtrlPort: 7236
D/WifiDisplayController(  903):  WFD MaxThroughput: 50
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,V/AudioService(  903): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  903):     Client/Owner: Client
V/AudioService(  903):     GroupId: 
V/AudioService(  903):     Passphrase: 
V/AudioService(  903):     SessionId: 0
V/AudioService(  903):     IP Address: }
D/HtcEffectManagerBase(  903): onEventChanged id=5 status=false
D/HtcEffectManager(  903): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  903): convertEffect before=902
D/HtcEffectManager(  903): convertEffect after=902
,D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
,D/Tethering(  903): interfaceLinkStateChanged p2p0, false
D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,I/SensorManager(  903): mEventCount = 1050
,I/bt-btu  ( 3933): btu_task received preload complete event
,D/bt-btm  ( 3933): btm_acl_device_down
D/bt-btm  ( 3933): btm_acl_reset_paging
,D/bt-btm  ( 3933): btm_acl_set_discing
,I/bt-btm  ( 3933): btm_reset_complete
,I/bt-btm  ( 3933): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3933): Start reading local supported commands
,D/bt-btm  ( 3933): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3933): BTM reads next extended features page (1)
,D/bt-btm  ( 3933): BTM reads next extended features page (2)
,D/bt-btm  ( 3933): BTM reached last extended features page (2)
,D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3933): btm_read_ble_wl_size 
D/bt-btm  ( 3933): btm_read_white_list_size_complete 
,D/bt-btm  ( 3933): btm_get_ble_buffer_size 
D/bt-btm  ( 3933): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3933): btm_read_ble_local_supported_features 
D/bt-btm  ( 3933): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3933): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3933): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3933): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3933): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3933): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3933): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3933): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3933): BTM_SetInquiryMode
I/bt-btm  ( 3933): BTM_SetPageScanType
I/bt-btm  ( 3933): BTM_SetInquiryScanType
D/bt-btm  ( 3933): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3933): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3933): BTM_BleLoadLocalKeys
D/bt-btm  ( 3933): BTM_BleLoadLocalKeys
I/bt-btm  ( 3933): BTM_Sec: application registered
E/bt-btm  ( 3933): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fa6941 
I/bt-btm  ( 3933): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3933): SMP_Register state=0
E/bt-btm  ( 3933): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fa6941 
I/bt-btm  ( 3933): BTM_Sec: application registered
D/bt-btm  ( 3933): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3933): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3933): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3933): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3933): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3933): BTM_RegBusyLevelNotif
I/bt-att  ( 3933): GATT_Register
D/bt-att  ( 3933): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3933): allocated gatt_if=3
I/bt-att  ( 3933): GATT_StartIf gatt_if=3
D/bt-att  ( 3933): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3933): gatt_find_the_connected_bda found=0 found_idx=7
,E/bt-btif ( 3933): Calling BTA_HhEnable
,E/bt-btif ( 3933): btif_storage_get_adapter_property service_mask:0x140040
,I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3933): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3933): BTM_AllocateSCN
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3933): BTM_AllocateSCN
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3933): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3933): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-avp  ( 3933): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3933): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up, to 21 chars saved)
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3933): GATT_Register
D/bt-att  ( 3933): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3933): allocated gatt_if=4
I/bt-att  ( 3933): GATT_StartIf gatt_if=4
D/bt-att  ( 3933): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3933): gatt_find_the_connected_bda found=0 found_idx=7
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3933): Address is:80:01:84:8A:B3:68
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:1 len:14
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3933): Scan Mode:20
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3933): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:8 len:30
D/BluetoothAdapter( 3933): getBluetoothService(): entry
D/BluetoothAdapter( 3933): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3933): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41e5ea28
D/BluetoothDevice( 3933): getService : Register callback
D/BluetoothAdapterProperties( 3933): Adding bonded device:B4:CE:F6:AB:A4:6A
D/BluetoothAdapterProperties( 3933): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 3933): Adding bonded device:34:FC:EF:9D:93:0B
D/BluetoothAdapterProperties( 3933): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3933): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): BTA_JvEnable
I/bt-btm  ( 3933): BTM_ReadConnectability
I/bt-btm  ( 3933): BTM_ReadDiscoverability
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3933): br_edr_supported=0x2
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3933): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3933): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3933): br_edr_supported=0x0
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
,I/bt-btm  ( 3933): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3933): bta_pan_co_init
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3933): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3933):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3933):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3933): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3933):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3933):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,E/bt_mct  ( 3933): hci lib postload completed
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3933): ScanMode =  20
D/BluetoothAdapterProperties( 3933): State =  11
I/bt-btif ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): BTM_SetDiscoverability
,I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/BluetoothAdapterProperties( 3933): Setting state to 12
D/bt-btm  ( 3933): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3933): br_edr_supported=0x0
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3933): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3933): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3933): Scan Mode:21
I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3933): Discoverable Timeout:120
I/BluetoothAdapterState( 3933): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3933): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  903): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  903): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothHeadset( 1216): onBluetoothStateChange: up=true
D/wpa_supplicant( 4023): EAPOL: disable timer tick
I/BluetoothAdapterState( 3933): Entering On State
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/BluetoothAdapterService(1105298040)( 3933): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3933): getBondedDevices: length=5
D/BluetoothHeadset( 1107): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1216): Proxy object connected
D/BluetoothAdapterService(1105298040)( 3933): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3933): getBondedDevices: length=5
,D/BluetoothHeadset( 1107): Proxy object connected
,I/QuickSettingMiniLite( 1107): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@421106c0
,D/BluetoothPan(  903): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1216): onBluetoothStateChange: up=true
,D/BluetoothPan(  903): BluetoothPAN Proxy object connected
D/BluetoothHeadset( 1216): Proxy object connected
,D/BluetoothPhoneService( 1216): BluetoothHeadset onServiceConnected
,D/BluetoothHeadset(  903): onBluetoothStateChange: up=true
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothAdapter( 1216): 1106499424: getState(). Returning 12
,D/BluetoothA2dp(  903): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  903): Proxy object connected
,D/BluetoothManagerService(  903): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothAdapter(  903): 1114786784: getState(). Returning 12
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,V/BluetoothPbapReceiver( 3933): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3933): ***********state = 12
,D/BluetoothA2dp(  903): Proxy object connected
D/BluetoothAdapter(  903): 1114786784: getState(). Returning 12
,D/HtcBtWidget_BTWidgetProvider( 3959): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3959): updateWidget(context) for widget: ,
D/PMS     (  903): acquireWL(4288b0c0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3325 1000 null
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  903): releaseWL(4288b0c0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  903): acquireWL(44313080): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3325 1000 null
D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 12
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  903): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42723478:true
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothSapReceiver( 3933): SapReceiver onReceive 
V/BluetoothSapReceiver( 3933): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3933):  Bluetooth Adapter state = 12
I/LocationAgent( 3325): new LocationAgent instance!!
V/BluetoothSapReceiver( 3933): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 12
D/HtcTagManager( 3325): HtcTagManager construction complete
,D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
,D/BluetoothInputDevice( 3325): BluetoothInputDevice()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
,D/BluetoothInputDevice( 3325): BluetoothInputDevice(): Binding service...
,D/BluetoothManagerService(  903): Registered receivers: 7
,D/BluetoothPan( 3325): BluetoothPan()
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/wpa_supplicant( 4023): nl80211: Event message available
D/wpa_supplicant( 4023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4023): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4023): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 4023): nl80211: Survey data missing
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4023): Sorted scan results
I/wpa_supplicant( 4023): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 4023): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4023): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4023): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 4023): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
I/wpa_supplicant( 4023): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-89
I/wpa_supplicant( 4023): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 4023): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 4023): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4023): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4023): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4023): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4023): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4023): Add randomness: count=7 entropy=5
D/wpa_supplicant( 4023): Add randomness: count=8 entropy=6
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/BluetoothManagerService(  903): Registered receivers: 8
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4023): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4023): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4023): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4023): wpa_supplicant_pick_network+
I/wpa_supplicant( 4023): Selecting BSS from priority group 1
I/wpa_supplicant( 4023): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4023): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=,20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4023): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4023): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4023): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4023):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4023):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 4023): Start print parameters
I/wpa_supplicant( 4023): wpa_s->wpa_state is 3
I/wpa_supplicant( 4023): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4023): isConcurrentMode() is 0
I/wpa_supplicant( 4023): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4023): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4023): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4023): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4023): wpa_s->reassociate is 0
I/wpa_supplicant( 4023): wpa_s->is_screen_on 1
I/wpa_supplicant( 4023): wpa_s->ifname wlan0
I/wpa_supplicant( 4023): End print parameters
I/wpa_supplicant( 4023): selected network = 2
D/wpa_supplicant( 4023): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb77804e8  current_ssid=0x0
D/wpa_supplicant( 4023): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4023): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4023): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4023): check if in concurrent case
I/wpa_supplicant( 4023): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
D/BluetoothPan( 3325): BluetoothPan(): Binding service...
D/wpa_supplicant( 4023): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4023): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4023): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4023): RSN: PMKSA cache search - network_ctx=0xb77804e8 try_opportunistic=0
D/wpa_supplicant( 4023): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4023): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4023): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4023): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4023): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4023): nl80211: Unsubscribe mgmt frames handle 0xb777f718 (mode change)
D/wpa_supplicant( 4023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb777f718
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb777f718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4023):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4023):   * freq=2412
D/wpa_supplicant( 4023):   * Auth Type 0
D/wpa_supplicant( 4023):   * WPA Versions 0x2
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4023): nl80211: Connect request send successfully
D/wpa_supplicant( 4023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/BluetoothMap( 3325): Create BluetoothMap proxy object
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/BluetoothManagerService(  903): Registered receivers: 9
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 12
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3933): Manager Instance is not NULL
E/BluetoothMap( 3325): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothSap( 3325): BluetoothSap() call bindService
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 10
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 4023): reply (926) for get BSS: id=0
I/wpa_supplicant( 4023): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4023): freq=5220
I/wpa_supplicant( 4023): level=-47
I/wpa_supplicant( 4023): tsf=0000000106401456
I/wpa_supplicant( 4023): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4023): ssid=NG7005g
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=1
I/wpa_supplicant( 4023): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): freq=2412
I/wpa_supplicant( 4023): level=-50
I/wpa_supplicant( 4023): tsf=0000000106401467
I/wpa_supplicant( 4023): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4023): ssid=01ABC
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=2
I/wpa_supplicant( 4023): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): freq=2412
I/wpa_supplicant( 4023): level=-50
I/wpa_supplicant( 4023): tsf=0000000106401471
I/wpa_supplicant( 4023): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4023): ssid=NG700
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=3
I/wpa_supplicant( 4023): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4023): freq=2427
I/wpa_supplicant( 4023): level=-80
I/wpa_supplicant( 4023): tsf=0000000106401475
I/wpa_supplicant( 4023): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4023): ssid=Gonzos
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=4
I/wpa_supplicant( 4023): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 4023): freq=2437
I/wpa_supplicant( 4023): level=-87
I/wpa_supplicant( 4023): tsf=0000000106401482
I/wpa_supplicant( 4023): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4023): ssid=UPC4688432
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=5
I/wpa_supplicant( 4023): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 4023): freq=2462
I/wpa_supplicant( 4023): level=-89
I/wpa_supplicant( 4023): tsf=0000000106401479
I/wpa_supplicant( 4023): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 4023): ssid=UPC Wi-Free
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=6
I/wpa_supplicant( 4023): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 4023): freq=2462
I/wpa_supplicant( 4023): level=-90
I/wpa_supplicant( 4023): tsf=0000000106401486
I/wpa_supplicant( 4023): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4023): ssid=UPC5999698
I/wpa_supplicant( 4023): ####
D/BluetoothAdapter( 1107): 1108004192: getState(). Returning 12
D/BluetoothPbap( 3325): BluetoothPbap()
D/BluetoothManagerService(  903): registerStateChangeCallback+
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 106401456, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 106401467, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 106401471, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 106401475, distance: ?(cm), distanceSd: ?(cm)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 11
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/BluetoothAdapter( 1107): 1108004192: getState(). Returning 12
D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
D/BluetoothPbap( 3325): BluetoothPbap(): Binding service...
D/WifiStateMachine(  903): == begin of scan result ==
I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/WifiStateMachine(  903): == (7) end of scan result ==
D/PhoneStatusBar( 1107): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/EmailUtils( 3933): ============NULL aList========
V/EmailUtils( 3933): <-getEmailAccountIdList
V/BluetoothSapService( 3933): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3933): state: 12
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 12
W/ContextImpl( 3933): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 106401482, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 106401479, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 106401486, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 7 to mScanResults
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
V/BluetoothSapService( 3933): Starting SAP server process
D/BluetoothA2dp( 3325): BluetoothA2dp()
D/BluetoothManagerService(  903): registerStateChangeCallback+
V/BluetoothPbapService( 3933): Handler(): got msg=1
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
D/BluetoothA2dp( 3325): BluetoothA2dp(): Binding service...
D/BluetoothManagerService(  903): Registered receivers: 12
V/BluetoothPbapService( 3933): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3933): Pbap Service initSocket
D/BluetoothHeadset( 3325): BluetoothHeadset()
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 13
D/BluetoothAdapter( 3933): getBluetoothService(): entry
,W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
E/BluetoothServiceJni( 3933): SOCK FLAG = 1 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3933):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3933): Succeed to create listening socket 
V/BluetoothPbapService( 3933): Accepting socket connection...
D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
D/BluetoothHeadset( 3325): BluetoothHeadset(): Binding service...
D/HtcTagManager( 3325): startProxy
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
W/ContextImpl( 3325): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
D/LocalBluetoothProfileManager( 3325): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 1107): 1108004192: getState(). Returning 12
I/QuickSettingMiniLite( 1107): updateLiteState:no connect device!
V/BluetoothMasService( 3933): handleMessage: mIsEmailEnabledtrue
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
V/BtMns   ( 3933): BluetoothMns: isEmailEnabled: true
D/DockEventReceiver( 3325): finishStartingService: stopping service
D/BluetoothPan( 3325): BluetoothPAN Proxy object connected
D/PanProfile( 3325): Bluetooth service connected
D/BluetoothMasService( 3933): Map_prev 1
D/BluetoothA2dp( 3325): Proxy object connected
D/A2dpProfile( 3325): Bluetooth service connected
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
D/BluetoothAdapter( 3933): getBluetoothService(): entry
D/BluetoothHeadset( 3325): Proxy object connected
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
D/HeadsetProfile( 3325): Bluetooth service connected
D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3933):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3998): onCreate: going to find gatt base service first.
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3933): getBluetoothService(): entry
D/BluetoothInputDevice( 3325): Proxy object connected
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
D/HidProfile( 3325): Bluetooth service connected
D/BluetoothAdapter( 3325): 1106872288: getState(). Returning 12
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3933):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
V/TAG     ( 3933): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3933): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41e569e0
D/SapServerProfile( 3325): Bluetooth service connected
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43daea40:true
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
,D/PMS     (  903): releaseWL(44313080): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/[HTC_BLE][Constants]( 3998):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3998):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3998):  + discoverServicesOnBonded = false
V/BluetoothPbapService( 3933): Pbap Service onBind
D/BluetoothPbap( 3325): Proxy object connected
D/PbapServerProfile( 3325): Bluetooth service connected
D/BluetoothSapService( 3933): Sap_prev 1
V/BluetoothSapService( 3933): SAP Service startRfcommListenerThread
V/BluetoothSapService( 3933): Sap Service initRfcommSocket
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3933):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3933): Succeed to create listening socket 
V/BluetoothSapService( 3933): Accepting socket connection...
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/BluetoothFtpService( 3933): Ftp Service onCreate
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 12
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3998):  + Google LE service found. Using BaseLeProfilesGoogle.
D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 12
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3998): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41e1e1c8
E/BluetoothServiceJni( 3933): SOCK FLAG = 0 ***********************
D/[HTC_BLE][Constants]( 3998): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3998): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3998): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3998): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3998): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
D/[HTC_BLE][Constants]( 3998): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3933):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3933): Accept thread started.
D/BluetoothFtpService( 3933): Ftp_prev 1
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3998): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 1 ****************,*******
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3933):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3998): Received state change = 12
V/BluetoothFtpService:RfcommSocketAcceptThread( 3933): Run Accept thread
D/BluetoothAdapter( 3933): 1105316216: getState(). Returning 12
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3933): Manager Instance is not NULL
D/HtcTagManager( 3325): onServiceConnected
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3998): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3998): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41e1e1c8
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3998): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e1e1c8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3998): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e1e1c8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41e291b0
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3998): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e1e1c8
D/HtcTagProfile( 3325): setup proxy
D/HtcPxpProfile( 3325): setup proxy
D/HtcFmpProfile( 3325): setup proxy
D/EmailUtils( 3933): ============NULL aList========
V/EmailUtils( 3933): <-getEmailAccountIdList
D/BluetoothMasService( 3933): Map_prev 1
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4023): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4023): nl80211: Event message available
D/wpa_supplicant( 4023): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4023): nl80211: Connect event
D/wpa_supplicant( 4023): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4023): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4023): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4023): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4023): Add randomness: count=9 entropy=7
I/wpa_supplicant( 4023): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4023): TDLS: Remove peers on association
D/wpa_supplicant( 4023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - portValid=0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4023): htc_wext_set_keepalive +
I/wpa_supplicant( 4023): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4023): getPrivFuncNum +	
I/wpa_supplicant( 4023): getPrivFuncNum -, cmd = 0x8bf6,
I/wpa_supplicant( 4023): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4023): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 4023): Get randomness: len=32 entropy=8
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48,
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/WifiStateMachine(  903): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Associated
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  903): java.lang.Throwable: stack dump
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/WifiStateMachine(  903): This record is existed, only update it...
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
I/wpa_supplicant( 4023): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb777f9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4023):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 10
,D/wpa_supplicant( 4023): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4023): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b13340:true
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef2b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4023):    broadcast key
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4023): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/WifiApDatabaseHandler(  903): updateConnectedAP...
I/wpa_supplicant( 4023): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4023): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4023): set send_ind_to_ndc = 0
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 4023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4023): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4023): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4023): EAPOL authentication completed successfully
I/wpa_supplicant( 4023): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
I/LocationAgent( 3836): new LocationAgent instance!!
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/RingtoneManager( 3998): getExternalStorageState=mounted
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/HtcTagManager( 3836): HtcTagManager construction complete
D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[1]: Daisy
D/BluetoothInputDevice( 3836): BluetoothInputDevice()
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[3]: Foxglove
D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 14
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[8]: Olive
D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
D/BluetoothInputDevice( 3836): BluetoothInputDevice(): Binding service...
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[12]: Tulip
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3998):  + mAlertUri: content://settings/system/alarm_alert
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3998): BleProfilesStateMachine is initialized...
D/BluetoothPan( 3836): BluetoothPan()
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3998): Enter IdleState
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3998): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3998): initScanModeInterface: true
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/System.err(  903): java.lang.Throwable: stack dump
,W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  903): Registered receivers: 15
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3998): loadDeviceConfiguration() init =true
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@442963f0:true
D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
D/BluetoothPan( 3836): BluetoothPan(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3998):  + mTag.getPrimaryDeviceList() = []
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
D/[HTC_BLE][Constants]( 3998):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3998):  + enableOnBonded = false
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/[HTC_BLE][Constants]( 3998):  + discoverServicesOnBonded = false
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothMap( 3836): Create BluetoothMap proxy object
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 16
,E/BluetoothMap( 3836): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothSap( 3836): BluetoothSap() call bindService
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1743/10178)
,D/WISPrService( 3325): >>>>>WISPrService start isConnected = false<<<<<
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3998): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41e291b0
,D/BluetoothPbap( 3836): BluetoothPbap()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/BluetoothPbap( 3836): BluetoothPbap(): Binding service...
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/WifiService(  903): New client listening to asynchronous messages
D/WISPrService( 3325): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  903): [StoppedState] Start DHCP
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/BluetoothA2dp( 3836): BluetoothA2dp()
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): WiFioffload: SignalStrength: =97
,D/BluetoothA2dp( 3836): BluetoothA2dp(): Binding service...
,D/WifiNative-wlan0(  903):    returned true
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED -1 -> 3
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/WifiStateMachine(  903): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  903): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): WiFioffload: update mobile network = Unknown
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/BluetoothHeadset( 3836): BluetoothHeadset()
D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): Power_Mode_Type mode = 1
I/wpa_supplicant( 4023): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  903):    returned null
D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/BluetoothHeadset( 3836): BluetoothHeadset(): Binding service...
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(438b2db8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a7f2d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a7f2d0 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/HtcTagManager( 3836): startProxy
,W/ContextImpl( 3836): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3836): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3836): setBluetoothStateOn
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,I/QuickSettingWifi( 1107): receive.wifiConnect:false wifiAPname:null elapse:1
,W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/HtcTagManager( 3836): startProxy
D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
D/BluetoothAdapterService(1105298040)( 3933): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3933): getBondedDevices: length=5
D/BluetoothAdapter( 3836): getBluetoothService(): entry
D/BluetoothAdapter( 3836): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3836): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41e58af0
D/BluetoothDevice( 3836): getService : Register callback
E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,E/BluetoothDevice( 3836): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/HtcTagManager( 3836): addHtcTagProfiles
,D/BluetoothManagerService(  903): Registered receivers: 17
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 18
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 19
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 20
D/BluetoothInputDevice( 3836): Proxy object connected
,D/HidProfile( 3836): Bluetooth service connected
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
D/BluetoothPan( 3836): BluetoothPAN Proxy object connected
,D/PanProfile( 3836): Bluetooth service connected
D/SapServerProfile( 3836): Bluetooth service connected
,D/BluetoothPbap( 3836): Proxy object connected
D/PbapServerProfile( 3836): Bluetooth service connected
D/BluetoothA2dp( 3836): Proxy object connected
D/A2dpProfile( 3836): Bluetooth service connected
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/BluetoothHeadset( 3836): Proxy object connected
D/HeadsetProfile( 3836): Bluetooth service connected
,D/BluetoothAdapter( 3836): 1105327096: getState(). Returning 12
,D/HtcTagManager( 3836): onServiceConnected
D/HtcTagProfile( 3836): setup proxy
D/HtcPxpProfile( 3836): setup proxy
,D/HtcFmpProfile( 3836): setup proxy
,D/wpa_supplicant( 4023): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4023): EAPOL: disable timer tick
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4023): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  903): releaseWL(438b2db8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): gateway: /192.168.1.1
,D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4023): WiFi gateway: 0x101a8c0,
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19696 delay=15s
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1743/10178)
,D/WifiWatchdogStateMachine(  903): WAN detection
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
,D/WISPrService( 3325): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/MDST    (  903): default: setTeardownRequested(true)
,D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@4272a7e0
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,I/QuickSettingWifi( 1107): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(4327ee00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(4327ee00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WIFI_ICON( 1107): WifiActivity: 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4116 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/CaptivePortalTracker(  903): NoActiveNetworkState
D/libc    (  903): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
D/PMS     (  903): acquireWL(42417da8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1391/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1743/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (3765/10100)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3413/10051)
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  364): [NET] +++++ res_nsend xid =e733 +++++,
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
V/Tethering(  903): bSetPropertyMultiRAB:false
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1,
I/Tethering(  903): Found interface wlan0
D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/ConnectivityHelper( 1247): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1762/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1247/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (3765/10100)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  903): BroadcastRSSIForIMS, newrssi =-49 , oldRssi= -200
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
,I/jxcore-log( 3872): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3872): 
,D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 136
D/libc    (  364): [NET]res_nsend:resplen=104
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(438b2e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42479400
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
I/PMS     (  903): Going to sleep due to screen timeout...
I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  903): setLight #0: color=#0
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42479400, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4235b200
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@42914170
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/MusicStore( 4116): Database version: 95
,W/ContextImpl( 4116): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ActivityManager(  903): screenshot for ActivityRecord{431c10c0 u0 com.test.thalitest/.MainActivity t2}, bitmap=android.graphics.Bitmap@426cfa10, time = 2064
,W/PMS     (  903): mWirelessDisplayManager is null
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
I/IntentController( 1107): receive(android.intent.action.TIME_SET,4,false)
D/DotMatrix( 1539): [EventService] EVENT_RESET_THEME_TIMESTAMP
I/FeedActionBar( 1247): updateLastUpdatedTime(in String) LAST UPDATED 12:10
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42b27090): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 903 1000 WorkSource{10096}
D/DotMatrix( 1539): [EventService] isTheSameDay:false,timestamp is early than today:true
,I/ActivityManager(  903): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4141 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  903): releaseWL(42b27090): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096},
,W/ContextImpl( 4116): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  903): acquireWL(43d7d898): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 903 1000 WorkSource{10096}
,D/PMS     (  903): acquireWL(44301460): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 903 1000 WorkSource{10160}
,D/PMS     (  903): releaseWL(438b2e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4116): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/GpsLocationProvider(  903): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  903): NTP server returned: 1449832341519 (Fri Dec 11 12:12:21 CET 2015) reference: 109663 certainty: 12 system time offset: -101
D/GpsLocationProvider(  903): reportAGpsStatus with type = 12090status = 30767ipAddr = [B@4346ed38ssid = nullpassword = null
D/GpsLocationProvider(  903): xtraDownloadRequest
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(43154718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(43154718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/GpsLocationProvider(  903): [handleMessage] INJECT_NTP_TIME_FINISHED
D/GpsLocationProvider(  903): [handleMessage] REPORT_AGPS_STATUS
D/GpsLocationProvider(  903): handleReportAgpsStatus with type = 12090status = 30767ipAddr = [B@4346ed38ssid = password = null
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 12090
D/GpsLocationProvider(  903): reportAGpsStatus agpsConnInfo is null for type 12090
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(443116f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(443116f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6c32 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4116): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4116): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4116, uid=10154, userID:0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4311d5c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(44301460): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(4311d5c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 390ms
D/PMS     (  903): nativeSetInteractive:false
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/PMS     (  903): nativeSetInteractive:false done
,D/PMS     (  903): nativeSetAutoSuspend:true
,D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
,I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1228): ScreenObserver: OFF
,D/NfcService( 1228): applyRouting - 0
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@438ec940)
W/ResourceType( 3872): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3872): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41e0e3c8 VFEDH.C. .F...... 0,0-720,1134 #64}
I/InputMethodManagerService(  903): Disable input method client, pid=3872
D/PMN     (  903): wakingUp
,D/NfcService( 1228): applyRouting -2
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/PMS     (  903): acquireWL(43dcb700): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  903): acquireWL(43e18200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/WindowManager(  903): No lock screen! windowToken=null
D/PMS     (  903): releaseWL(43dcb700): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(43e18200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  903): onScreenOn
,D/MediaRouterService(  903): Client com.google.android.music (pid 4116): Registered
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/MtpService( 2211): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
D/MtpService( 2211): [MTP][onReceive]-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1228): applyRouting - 0
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/NfcService( 1228): applyRouting -2
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/PMS     (  903): acquireWL(43d04190): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
,D/PMS     (  903): releaseWL(43d04190): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/MediaRouter( 4116): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19697 delay=15s
I/ClockThread( 1107): stop update clock
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): SET_SCREEN_ON:On
I/wpa_supplicant( 4023): htc_wext_set_keepalive +
I/wpa_supplicant( 4023): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4023): getPrivFuncNum +	
I/wpa_supplicant( 4023): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=11 [27][3][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): WiFioffload: SignalStrength: =97
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WifiNative-wlan0(  903):    returned true
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/NetworkMonitor( 4116): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (4116/10154)
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
,D/NetworkPolicy(  903): updateScreenOn: false
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4167 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42c641f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/DelayedSyncController( 4141): Delaying sync.
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(42c641f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MediaRouter( 4116): getSelectedRoute
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(43dede60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): acquireWL(43ae3df8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
D/PMS     (  903): releaseWL(43d7d898): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  903): releaseWL(43ae3df8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/NetworkMonitor( 4116): type=WIFI subType= reason=null isConnected=true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3998): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3998): onScreenOn: 1449832342111
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3998): onScreenOn: 1449832342111
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4116/10154)
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4235b200
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4235b200, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@42914170
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(4424cfb8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 903 1000 WorkSource{10096}
D/PMN     (  903): goingToSleep
D/PMS     (  903): releaseWL(43dede60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  903): acquireWL(43311528): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4116, uid=10154, userID:0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(434cee60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4141): Delaying sync.
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19697 mDataStallAlarmIntent=PendingIntent{42462798: PendingIntentRecord{4280f698 android broadcastIntent}}
D/PMS     (  903): releaseWL(434cee60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  903): releaseWL(43311528): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(44327310): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): SET_SCREEN_ON:Off
I/wpa_supplicant( 4023): htc_wext_set_keepalive +
I/wpa_supplicant( 4023): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4023): getPrivFuncNum +	
I/wpa_supplicant( 4023): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4023): get_ip_address source addr = c0a80176
I/wpa_supplicant( 4023): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 4023): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(441e5068): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
D/PMS     (  903): releaseWL(4424cfb8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/PMS     (  903): releaseWL(44327310): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/Process (  903): killProcessQuiet, pid=3735
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  903): Killing 3735:com.google.android.partnersetup/u0a31 (adj 15): empty #17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  903): updateScreenOn: false
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3735
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,E/BTIF_CORE( 3933): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3933): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3933): Wake lock released
,D/ACRA    ( 4167): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4167): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4167): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
D/ContactMessageStore( 1216): start background delete task...
,D/PMS     (  903): releaseWL(441e5068): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ContactMessageStore( 1216): size: 0 , 0
D/ContactMessageStore( 1216): Background delete complete
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3998): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3998): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3998): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3998): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3998): onScreenOff
D/PMS     (  903): acquireWL(442b9f08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
D/PMS     (  903): releaseWL(442b9f08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/SystemClassLoaderAdder( 4167): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4167): Preparing secondary program dexes.
,V/DexLibLoader( 4167): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4167): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4167): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4167): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4167): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4167): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4167): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4167): Dex already copied
D/OdexVerifier( 4167): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4167): Creating class loader
,V/DexLibLoader( 4167): Finished creating class loader
V/DexLibLoader( 4167): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4167): Dex already copied
D/OdexVerifier( 4167): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4167): Creating class loader
,V/DexLibLoader( 4167): Finished creating class loader
,V/DexLibLoader( 4167): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4167): Dex already copied
D/OdexVerifier( 4167): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4167): Creating class loader
,V/DexLibLoader( 4167): Finished creating class loader
V/DexLibLoader( 4167): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4167): Dex already copied
D/OdexVerifier( 4167): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4167): Creating class loader
,V/DexLibLoader( 4167): Finished creating class loader
,V/DexLibLoader( 4167): Verifying classes from secondary dexes.
,D/DexLibLoader( 4167): DexLibLoader.ensureDexLoaded took 113 ms
,W/dalvikvm( 4167): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4167): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4167): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4167): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4167): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4167): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4167): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8f82 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/23.59.123.86
,W/dalvikvm( 4167): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4167): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4167): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4167): Verify
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4167/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4167): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4167): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,W/ActivityManager(  903): Disable JIT of com.htc.bgp
,I/ActivityManager(  903): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4194 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  903): killProcessQuiet, pid=1371
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 1371:com.htc.sense.hsp/u0a53 (adj 15): empty #17
,I/CalendarProvider2( 4194): Created com.android.providers.calendar.CalendarAlarmManager@41e39a48(com.android.providers.calendar.HtcCalendarProvider@41e21dd0)
,D/CalendarProvider2( 4194): wait start:true
,D/CalendarProvider2( 4194): wait end:false
,W/fb4a(:<default>):UserScope( 4167): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4167): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/PMS     (  903): acquireWL(43e5f9e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,W/fb4a(:<default>):UserScope( 4167): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  903): acquireWL(42e38420): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
D/PMS     (  903): releaseWL(43e5f9e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,I/ActivityManager(  903): Recipient 1371
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1336): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
D/PMS     (  903): releaseWL(42e38420): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/libc    ( 1336): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1336): [NET] getaddrinfo-,err=8
D/libc    ( 1336): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1336): [NET] getaddrinfo-, 1
D/libc    ( 1336): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =973b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
D/PMS     (  903): acquireWL(4316e0a0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1336 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,E/dalvikvm( 4167): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4167): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4167): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4167): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4167): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4167): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4167): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4167): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4167): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4167): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4167): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4167): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,I/ActivityManager(  903): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4218 uid=10053 gids={50053, 1023, 3003, 5012}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 270
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1336): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 9.960MB for 84664-byte allocation
W/dalvikvm( 4167): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4167): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4167): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4167): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4167): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4167): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/ContactMessageStore( 1216): notify MmsSms
D/AccFlag ( 1216): sense_version=6.0
,D/AccFlag ( 1216): sku_id=99
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 9.988MB for 39954-byte allocation
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 10.060MB for 79892-byte allocation
,D/libc    ( 1336): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1336): [NET] getaddrinfo-,err=8
W/ActivityThread( 1336): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 10.087MB for 28144-byte allocation
D/PMS     (  903): acquireWL(428651d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
,D/PluginProvider( 4218): PluginProvider onCreate
D/PMS     (  903): releaseWL(428651d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PluginProvider( 4218): current plugin count: 19
,D/HtcAppUPService( 4218): HtcUPDataProvider onCreate()
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,D/AutoSetting( 4218): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4233 uid=10078 gids={50078, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=3765
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3765:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (4218/10053)
,D/GCM     ( 1336): Connected
D/PMS     (  903): acquireWL(431b8100): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1336 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
D/AutoSetting( 4218): service - onCreate()
I/dalvikvm-heap( 4167): Grow heap (frag case) to 10.274MB for 75760-byte allocation
,D/AutoSetting( 4218): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
,D/AutoSetting( 4218): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 4218): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  903): request 4284cf50 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  903): provider request: passive ProviderRequest[ON interval=0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4167/10026)
D/PMS     (  903): releaseWL(4316e0a0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4422d8a8 u0 ReceiverList{42a92e80 4167 com.facebook.katana/10026/u0 remote:438b5038}}
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1336/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (4218/10053)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e4e688 u0 ReceiverList{4274a738 4167 com.facebook.katana/10026/u0 remote:4313d7f8}}
D/AutoSetting( 4218): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4218): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
D/PMS     (  903): releaseWL(431b8100): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(443132b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1336 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4167/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4167/10026)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=25 [12][3][0]
,D/MobileConnectivityChangeReceiver( 4233): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4167/10026)
D/MobileConnectivityChangeReceiver( 4233): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4233): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4233): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4233/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
D/PMS     (  903): acquireWL(442ee758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1391 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4233/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4233/10078)
D/PMS     (  903): acquireWL(442e43e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4250 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1336/10028)
,D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1336): Message class mpf
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  903): acquireWL(442d3d88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
D/PMS     (  903): releaseWL(442e43e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
,D/PMS     (  903): releaseWL(442ee758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1336/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/GCoreFlp( 1391): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(44268f78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1391 10028 null
I/CheckinService( 1198): Preparing to send checkin request
,I/EventLogService( 1198): Accumulating logs since 1449830846763
D/PMS     (  903): releaseWL(44268f78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/ActivityManager(  903): Recipient 3765
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): releaseWL(443132b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(4422da50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10028 null
D/PMS     (  903): releaseWL(4422da50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4250): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4250): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4250): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4167): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/ContextImpl( 4250): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4250): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4167): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4167): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/EventLogAggregator( 1198): Unknown tag: install_package_attempt
W/EventLogAggregator( 1198): Unknown tag: snet
W/EventLogAggregator( 1198): Unknown tag: snet_gcore
,I/GoogleHttpClient( 1198): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1198): Using GMS GoogleHttpClient
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1198/10028)
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1198/10028)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4250/10151)
,V/WebViewChromiumFactoryProvider( 4250): Binding Chromium to main looper Looper (main, tid 1) {41e02fe0}
,I/LibraryLoader( 4250): Expected native library version number "",actual native library version number ""
,I/chromium( 4250): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4250): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4250): BLUETOOTH permission is missing!
D/PMS     (  903): acquireWL(434a3c80): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): acquireWL(43148388): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): releaseWL(43148388): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4250): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4250): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4250): Local Branch: 
I/Adreno-EGL( 4250): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4250): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4250):                  aa63bbd948f41d15fc72f585e
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,I/NSApplication( 4250): Starting up...
W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4250/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4250/10151)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,W/CheckinRequestBuilder( 1198): awaiting user notification for token
,D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3655/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3655/10160)
I/RemoteViews( 1107): com.google.android.gms (false,0)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{420c06c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/Process (  903): killProcessQuiet, pid=3785
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/RemoteViews.Performance( 1107): com.google.android.gms 0 12 3 12
I/ActivityManager(  903): Killing 3785:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1743/10178)
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3785
,D/AlertReceiver( 3822): beginStartingService
D/PMS     (  903): acquireWL(42711f40): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3822 10013 null
,D/PMS     (  903): acquireWL(437be490): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,D/AlertService( 3822): start to updateAlertNotification!
D/PMS     (  903): releaseWL(437be490): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4297 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/AlertService( 3822): No fired or scheduled alerts
D/HtcAlertUtils( 3822): -- cancelReminderNotification --
,D/HtcAlertUtils( 3822): broadcastExistReminder!
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3822): stopSelfResult true
D/PMS     (  903): releaseWL(42711f40): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4310 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/MultiDex( 4297): install
,I/MultiDex( 4297): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,I/MultiDex( 4297): loading existing secondary dex files
,I/MultiDex( 4297): load found 1 secondary dex files
,I/MultiDex( 4297): install done
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/WeatherRequest( 1107): request cur loc, but there is no sys cur
,I/ProviderInstaller( 4297): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4326 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4310): can't get weather sync account
,W/WeatherRequest( 4310): request cur loc, but there is no sys cur
,W/Settings( 4310): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 0 9 17
,D/PMS     (  903): acquireWL(43139160): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4326 10070 null
D/PMS     (  903): acquireWL(43e7c300): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4326 10070 null
D/PMS     (  903): releaseWL(43139160): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 4326): update TASK shortcut>
,I/CalendarProvider2( 4194): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4194): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  903): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4344 uid=10090 gids={50090, 3003, 5012, 1028}
,D/Process (  903): killProcessQuiet, pid=3752
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/GoogleHttpClient( 4297): Falling back to old SSLCertificateSocketFactory
I/ActivityManager(  903): Killing 3752:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3752
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/TodoTaskNotifyService( 4326): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 4326): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4326): stopSelfResult true
,D/Process (  903): killProcessQuiet, pid=3802
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  903): releaseWL(43e7c300): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Killing 3802:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3802
,I/WorldClock.Global( 4344): isHtcDevice = true
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.Global( 4344): isHtcDevice = true
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4344): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  903): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4360 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 4344): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4344): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
D/libc    ( 4297): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4297): [NET] getaddrinfo-,err=8
D/libc    ( 4297): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4297): [NET] getaddrinfo-, 1
D/libc    ( 4297): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1606 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,I/IntentController( 1107): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 105
D/libc    (  364): [NET]res_nsend:resplen=86
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4297): [NET] getaddrinfo_proxy-, success
,D/Process (  903): killProcessQuiet, pid=3619
,I/ActivityManager(  903): Killing 3619:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TimeService( 4360): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832345375
,I/ActivityManager(  903): Recipient 3619
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3918
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  903): Killing 3918:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/libc    ( 4297): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4297): [NET] getaddrinfo-,err=8
D/AutoSetting( 4218): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 4218): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  903): Recipient 3918
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TetherSettings( 3325): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
D/        ( 3325): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3325): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3325): Cust_ConnectToPC   : spcsc>false
D/        ( 3325): Cust_ConnectToPC   : IPT>true
D/        ( 3325): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
E/SmartNS_Utility( 3325): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3325): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3325): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,I/PSReceiver( 3325): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3325): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3325):  defaultType:0
I/ActivityManager(  903): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4379 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  903): acquireWL(44262930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10028 null
,D/PMS     (  903): releaseWL(44262930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4379): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 ,
,D/PMS     (  903): acquireWL(43dd12d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4379 1000 null
D/SmartSyncUtils( 4379): isEpsOn(), nState = 0
,D/PMS     (  903): releaseWL(43dd12d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/SmartSyncUtils( 4379): getMobilePolicyEnabled, result = true
,D/Process (  903): killProcessQuiet, pid=4027
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4027:com.htc.widget.process2/u0a48 (adj 15): empty #17
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Recipient 4027
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4379): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4379): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4379): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4379): isEpsOn(), nState = 0
D/WifiService(  903): New client listening to asynchronous messages
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42914170
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42914170, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42914170, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42914170
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@429146b8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@429146b8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4399 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4399): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4399): MmsConfig.loadMmsSettings
,E/dalvikvm( 4399): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4399): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4399): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4399): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4399): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  903): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4422 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ProviderInstaller( 4399): Installed default security provider GmsCore_OpenSSL
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4399, uid=10111, userID:0
,W/Settings( 4399): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4422): onCreate
,D/MmsCustomizationProvider( 4422): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4422): GetPrviateResource
,V/GetPrviateResource( 4422): GetPrviateResource
,D/MmsCustomizationProvider( 4422): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4399): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4399): MmsConfig.loadFromDatabase
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4399, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4399, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4399, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4399, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4399, uid=10111, userID:0
,E/Babel   ( 4399): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4399): MmsConfig.loadFromResources
E/Babel   ( 4399): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4399): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,D/Process (  903): killProcessQuiet, pid=3959
,I/ActivityManager(  903): Killing 3959:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  903): Recipient 3959
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (4399/10111)
,I/ActivityManager(  903): Resuming delayed broadcast
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Process (  903): killProcessQuiet, pid=3978
,I/ActivityManager(  903): Killing 3978:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/MessageCustFlag( 4422): sense_version=6.0
D/BTAccessoryUtil( 4422): createReceiver
D/BTAccessoryUtil( 4422): registerReceiver return intent = null
D/MessageCustFlag( 4422): sku_id=99
,W/SystemReader( 4422): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/Messaging( 4422): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4422): networkCode: 
D/MessageCustFlag( 4422): sku_id=99
D/MmsConfig( 4422): SIE smsPri: null
,D/MmsConfig( 4422): networkCode: 
I/ActivityManager(  903): Recipient 3978
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Resuming delayed broadcast
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (4399/10111)
D/HtcTelephonyCapability( 4422): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4422): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4422): getRATByHtcTelephonyCapability:1
W/SystemReader( 4422): Cannot find qct_8960_interface, use default value instead
D/ProviderChangeReceiver( 3822): ---------------------------------------------------
D/ProviderChangeReceiver( 3822): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3822): start to updateAlertNotification!
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3822): No fired or scheduled alerts
,D/HtcAlertUtils( 3822): -- cancelReminderNotification --
,D/HtcAlertUtils( 3822): broadcastExistReminder!
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  903): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(4418d538): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4326 10070 null
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,E/TodoTaskNotifyService( 4326): java.lang.NullPointerException
,W/System.err( 4326): java.lang.NullPointerException
W/System.err( 4326): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4326): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4326): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4326): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4326): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  903): acquireWL(44163208): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4326 10070 null
I/ActivityManager(  903): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  903): releaseWL(4418d538): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  903): releaseWL(44163208): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4326): stopSelfResult true
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(43fa75b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4326 10070 null
D/PMS     (  903): acquireWL(43f02778): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4326 10070 null
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4448 uid=10038 gids={50038}
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/TodoTaskNotifyService( 4326): java.lang.NullPointerException
,W/System.err( 4326): java.lang.NullPointerException
W/System.err( 4326): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4326): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4326): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4326): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4326): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Babel   ( 4399): UserRecoverableAuthException.
,E/Babel   ( 4399): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4399): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4399): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4399): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4399): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4399): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4399): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4399): Error getting auth token
,E/Babel   ( 4399): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4399): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4399): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4399): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4399): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4399): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
D/PMS     (  903): releaseWL(43fa75b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  903): releaseWL(43f02778): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 4326): stopSelfResult true
,E/Babel   ( 4399): Account registration failedRedacted-21
E/Babel   ( 4399): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4399): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4399): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4399): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4399): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4399): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4399): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4399): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (4399/10111)
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4463 uid=10077 gids={50077}
,D/Process (  903): killProcessQuiet, pid=4116
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4116:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4116
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  903): Client com.google.android.music (pid 4116): Died!
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,D/SMSBackup( 4463): Got a database change event
,D/Process (  903): killProcessQuiet, pid=4167
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,I/ActivityManager(  903): Killing 4167:com.facebook.katana/u0a26 (adj 15): empty #17
W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4399): Unexpected exception while authenticating.
,E/Babel   ( 4399): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4399): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4399): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4399): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4399): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4399): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4399): 	at java.lang.Thread.run(Thread.java:864)
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{420c3248 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 8 2 12
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4297/10028)
,I/ActivityManager(  903): Recipient 4167
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): acquireWL(433a82d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1391 10028 null
,D/PMS     (  903): acquireWL(4311e450): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1391 10028 null
,D/PMS     (  903): releaseWL(433a82d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(4311e450): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  903): releaseWL(42417da8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4297): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 1198): Sending checkin request (8988 bytes)
W/ActivityThread( 1198): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/Process (  903): killProcessQuiet, pid=3413
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3413:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3413
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1198): [NET] getaddrinfo-, 1
,D/libc    ( 1198): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b020 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 103
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1198): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(42629948): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10028 null
,D/PMS     (  903): releaseWL(42629948): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/CheckinResponseProcessor( 1198): From server: 1 gservices updates and 0 deletes
,D/PMS     (  903): releaseWL(434a3c80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CertBlacklister(  903): Certificate blacklist changed, updating...
,I/CertBlacklister(  903): Certificate blacklist updated
,I/GservicesProvider( 1336): main difference update completed
,I/ActivityManager(  903): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4483 uid=10016 gids={50016, 3003, 5012, 2001}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4233/10078)
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1198/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=1 [51][1][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1198/10028)
,W/ContextImpl( 4483): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4483): Update started
,I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,I/ActivityManager(  903): Resuming delayed broadcast
W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/UpdateRequestReceiver( 4483): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4483): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
D/ConnectivityService(  903): getAllNetworkInfo called by  (2211/10021)
,I/UpdateFetcherService( 4483): Update started
,D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1198): awaiting user notification for token
,I/RemoteViews( 1107): com.google.android.gms (false,0)
I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{42181ca0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/DownloadManager( 2211): Download 139 starting
D/PMS     (  903): acquireWL(4286b760): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2211 10021 WorkSource{10016}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 10 4 12
D/ConnectivityService(  903): getAllNetworkInfo called by  (2211/10021)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
W/ActivityThread( 2211): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/CheckinTask( 1198): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1198): Unable to close GMS GoogleHttpClient
I/ActivityManager(  903): Resuming delayed broadcast
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/ConnectivityService(  903): getAllNetworkInfo called by  (2211/10021)
E/UpdateRequestReceiver( 4483): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 4483): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4483): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/Process (  903): killProcessQuiet, pid=4233
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4233:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,D/PMS     (  903): acquireWL(438cd0a0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2211 10021 WorkSource{10016}
I/ActivityManager(  903): Recipient 4233
,I/DownloadManager( 2211): Download 140 starting
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getAllNetworkInfo called by  (2211/10021)
D/Messaging( 4422): mNeedToUpdateDate2 start
D/MmsConfig( 4422): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4422): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4422): 
D/MmsAsyncWorkHandler( 4422): HM tk = 20001
,D/ReportIndicatorCache( 4422): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4422): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41e09910
I/Messaging( 4422): mccmnc> 
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1216):  phoneType = -1
,D/MmsSmsV2Provider( 1216): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4422): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4422): [DraftCache/1] refresh
D/MmsConfig( 4422): networkCode: 
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
D/Messaging( 4422): ViewCache CreatePreloadOnlyConversationList
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.analytics.internal.GServicesChangedReceiver
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1216):  phoneType = -1
D/MmsSmsV2Provider( 1216): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/MessageCustFlag( 4422): sense_version=6.0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Jerry   ( 4422): start to preload cursor >>>>>>>
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 2211): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2211): [NET] getaddrinfo-,err=8
D/libc    ( 2211): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2211): [NET] getaddrinfo-, 1
D/libc    ( 2211): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =99d7 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/PhoneStorageUtil( 4422): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4422): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4422): createReceiver
D/libc    ( 2211): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2211): [NET] getaddrinfo-,err=8
D/libc    ( 2211): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2211): [NET] getaddrinfo-, 1
D/libc    ( 2211): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =acd1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/Messaging( 4422): mNeedToUpdateDate2: false
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/TelephUtils( 1216): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
V/MmsProvider( 1216): Update uri=content://mms, match=0
,V/MmsProvider( 1216): selection=st=129 AND m_type!=134
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1216):  phoneType = -1
D/Messaging( 4422): Reset downloading state: 0
,V/GA-SERVICE( 1198): Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
,V/MmsSystemEventReceiver( 4422): TransactionService is going to be woken up.
D/PMS     (  903): releaseWL(442d3d88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1198): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41f21e00 that was originally bound here
E/ActivityThread( 1198): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41f21e00 that was originally bound here
E/ActivityThread( 1198): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1198): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1198): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1198): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1198): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1198): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1198): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1198): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1198): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1198): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1198): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1198): 	at bks.a(SourceFile:298)
E/ActivityThread( 1198): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1198): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1198): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1198): 	at java.lang.Thread.run(Thread.java:864)
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1198, uid=10028, userID:0
,I/ActivityManager(  903): Delaying start of: ServiceRecord{43148fc0 u0 com.htc.sense.mms/.transaction.TransactionService}
V/TransactionService( 4422): 1-Creating TransactionService
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1216):  phoneType = -1
D/MmsSmsV2Provider( 1216): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/Messaging( 4422): ViewCache CreatePreload
D/Messaging( 4422): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 4422): onStartCommand: 1
D/MmsSystemEventReceiver( 4422): unRegisterForConnectionStateChanges
V/TransactionService( 4422): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4422): Loading previous transactions.
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/AccFlag ( 1216): sku_id=99
D/Cust_MMSMS( 4422): _has_set_default_values_2=true
D/DraftCache( 4422): [DraftCache/454] rebuildCache
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1216):  phoneType = -1
D/MmsSmsV2Provider( 1216): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/AccFlag ( 1216): device_type: 1
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 230
D/MsgPreferenceUtils( 4422): def_index: 0
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2211): [NET] getaddrinfo_proxy-, success
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2211): [NET] getaddrinfo_proxy-, success
D/Messaging( 4422): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/Jerry   ( 1216): URI_DRAFT
D/TransactionService( 4422): Force set service start id to 1
V/TransactionService( 4422): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4422): unRegisterForConnectionStateChanges
,D/TransactionService( 4422): stopSelfResult: true, mLastHandledServiceId: 1
,I/ActivityManager(  903): Resuming delayed broadcast
,V/TransactionService( 4422): Destroying TransactionService
,D/DraftCache( 4422): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4422): [DraftCache/454] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4422): 
D/MmsAsyncWorkHandler( 4422): HM tk = 20002
,V/TransactionService( 4422): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4422): globalIndex = 1
D/PMS     (  903): acquireWL(43908f30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
I/ActivityManager(  903): Delay finish: com.google.android.gms/.checkin.CheckinService$Receiver
D/MsgPreferenceUtils( 4422): phone state: true
D/MsgPreferenceUtils( 4422): sd state: false
,D/MsgPreferenceUtils( 4422): vIndex = 0
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1216): sku_id=99
D/PMS     (  903): acquireWL(428d4790): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
D/PMS     (  903): releaseWL(43908f30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1216): sku_id=99
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): releaseWL(428d4790): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/SystemUpdateService( 1198): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/PMS     (  903): acquireWL(438b1468): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1198 10028 null
I/ActivityManager(  903): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/DownloadManager( 2211): Ignoring Content-Length since Transfer-Encoding is also defined
I/SystemUpdateService( 1198): cancelUpdate (empty URL)
,I/SystemUpdateService( 1198): active receiver: disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1198, uid=10028, userID:0
,I/SystemUpdateService( 1198): cancelUpdate (empty URL)
,I/SystemUpdateService( 1198): active receiver: disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1198, uid=10028, userID:0
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(438b1468): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
,D/GCM     ( 1336): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  903): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
D/PMS     (  903): acquireWL(42904a98): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [12][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42904a98): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,I/GCM     ( 1336): GCM config loaded
,I/DownloadManager( 2211): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2211): Download 140 finished with status SUCCESS
D/PMS     (  903): releaseWL(438cd0a0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,D/SystemEventReceiver( 1198): Received GSERVICES_CHANGED broadcast
I/ActivityManager(  903): Resuming delayed broadcast
,I/DownloadManager( 2211): Download 139 finished with status SUCCESS
,I/OcrUtils( 1198): Updating ocr activity enabled=false
,I/GCoreUlr( 1391): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
D/PMS     (  903): releaseWL(4286b760): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/PMS     (  903): acquireWL(44318ea0): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1391 10028 null
,I/GCoreUlr( 1391): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4555 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4555, uid=10031, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4555, uid=10031, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4555, uid=10031, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=4555, uid=10031, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4555, uid=10031, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4555, uid=10031, userID:0
,D/PMS     (  903): acquireWL(442eb690): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
,D/PMS     (  903): releaseWL(442eb690): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  903): acquireWL(442d3d88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
,D/PMS     (  903): releaseWL(442d3d88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  903): acquireWL(442beb90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
,D/PMS     (  903): releaseWL(442beb90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  903): acquireWL(4428b278): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
,D/PMS     (  903): releaseWL(4428b278): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  903): acquireWL(4426c518): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
,D/PMS     (  903): releaseWL(4426c518): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  903): acquireWL(42696cb8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
,D/PMS     (  903): releaseWL(42696cb8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/GCoreUlr( 1391): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1391): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(4239ee18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
D/PMS     (  903): releaseWL(4239ee18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  903): acquireWL(41e84138): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1391 10028 null
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=4141
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/GCoreUlr( 1391): Unbound from all location providers
D/PMS     (  903): releaseWL(41e84138): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/ActivityManager(  903): Killing 4141:com.android.chrome/u0a96 (adj 15): empty #17
D/PMS     (  903): releaseWL(44318ea0): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4141
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4577 uid=10078 gids={50078, 3003, 5012}
,E/PhoneMonitor( 4577): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4577): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4577/10078)
,I/ActivityManager(  903): Killing 4250:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=4250
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4577/10078)
,D/PMS     (  903): acquireWL(425d22b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,I/Search.GservicesUpdateTask( 2662): Updating Gservices keys
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4577/10078)
D/PMS     (  903): acquireWL(42317080): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
D/PMS     (  903): releaseWL(425d22b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): releaseWL(42317080): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
,W/Search.LoginHelper( 2662): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2662): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
,I/ActivityManager(  903): Resuming delayed broadcast
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 3655): Grow heap (frag case) to 13.623MB for 1821008-byte allocation
I/ActivityManager(  903): Recipient 4250
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3655, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/GCM     ( 1336): GCM config loaded
,I/dalvikvm-heap( 3655): Grow heap (frag case) to 15.318MB for 1821008-byte allocation
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3655, uid=10160, userID:0
,W/ContextImpl( 4483): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/ConnectivityService(  903): getAllNetworkInfo called by  (2211/10021)
,I/DownloadManager( 2211): Download 141 starting
D/PMS     (  903): acquireWL(4354b988): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2211 10021 WorkSource{10016}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4483): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
D/ConnectivityService(  903): getAllNetworkInfo called by  (2211/10021)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2211): Ignoring Content-Length since Transfer-Encoding is also defined
I/ActivityManager(  903): Resuming delayed broadcast
D/ConnectivityService(  903): getAllNetworkInfo called by  (2211/10021)
,I/AdsMeasurementBroadcastReceiver( 1198): Reporting settings might have changed, alerting AdsMeasurementService
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/AdsMeasurementBroadcastReceiver( 1198): Unauthorized to start the main service
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2211): Download 142 starting
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): acquireWL(442c0cd8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2211 10021 WorkSource{10016}
D/ConnectivityService(  903): getAllNetworkInfo called by  (2211/10021)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2211): Ignoring Content-Length since Transfer-Encoding is also defined
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2211/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [31][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2211): Download 141 finished with status SUCCESS
D/PMS     (  903): releaseWL(4354b988): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4483): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4483): Update downloaded, starting installation
,I/UpdateFetcherService( 4483): Started installation
I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/DownloadManager( 2211): Download 142 finished with status SUCCESS
D/PMS     (  903): releaseWL(442c0cd8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/ActivityManager(  903): Resuming delayed broadcast
,W/ContextImpl( 4483): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/ActivityManager(  903): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
I/UpdateFetcherService( 4483): Update downloaded, starting installation
I/UpdateFetcherService( 4483): Started installation
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ConfigUpdateInstallReceiver(  903): Not installing, new version is <= current version
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4399, uid=10111, userID:0
,D/Process (  903): killProcessQuiet, pid=4310
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4310:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4310
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Process (  903): killProcessQuiet, pid=4344
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4344:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4344
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3655): Grow heap (frag case) to 17.071MB for 1821008-byte allocation,
,I/GAV2    ( 3655): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 4218): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4218): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4218): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,W/PackageSettings(  903): Skipping PackageSetting{42565978 com.example.hello/10355} due to missing metadata
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{431b8300 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
,D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1247): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/Launcher( 1247): Deferring update until onResume,
,D/Launcher( 1247): waitUntilResume // bindAppsUpdated
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/PeopleContactsSync( 1198): CP2 sync disabled
,I/[PluginManager]RegisterService( 4218): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 4218): handle notify Blinkfeed plugin client changed
,D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  903): acquireWL(436b1e08): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/ActivityManager(  903): Resuming delayed broadcast
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4621 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/PMS     (  903): releaseWL(436b1e08): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4621, uid=10073, userID:0
,D/Finsky  ( 4621): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4621/10073)
,D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4621/10073)
,D/Finsky  ( 4621): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4621): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4621): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4621, uid=10073, userID:0
,D/Finsky  ( 4621): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4621): [1] 2.run: Finished loading 1 libraries.
,D/Process (  903): killProcessQuiet, pid=4360
,I/ActivityManager(  903): Killing 4360:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/IcingCorporaProvider( 2662): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  903): Recipient 4360
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(442ddce0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3655 10160 null
,D/Finsky  ( 4621): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PMS     (  903): releaseWL(442ddce0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4621): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/IcingCorporaProvider( 2662): UpdateCorporaTask done [took 229 ms] updated apps [took 228 ms] 
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41e91ed0 +
,I/Prism.WidgetManager( 1247): onLoadItems() +
,D/PMS     (  903): acquireWL(4285eaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
,V/AlarmManager(  903): sending alarm PendingIntent{4234cd30: PendingIntentRecord{42689398 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449832362853, Int=0
,W/PackageManager(  903): Unable to load service info ResolveInfo{42893230 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
,D/PMS     (  903): releaseWL(4285eaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4621): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4621): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/asset   ( 1247): Copying FileAsset 0x64a7d710 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
,I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41e91ed0 -
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4621): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4621): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4621): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/PMS     (  903): acquireWL(426604d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=100
D/PMS     (  903): releaseWL(426604d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PhoneApp( 1216): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1216): -- N1 =0
,D/PhoneApp( 1216): -- N2 =0
,D/PhoneApp( 1216): -- N3 =0
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(42c21a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{420a2038: PendingIntentRecord{427897b0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=139735, Int=0
,D/PMS     (  903): acquireWL(431bab90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42c21a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42c1e320): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(431bab90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(42c1e320): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 4218): service - mHandler: update timezone
,D/AutoSetting( 4194): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4194): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4194): service - onCreate()
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4194): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4194): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4194): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4194): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4194): service - mHandler: update timezone
,D/AutoSetting( 4194): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4194): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4194): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4194): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1107): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{421ab5c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.htclocationservice 3 26 8 11
,D/AutoSetting( 4218): service - handleMessage() stop self
,D/AutoSetting( 4218): service - handleMessage() quit looper
,D/AutoSetting( 4218): service - onDestroy() END
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  903): acquireWL(43a1ffa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{422810b8: PendingIntentRecord{42875428 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140386, Int=0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
,V/AlarmManager(  903): sending alarm PendingIntent{42630258: PendingIntentRecord{43022c58 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449832378061, Int=563223000
,V/AlarmManager(  903): sending alarm PendingIntent{421104a8: PendingIntentRecord{426d2388 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449832378253, Int=0
,D/PMS     (  903): acquireWL(43934ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10028 null
,D/PMS     (  903): acquireWL(4333b128): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(43934ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  903): releaseWL(43a1ffa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  903): acquireWL(43e7e3c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(4333b128): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,I/CheckinService( 1198): Preparing to send checkin request
,I/EventLogService( 1198): Accumulating logs since 1449832344666
,W/EventLogAggregator( 1198): Unknown tag: install_package_attempt
W/EventLogAggregator( 1198): Unknown tag: snet
,W/EventLogAggregator( 1198): Unknown tag: snet_gcore
,I/GoogleHttpClient( 1198): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1198): Using GMS GoogleHttpClient
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1198/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [11][0][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1198/10028)
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1198): awaiting user notification for token
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41e02a88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 3 12 3 12
,D/Finsky  ( 4621): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4297/10028)
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4297): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 1198): Sending checkin request (9004 bytes)
,D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1198): [NET] getaddrinfo-, 1
,D/libc    ( 1198): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2085 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1198): [NET] getaddrinfo_proxy-, success
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(4429b320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=148145, Int=0
I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4429b320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43e82808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10028 null
,D/PMS     (  903): releaseWL(43e82808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1198/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1198/10028)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=18 [16][3][0]
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1198): awaiting user notification for token
,D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41fba8a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 3 10 3 12
,I/CheckinTask( 1198): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1198): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): releaseWL(43e7e3c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1198): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41eebe30 that was originally bound here
E/ActivityThread( 1198): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41eebe30 that was originally bound here
E/ActivityThread( 1198): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1198): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1198): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1198): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1198): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1198): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1198): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1198): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1198): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1198): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1198): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1198): 	at bks.a(SourceFile:298)
E/ActivityThread( 1198): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1198): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1198): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1198): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1336): GCM config loaded
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{442fef68 u0 com.htc.htclocationservice/.AutoSettingService}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43312310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(43312310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/ContextImpl( 4379): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3325): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3325): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3325): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3325): Cust_ConnectToPC   : spcsc>false
D/        ( 3325): Cust_ConnectToPC   : IPT>true
D/        ( 3325): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3325): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3325): Index of the first 1 = -1
,W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3325): hasRemovableStorageSlot: true
I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 3325): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3325): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3325): [ACC]android_networking:tethering_guard_support=false
,D/AutoSetting( 4194): service - handleMessage() stop self
,D/AutoSetting( 4194): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=4399
,D/AutoSetting( 4194): service - handleMessage() quit looper
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 4399:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4399
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(435273a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(435273a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43886d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=208145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43886d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(4290c190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4290c190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(43a56618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=268145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43a56618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4428b118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4428b118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3872): Connected to the server!
I/jxcore-log( 3872): 
,I/chromium( 3872): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43502788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43502788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43882740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=328145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43882740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(4349e330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4349e330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(4433c0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=388145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4433c0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42a09858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(42a09858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,W/GLSActivity( 1336): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1336): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1336): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1336): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1336): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1336): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1336): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1336): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{421f3798 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 9 3 12
,E/PlayEventLogger( 4621): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4621): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4621): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4621): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4621): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4621): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4621): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4621): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 4621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4621): [NET] getaddrinfo-,err=8
D/libc    ( 4621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4621): [NET] getaddrinfo-, 1
,D/libc    ( 4621): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ae4e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 268
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4621): [NET] getaddrinfo_proxy-, success
I/global  ( 4621): call createSocket() return a new socket.
,D/libc    ( 4621): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4621): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  903): acquireWL(43005c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(43005c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/libc    ( 4621): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4621): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(43ec7718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=448145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43ec7718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43008af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43008af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(428c4828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428c4828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(43ee31b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=508145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43ee31b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(434a3aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(434a3aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43874318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=568145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43874318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(442a8580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(442a8580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1216): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1216): sku_id=99
D/ContactMessageStore( 1216): start background delete task...
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1216): size: 0 , 0
,D/ContactMessageStore( 1216): Background delete complete,
,D/PMS     (  903): acquireWL(43877810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=628145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43877810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42b62270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42b62270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43d010d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=688146, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43d010d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  903): killProcessQuiet, pid=3822
,I/ActivityManager(  903): Killing 3822:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 3822
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4691 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  903): acquireWL(43a85048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10047}
V/AlarmManager(  903): sending alarm PendingIntent{42864ec8: PendingIntentRecord{427f27a8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449832449889, Int=10800000
,V/AlarmManager(  903): sending alarm PendingIntent{442b9b50: PendingIntentRecord{42365d00 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449832646835, Int=1800000
,V/AlarmManager(  903): sending alarm PendingIntent{442b9cd8: PendingIntentRecord{42689398 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449832963548, Int=0
,D/PMS     (  903): acquireWL(43ab5908): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1198 10028 null
,D/PMS     (  903): acquireWL(442dee40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(442dee40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): releaseWL(43a85048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  903): acquireWL(431c04a0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(43ab5908): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 1198): Aggregate from 1449832378340 (log), 1449830846763 (data)
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4691/10047)
,D/PMS     (  903): releaseWL(431c04a0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4621): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4621): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1336): GoogleAccountDataService.getToken()
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1336): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4621): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4621): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4621): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/Process (  903): killProcessQuiet, pid=3836
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3836:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
,I/ActivityManager(  903): Recipient 3836
,D/PMS     (  903): acquireWL(4316bcf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
,V/AlarmManager(  903): sending alarm PendingIntent{422f7e08: PendingIntentRecord{426d2388 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449832978786, Int=0
,D/PMS     (  903): releaseWL(4316bcf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4621): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  903): acquireWL(427b0588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=748146, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(427b0588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42861e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{420d4670: PendingIntentRecord{42734f98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781074, Int=0
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/PMS     (  903): releaseWL(42861e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): acquireWL(43ddd538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43ddd538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43827750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=808145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43827750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43a36700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43a36700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43e71b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=868145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43e71b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43dd0a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43dd0a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42804180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=928145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42804180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(442d5830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(442d5830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43bc89b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=988145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43bc89b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(439dcee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{433c4528: PendingIntentRecord{42848e88 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012729, Int=0
,D/PMS     (  903): acquireWL(428b0d50): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1336 10028 null
,D/PMS     (  903): releaseWL(428b0d50): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,V/AlarmManager(  903): sending alarm PendingIntent{4234d2f0: PendingIntentRecord{4241bed0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449833170428, Int=900000
,V/AlarmManager(  903): sending alarm PendingIntent{426e6350: PendingIntentRecord{428a0bf8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449833245668, Int=0
,D/PMS     (  903): acquireWL(43e1e1a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10028 null
,W/ContextImpl( 4379): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(43e1e1a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4379): call getInstance()
,D/SmartSyncUtils( 4379): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4379): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4379): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4379): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
D/PMS     (  903): releaseWL(439dcee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(438eba00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4379 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4379): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4379): SettingOnTime = 1449882000000, randomSettingOnTime = 1449879776000
D/SmartSyncScreenOnOffTimeReceiver( 4379): SettingOffTime = 1449878400000, randomSettingOffTime = 1449878566000
D/SmartSyncScreenOnOffTimeReceiver( 4379): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4379): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4379): bNightModeTurnOffOnce = false
D/PMS     (  903): releaseWL(438eba00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(44318b68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1336 10028 null
,D/GCM     ( 1336): Message class mow
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1336/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1336/10028)
,D/PMS     (  903): releaseWL(44318b68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(429253c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1336 10028 null
,D/PMS     (  903): releaseWL(429253c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  903): acquireWL(430107c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(430107c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42f9b320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1048145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42f9b320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43a54d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43a54d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43dc21e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1108145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43dc21e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43d9bc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43d9bc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43a678f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1168145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43a678f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43ee3228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(43ee3228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(428ed3e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1228145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(428ed3e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(434a3a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(434a3a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43eb5298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1288145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43eb5298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(442876b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(442876b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43df95d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1348145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43df95d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(44222010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(44222010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43d64660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1408146, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43d64660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43106410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43106410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43e95760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1468145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43e95760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4388c7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/BatteryService(  903): n_update end
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/PMS     (  903): releaseWL(4388c7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43ea5470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1528145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43ea5470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4292b148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4292b148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(431652a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1588145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(431652a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43623898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43623898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4285b7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4285b7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43db3300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1648145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43db3300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(44310da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(44310da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4273b2d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4273b2d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43ecaec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1708145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43ecaec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42d11ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  903): sending alarm PendingIntent{420d4670: PendingIntentRecord{42734f98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1501101, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{420a2038: PendingIntentRecord{427897b0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1732147, Int=0
,D/PMS     (  903): acquireWL(4269c458): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42d11ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42863648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(4269c458): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(42863648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): acquireWL(42c3e8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42c3e8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(438fa738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1768146, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(438fa738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43e378a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43e378a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(4403fec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4403fec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(43df47c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1828146, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  903): Prepared write state in 45ms
,D/PMS     (  903): releaseWL(43df47c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  903): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-09-47.bin
,I/ProcessStatsService(  903): Prepared write state in 36ms
,I/ProcessStatsService(  903): Prepared write state in 19ms
,D/PMS     (  903): acquireWL(42ddcf30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42ddcf30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
,D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42b69828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/PMS     (  903): releaseWL(42b69828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
,D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(428ef810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41df9890: PendingIntentRecord{4264eec0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1888145, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(428ef810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),D/CustomizationManager( 4723): ====startRecUseTime====
D/htc.customization.log.level( 4723):  is 
W/CustomizationLogLevel( 4723): Level value is invalid, use default level 2
D/CustomizationManager( 4723):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4723): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4723): Parsing tag category name = system
I/CustomizationCIDLoader( 4723): Parsing tag category name = application
I/CustomizationCIDLoader( 4723): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4723): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4723): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4723): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4723): Parsing tag category name = Settings
D/CustomizationManager( 4723):  Read CID file spent 0.156 (s)
D/CustomizationManager( 4723):  All configurations done spent 0.156 (s)
W/HtcNativeFlag( 4723): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4723): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4723): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4723): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4723, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  903): killProcessQuiet, pid=3872
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  903): Killing 3872:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  903):   Force finishing activity ActivityRecord{431c10c0 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  903): Copying FileAsset 0x62ba8bf0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 3872 uid 10348
E/JavaBinder( 1183): !!! FAILED BINDER TRANSACTION !!!
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  903): WIN DEATH: Window{42287ea0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  903): Client connection lost with reason: 4
W/PackageSettings(  903): Skipping PackageSetting{42565978 com.example.hello/10355} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/DotMatrix( 1539): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1539): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
I/acms    ( 1762): Unregistering com.test.thalitest
E/acms    ( 1762): Could not unregister removed application com.test.thalitest
W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1273): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PMS     (  903): acquireWL(442e8d88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1391 10028 null
W/GeofencerStateMachine( 1391): Ignoring removeGeofence because network location is disabled.
E/cutils-trace( 4723): Error opening trace file: No such file or directory (2)
I/Launcher( 1247): Deferring update until onResume
D/Launcher( 1247): waitUntilResume // bindAppsRemoved
D/PMS     (  903): releaseWL(442e8d88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4739 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/MultiDex( 4739): install
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/MultiDex( 4739): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/MultiDex( 4739): loading existing secondary dex files
I/MultiDex( 4739): load found 1 secondary dex files
I/MultiDex( 4739): install done
I/ActivityManager(  903): Delaying start of: ServiceRecord{4429c4c8 u0 com.google.android.gms/.wearable.service.WearableControlService}
E/ExternalAccountType( 1321): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  903):   Scheme: "mmsto"
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4756 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1198): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
D/PMS     (  903): acquireWL(42877018): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
I/Icing   ( 1198): doRemovePackageData com.test.thalitest
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1198): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1198): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1198): Writing status failed
I/ProviderInstaller( 4739): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  903): releaseWL(42877018): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4756): install
I/MultiDex( 4756): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4756): loading existing secondary dex files
I/MultiDex( 4756): load found 1 secondary dex files
I/MultiDex( 4756): install done
E/SQLiteDatabase( 1198): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1198): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1198): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1198): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1198): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1198): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1198): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1198): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1198): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1198): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1198): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1198): Runtime exception while performing operation
E/ClearPendingStateOp( 1198): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1198): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1198): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1198): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1198): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1198): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1198): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1198): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1198): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1198): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1198): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1198): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1198): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1198): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1198): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1198): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1198): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1198): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1198): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1198): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1198): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ProviderInstaller( 4756): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  903): Resuming delayed broadcast
E/SharedPreferencesImpl( 1183): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/DropBoxManagerService(  903): Can't write: system_app_wtf
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 4218): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 4218): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 4218): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9f0c90
W/[PluginManager]RegisterService( 4218): provider may killed!
W/[PluginManager]RegisterService( 4218): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 4218): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 4218): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 4218): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 4218): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 4218): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 4218): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 4218): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4218): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4218): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4218): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4218): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4218): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4218): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4218): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 4326:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=4326
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2662): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4779 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4739): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4739): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4739): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4739): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4739): threadid=12: thread exiting with uncaught exception (group=0x419cfe30)
E/AndroidRuntime( 4739): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4739): Process: com.google.android.gms.drive, PID: 4739
E/AndroidRuntime( 4739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4739): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4739): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4739): 	at ctn.run(SourceFile:985)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
D/Process ( 4739): killProcess, pid=4739
D/Process ( 4739): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  903): Recipient 4739
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4739) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
E/SQLiteLog( 2662): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2662): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x647dbdf0
W/dalvikvm( 2662): threadid=14: thread exiting with uncaught exception (group=0x419cfe30)
I/ActivityManager(  903): Recipient 4326
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2662): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2662): Process: com.google.android.googlequicksearchbox:search, PID: 2662
E/AndroidRuntime( 2662): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2662): 	at cid.d(PG:186)
E/AndroidRuntime( 2662): 	at clo.g(PG:594)
E/AndroidRuntime( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2662): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2662): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2662): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2662): 	at clr.tL(PG:827)
E/AndroidRuntime( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2662): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2662): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2662): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2662): killProcess, pid=2662
D/Process ( 2662): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2662): Died!
D/WifiService(  903): Client connection lost with reason: 4
I/ActivityManager(  903): Recipient 2662
I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2662) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
E/SQLiteDatabase( 4779): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4779): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4779): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4779): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4779): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4779): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4779): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4779): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4779): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4779): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4779): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4779): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4779): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4779): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4779): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4779): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4779): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4779): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4779): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4779): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4779): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4779): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4779): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4779): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4779): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4779): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4779): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4779): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4779): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4779): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4779): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4779): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4779): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4779): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4779): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4779): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4779): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4779): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4779): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4779): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4779): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4779): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4779): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4779): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4779): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4779): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4779): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4779): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4779): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4779): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4779): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4779): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4779): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4779): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4779): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4779): threadid=11: thread exiting with uncaught exception (group=0x419cfe30)
E/AndroidRuntime( 4779): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4779): Process: com.google.android.apps.docs, PID: 4779
E/AndroidRuntime( 4779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4779): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4779): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4779): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4779): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4779): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4779): killProcess, pid=4779
E/SQLiteDatabase( 4779): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4779): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4779): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4779): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4779): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4779): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4779): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4779): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4779): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4779): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4779): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4779): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4779): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4779): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4779): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4797 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/PackageManager(  903): Unable to load service info ResolveInfo{442bfd18 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41e91ed0 +
I/Prism.WidgetManager( 1247): onLoadItems() +
I/ActivityManager(  903): Recipient 4779
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  903): killProcessQuiet, pid=4448
I/ActivityManager(  903): Killing 4448:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4779) has died.
I/ActivityManager(  903): Recipient 4448
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4797): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4797): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4797): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4797): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4797): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4797): threadid=10: thread exiting with uncaught exception (group=0x419cfe30)
E/ActivityManager(  903): App crashed! Process: com.android.keychain
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4810 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4797): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4797): Process: com.android.keychain, PID: 4797
E/AndroidRuntime( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4797): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4797): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4797): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4797): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4797): killProcess, pid=4797
D/Process ( 4797): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449834145126.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  903): Recipient 4797
I/ActivityManager(  903): Process com.android.keychain (pid 4797) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10423ms
D/AppTag  ( 4810): getInstance(Context context)
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4810): getInstance(Context context)
D/AppTag  ( 4810): onCreate()
D/PMS     (  903): acquireWL(43ee02c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3655 10160 null
D/PMS     (  903): releaseWL(43ee02c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4828 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4828): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4828 dbg=false s=true

```
