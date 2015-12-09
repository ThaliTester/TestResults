#### Test 50650278b28a87a_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3822 uid=10078 gids={50078}
,D/PMS     (  905): acquireWL(425159b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10078}
V/AlarmManager(  905): sending alarm PendingIntent{4239ad98: PendingIntentRecord{42665860 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449671219321, Int=60000
D/PMS     (  905): releaseWL(425159b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
--------- beginning of /dev/log/main
D/SMSBackup( 3822): SMSBackupAgentService started
D/SMSBackup( 3822): Checking restore status
D/SMSBackup( 3822): Restore complete
D/SMSBackup( 3822): cancelCheckAlarm
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
D/SMSBackup( 3822): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  905): killProcessQuiet, pid=3656
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3656:com.google.android.apps.docs/u0a100 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3656
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/cutils-trace( 3835): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3835): ====startRecUseTime====
D/htc.customization.log.level( 3835):  is 
W/CustomizationLogLevel( 3835): Level value is invalid, use default level 2
D/CustomizationManager( 3835):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3835): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3835): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3835): Parsing tag category name = system
I/CustomizationCIDLoader( 3835): Parsing tag category name = application
I/CustomizationCIDLoader( 3835): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3835): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3835): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3835): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3835): Parsing tag category name = Settings
D/CustomizationManager( 3835):  Read CID file spent 0.090 (s)
D/CustomizationManager( 3835):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 3835): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3835): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3835): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3835): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3835
D/PMS     (  905): acquireHCC(425fef60): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(440551d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x62c874d0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1128512432
I/FeedHostManager( 1245): [onPause]
I/FeedProviderManager( 1245): onPause
I/FeedHostManager( 1245): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c324e0
I/SocialFeedProvider( 1245): +onPause
I/SocialFeedProvider( 1245): -onPause
D/PMS     (  905): acquireWL(44140278): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3846 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
D/PMS     (  905): acquireWL(4404dc38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=102626, Int=0
I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
W/asset   ( 3846): Copying FileAsset 0x5c793420 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1245): [trimMemory] 20
D/PMS     (  905): releaseWL(4404dc38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
V/WebViewChromiumFactoryProvider( 3846): Binding Chromium to main looper Looper (main, tid 1) {41b19cc8}
I/LibraryLoader( 3846): Expected native library version number "",actual native library version number ""
I/chromium( 3846): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3846): Initializing chromium process, renderers=0
I/ClockThread( 1108): now=1449671220047 next=59953
D/PMS     (  905): acquireWL(42524f30): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(42616980): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423ba5a8:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3846): 1102253784: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  905): releaseWL(42616980): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3846): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3846): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3846): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3846): Local Branch: 
I/Adreno-EGL( 3846): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3846): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3846):                  aa63bbd948f41d15fc72f585e
W/chromium( 3846): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3846): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3846): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3846): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3846): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3846): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3846): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3846): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3846): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3846): CordovaWebView is running on device made by: HTC
,W/AwContents( 3846): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1245
,W/ResourceType( 3846): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3846): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b62460, mServedView=org.apache.cordova.engine.SystemWebView{41b281f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  905): Enable input method client, pid=3846
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +271ms
,W/AwContents( 3846): nativeOnDraw failed; clearing to background color.
,D/PMS     (  905): releaseWL(44140278): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3846): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3846): JniHelper::setJavaVM(0x415f3048), pthread_self() = 1663146344
D/JX-Cordova( 3846): jxcore cordova android initializing
,W/dalvikvm( 3846): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 11.510MB for 64402-byte allocation
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 11.632MB for 144892-byte allocation
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 11.748MB for 217334-byte allocation
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 11.923MB for 325996-byte allocation
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 12.198MB for 488990-byte allocation
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 12.603MB for 733480-byte allocation
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 14.051MB for 1650320-byte allocation
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 15.466MB for 2475476-byte allocation
,I/dalvikvm-heap( 3846): Grow heap (frag case) to 17.467MB for 3713210-byte allocation
,W/jxcore-log( 3846): Initializing JXcore engine
,W/jxcore-log( 3846): JXcore engine is ready
,W/jxcore-log( 3846): Starting JXcore engine
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(425fef60): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(440551d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3846): Platform android
W/jxcore-log( 3846): 
,W/jxcore-log( 3846): Process ARCH arm
W/jxcore-log( 3846): 
,I/jxcore-log( 3846): JXcore Cordova bridge is ready!
I/jxcore-log( 3846): 
,W/jxcore-log( 3846): JXcore engine is started
,I/chromium( 3846): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  905): releaseWL(42524f30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  905): mEventCount = 900
,I/jxcore-log( 3846): Toggling radios to true
I/jxcore-log( 3846): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): checking for enable restriction...
,D/BluetoothManagerService(  905): checkBTEasState, ret=true
I/BluetoothManagerService(  905): isBluetoothRestricted(): false
D/BluetoothManagerService(  905): enable(): region ID = 6
,D/BluetoothManagerService(  905): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 1
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 916
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  905): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3846): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1338
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
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=3846, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,I/ActivityManager(  905): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3891 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3846): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 3846): reconnect: Base Package Name=com.test.thalitest, uid=10389
,D/PMS     (  905): acquireWL(43c09098): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
I/jxcore-log( 3846): Radios toggled
I/jxcore-log( 3846): 
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3846): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3846): 
,I/jxcore-log( 3846): Perf Test app loaded loaded
I/jxcore-log( 3846): 
,I/jxcore-log( 3846): check test folder
I/jxcore-log( 3846): 
,I/jxcore-log( 3846): found test : ./testFindPeers.js
I/jxcore-log( 3846): 
,I/jxcore-log( 3846): found test : ./testSendData.js
I/jxcore-log( 3846): 
,D/AdapterServiceConfig( 3891): Adding HeadsetService
D/AdapterServiceConfig( 3891): Adding A2dpService
D/AdapterServiceConfig( 3891): Adding HidService
D/AdapterServiceConfig( 3891): Adding HealthService
D/AdapterServiceConfig( 3891): Adding PanService
,D/AdapterServiceConfig( 3891): Adding GattService
,W/linker  ( 3891): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3891): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43676050:true,
,D/BluetoothAdapterState( 3891): make
,I/BluetoothAdapterState( 3891): Entering OffState
,I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3891): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:1 len:14
,I/Choreographer( 3846): Skipped 91 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3846): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  905): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapter( 1200): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bbe330
,D/BluetoothAdapter( 1200): onBluetoothServiceUp done
D/BluetoothAdapter(  905): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4414cc08
,D/BluetoothAdapter(  905): onBluetoothServiceUp done
D/BluetoothAdapter( 1232): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c4dc48
,D/BluetoothAdapter( 1232): onBluetoothServiceUp done
D/BluetoothAdapter( 1108): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41eef828
,D/BluetoothAdapter( 1108): onBluetoothServiceUp done
D/BluetoothAdapter( 1216): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41b861d0
,D/BluetoothAdapter( 1216): onBluetoothServiceUp done
,D/BluetoothAdapter( 1347): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41b18760
,D/BluetoothAdapter( 1347): onBluetoothServiceUp done
D/BluetoothAdapter( 3891): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b33dc0
,D/BluetoothAdapter( 3891): onBluetoothServiceUp done
D/BluetoothAdapter( 3846): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4267ab18
D/BluetoothAdapter( 3846): onBluetoothServiceUp done
D/Tethering(  905): interfaceAdded wlan0
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() done
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): wlan0 is not a tetherable iface, ignoring
,D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/BluetoothAdapterState( 3891): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3891): Setting state to 11
I/BluetoothAdapterState( 3891): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3891): Broadcasting updateAdapterState() to 1 receivers.
,D/Tethering(  905): interfaceStatusChanged wlan0, false
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=10 new=11
,D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/BluetoothBondStateMachine( 3891): make
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3891): StableState(): Entering Off State
D/Tethering(  905): interfaceAdded p2p0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): p2p0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/PMS     (  905): releaseWL(43c09098): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,I/IntentController( 1108): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/BluetoothAdapter( 1200): 1105324672: getState(). Returning 11
,D/BluetoothAdapter( 1200): 1105324672: getState(). Returning 11
,D/HeadsetService( 3891): Received start request. Starting profile...
D/HeadsetStateMachine( 3891): Version 1.6
,D/HeadsetStateMachine( 3891): make
D/PMS     (  905): acquireWL(44163a00): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1200 10029 null
D/PMS     (  905): releaseWL(44163a00): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3918 uid=10040 gids={50040, 3002, 3001}
,I/BluetoothAdapterState( 3891): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 3891): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3891): Received start request. Starting profile...
,V/Avrcp   ( 3891): make
,D/Avrcp   ( 3891): fillIntentFilter()
,D/A2dpStateMachine( 3891): make
,D/A2dpStateMachine( 3891): Enter Disconnected: -2
,D/HtcBtWidget_BTWidgetProvider( 3918): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3918): updateWidget(context) for widget: 
,D/HidService( 3891): Received start request. Starting profile...
,D/HealthService( 3891): Received start request. Starting profile...
,D/Process (  905): killProcessQuiet, pid=3676
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PanService( 3891): Received start request. Starting profile...
,I/QuickSettingBluetooth( 1108): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/BluetoothTethering(  905): supplyMessenger
D/BluetoothTethering(  905): supplyMessenger mAsyncChannel is null
,D/BluetoothTethering(  905): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  905): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 3891): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BtGatt.DebugUtils( 3891): handleDebugAction() action=null
D/BtGatt.GattService( 3891): Received start request. Starting profile...
,D/BtGatt.GattService( 3891): start()
V/BluetoothPbapService( 3891): Pbap Service onCreate
,V/BluetoothPbapService( 3891): Starting PBAP service
I/ActivityManager(  905): Killing 3676:com.htc.backup/1000 (adj 15): empty #17
,D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 11
,D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 11
,E/BluetoothMasService( 3891): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 3891): Add permission for SmsProvider.
,V/BluetoothMasService( 3891): Starting MAS instances
,D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 11
,I/MailMessageReceiver( 3891): reg:com.android.bluetooth.btservice.AdapterApp@41b27328 with com.htc.util.mail.MailMessageReceiver@41b67760
I/MailManager( 3891): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b67760
,V/EmailUtils( 3891): Manager Instance is not NULL
I/ActivityManager(  905): Recipient 3676
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3937 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/wpa_supplicant( 3951): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 3951): Add randomness: count=1 entropy=0
D/wpa_supplicant( 3951): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3951): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 3951): Get randomness: len=20 entropy=1
D/wpa_supplicant( 3951): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3951): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 3951): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 3951): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3951): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 3951): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3951): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3951): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3951): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3951): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3951): update_config=1
D/wpa_supplicant( 3951): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3951): device_name='Android_1950'
D/wpa_supplicant( 3951): manufacturer='HTC'
D/wpa_supplicant( 3951): model_name='HTC_PHONE'
D/wpa_supplicant( 3951): model_number='1234'
D/wpa_supplicant( 3951): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3951): p2p_oper_reg_class=126
D/wpa_supplicant( 3951): p2p_oper_channel=36
D/wpa_supplicant( 3951): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 3951): persistent_reconnect=1
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 3951): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3951): nl80211: RFKILL status not available
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3951): nl80211: Using driver-based roaming
D/wpa_supplicant( 3951): nl80211: TDLS supported
D/wpa_supplicant( 3951): nl80211: TDLS external setup
D/wpa_supplicant( 3951): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3951): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3951): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3951): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3951): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3951): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 3951): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3951): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8542758
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Re,gister frame type=0xd0 nl_handle=0xb8542758
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3951): htc_wext_command_init +
E/wpa_supplicant( 3951): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 3951): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3951): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3951): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3951): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3951): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3951): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3951): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 3951): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/EmailUtils( 3891): ============NULL aList========
V/EmailUtils( 3891): <-getEmailAccountIdList
,V/BluetoothMasService( 3891): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 11
V/BluetoothMasService( 3891): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3891): Manager Instance is not NULL
D/EmailUtils( 3891): ============NULL aList========
,V/EmailUtils( 3891): <-getEmailAccountIdList
V/BluetoothSapService( 3891): Sap Service onCreate
,V/BluetoothSapService( 3891): initBinder
V/BluetoothSapService( 3891): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b6cb50
,V/BluetoothSapReceiver( 3891): BluetoothSapReceiver init
,D/BluetoothSapService( 3891): setSapService()
V/BluetoothSapService( 3891): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3891): state: 12
,D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 11
D/BluetoothAdapterService( 3891): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3891): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3891): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3891): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3891): Profile still not running:com.android.bluetooth.pan.PanService
,D/PanService( 3891): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterService( 3891): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3891): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  905): got CMD_CHANNEL_FULLY_CONNECTED
,I/ActivityManager(  905): Killing 3643:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=3643
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/BluetoothMasReceiver( 3891): Bluetooth STATE CHANGED to 11
,I/qcom-bluetooth( 3957): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  905): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3958 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3643
,I/qcom-bluetooth( 3975): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 3976): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3958): Received state change = 11
,I/qcom-bluetooth( 3978): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/WifiMonitor(  905): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1108): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/qcom-bluetooth( 3979): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/WIFI_ICON( 1108): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/qcom-bluetooth( 3980): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3981): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/ActivityManager(  905): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=3982 uid=10050 gids={50050}
,D/WifiService(  905): New client listening to asynchronous messages
,D/Process (  905): killProcessQuiet, pid=3694
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1347): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  905): Killing 3694:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3694
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 3951): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 3951):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 3951):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3951):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3951): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3951): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3951): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3951): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3951): nl80211: Flush PMKIDs
E/wpa_supplicant( 3951): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 3951): State: DISCONNECTED -> INACTIVE
,I/QuickSettingWifi( 1108): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/HtcWiFiWidget_WiFiWidgetProvider( 3982): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 3982): updateWidget(context) for widget: 
,D/Process (  905): killProcessQuiet, pid=3564
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  905): Killing 3564:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3564
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 3951): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3951): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3951): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 3951): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3951): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3951): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): Using existing control interface directory.
D/wpa_supplicant( 3951): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 3951): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 3951): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 3951): P2P: Own listen channel: 11
D/wpa_supplicant( 3951): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 3951): P2P: Add operating class 81
I/wpa_supplicant( 3951): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 3951): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3951): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3951): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3951): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3951): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3951): disable_scan_offload=1
D/wpa_supplicant( 3951): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 3951): update_config=1
D/wpa_supplicant( 3951): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3951): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3951): manufacturer='HTC'
D/wpa_supplicant( 3951): model_name='HTC Desire 820'
D/wpa_supplicant( 3951): model_number='HTC Desire 820'
D/wpa_supplicant( 3951): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 3951): persistent_reconnect=1
D/wpa_supplicant( 3951): p2p_disabled=1
D/wpa_supplicant( 3951): hs20=1
D/wpa_supplicant( 3951): interworking=1
D/wpa_supplicant( 3951): Line: 18 - start of a new network block
D/wpa_supplicant( 3951): key_mgmt: 0x2
D/wpa_supplicant( 3951): priority=1 (0x1)
,D/wpa_supplicant( 3951): signinfail=0 (0x0),
,I/qcom-bluetooth( 3997): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 3998): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3891): btu_task pending for preload complete event
,D/wpa_supplicant( 3951): Priority group 1
D/wpa_supplicant( 3951):    id=0 ssid='NG700'
I/wpa_supplicant( 3951): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 3951): nl80211: RFKILL status not available
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3951): nl80211: Using driver-based roaming
D/wpa_supplicant( 3951): nl80211: TDLS supported
D/wpa_supplicant( 3951): nl80211: TDLS external setup
D/wpa_supplicant( 3951): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3951): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3951): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3951): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3951): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3951): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 3951): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3951): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8552718
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3951): htc_wext_command_init +
I/wpa_supplicant( 3951): htc_wext_command_init -
I/wpa_supplicant( 3951): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 3951): Don't set 00 to countryID.conf
D/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 3951): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 3951): nl80211: Use separate P2P group interface
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 95
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3951): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3951): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3951): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3951): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3951): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5250-5330 @ 80 MHz,
D/wpa_supplicant( 3951): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3951): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged wlan0, false,
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 3951): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 3951):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 3951):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3951):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3951): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3951): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3951): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3951): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3951): nl80211: Flush PMKIDs
,E/wpa_supplicant( 3951): send_and_recv error -22 - cmd 54,
,D/wpa_supplicant( 3951): TDLS: TDLS operation supported by driver
,D/wpa_supplicant( 3951): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3951): WPS: Set UUID for interface wlan0
,D/wpa_supplicant( 3951): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3951): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
,D/wpa_supplicant( 3951): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 3951): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3951): Using existing control interface directory.
,I/wpa_supplicant( 3951): set country (DE) from /data/misc/wifi/countryID.conf
,I/wpa_supplicant( 3951): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 3951): Auto country group 1: ch36
I/wpa_supplicant( 3951): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3951): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 3951): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3951): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3951): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 3951): Get randomness: len=20 entropy=0
V/RegulatoryObserver(  905): uevent:
V/RegulatoryObserver(  905): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  905): Regulatory Country Code:DE
D/wpa_supplicant( 3951): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 3951): wpa_supplicant_scan enter
I/wpa_supplicant( 3951): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3951): ap_scan=1 , scan_req =1
I/wpa_supplicant( 3951): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 3951): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 3951): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_905-2
D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3951): nl80211: Event message available
D/wpa_supplicant( 3951): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 3951): nl80211: Regulatory domain change
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3951): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3951): nl80211: 2400-2483 @ 40 MHz
D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 1
D/wpa_supplicant( 3951): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3951): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3951): P2P: Add operating class 81
D/wpa_supplicant( 3951): P2P: Add operating class 115
D/wpa_supplicant( 3951): P2P: Add operating class 116
D/wpa_supplicant( 3951): P2P: Add operating class 117
D/wpa_supplicant( 3951): P2P: Update channel list
D/wpa_supplicant( 3951): p2p0: Updating hw mode
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 95
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3951): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3951): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3951): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3951): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3951): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3951): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): set wifi ON
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER MACADDR
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
V/RegulatoryObserver(  905): Start wifi-crda service to run crda.
V/RegulatoryObserver(  905): Country Code is DE
V/RegulatoryObserver(  905): Send broadcast country code message.
I/RegulatoryObserver(  905): Broadcast intent for crda country code: DE
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiConfigStore(  905): Loading config and enabling all networks
D/WifiNative-wlan0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): list_network_info: ret=0x1, pos=0xb8555117 buf=0xb85550e8
I/wpa_supplicant( 3951): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3951): 0	NG700	any	
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WifiNative-wlan0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  905): 0	NG700	any	
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 bssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 priority
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='priority'
I/IntentController( 1108): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/HtcWiFiWidget_WiFiWidgetProvider( 3982): onWiFiStateChanged() for widget: 
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/HtcWiFiWidget_WiFiWidgetProvider( 3982): updateWidget(context) for widget: 
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 3951): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 proto
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WIFI_ICON( 1108): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/WifiConfigStore(  905): Failed to look-up a string: W
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 group
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 limited
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 eap
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 phase2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 password
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 private_key
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,D/wpa_supplicant( 3951): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  905): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  905): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 3951): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3951): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET manufacturer HTC
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 3951): manufacturer='HTC'
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 3951): model_name='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 3951): model_number='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
,D/wpa_supplicant( 3951): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 3951): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET auto_interworking 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 3951): auto_interworking=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXSCAN-STOP
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): SET_SCREEN_ON:On
I/wpa_supplicant( 3951): htc_wext_set_keepalive +
I/wpa_supplicant( 3951): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3951): getPrivFuncNum +	
I/wpa_supplicant( 3951): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3951): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3951): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3951): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3951): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET ps 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 3951): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
W/Settings(  905): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  905): doBoolean: CTRL-DAT-AIR_MODE-0:1
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): SETBAND: 0
D/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 3951): P2P: Add operating class 81
D/wpa_supplicant( 3951): P2P: Add operating class 115
D/wpa_supplicant( 3951): P2P: Add operating class 116
D/wpa_supplicant( 3951): P2P: Add operating class 117
,D/wpa_supplicant( 3951): P2P: Update channel list
I/wpa_supplicant( 3951): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 3951): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3951): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 3951): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 3951): p2p_oper_reg_class=126
D/wpa_supplicant( 3951): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3951): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 3951): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3951): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 3951): p2p_oper_channel=36
E/wpa_supplicant( 3951): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3951): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
,D/wpa_supplicant( 3951): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 3951): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 3951): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: BSS_FLUSH 0
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
D/WifiMonitor(  905): startMonitoring(p2p0) with mConnected = true
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 3951): wpa_supplicant_scan enter
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 3951): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 3951): persistent_reconnect=1
I/wpa_supplicant( 3951): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_name Android_1950
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 3951): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 3951): device_name='Android_1950'
I/wpa_supplicant( 3951): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 3951): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 3951): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 3951): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 3951): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 3951): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 3951): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiP2pService(  905): P2pEnablingState
D/WifiP2pService(  905): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2p socket connection successful
D/WifiStateMachine(  905): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  905): P2pEnabledState
D/WifiP2pService(  905): sending p2p connection changed broadcast
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  905): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  905): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 3951): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3951): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 3951): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 3951): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 3951): Single channel concurrency preference: sta
I/wpa_supplicant( 3951): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  905): doBoolean: P2P_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 3951): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 3951): P2P: Stopping find
D/wpa_supplicant( 3951): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 3951): P2P: State IDLE -> IDLE
I/wpa_supplicant( 3951): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
,I/wpa_supplicant( 3951): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 3951): Recv Cmd 2: P2P_SERVICE_FLUSH
I/QuickSettingWifi( 1108): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 3951): list_network_info: ret=0x22, pos=0xb855510a buf=0xb85550e8
I/wpa_supplicant( 3951): list_network_info: buf=network id / ssid / bssid / flags
,I/wpa_supplicant( 3951): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  905): doBoolean: AP_SCAN 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "AP_SCAN 1"
,D/WifiNative-p2p0(  905):    returned false
,D/WifiNative-p2p0(  905): doBoolean: SET wifi_display 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 3951): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 3951): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 3951): WFD: Update WFD IE
I/wpa_supplicant( 3951): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3951): Recv Cmd 2: SET wifi_display
,D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  905): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 3951): WFD: Set subelement 0
D/wpa_supplicant( 3951): WFD: Update WFD IE
I/wpa_supplicant( 3951): WFD: Update WFD IE - DONE
,I/wpa_supplicant( 3951): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  905):    returned true
,D/WifiP2pService(  905): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  905):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  905):  primary type: 10-0050F204-5
D/WifiDisplayController(  905):  secondary type: null
D/WifiDisplayController(  905):  wps: 0
D/WifiDisplayController(  905):  grpcapab: 0
D/WifiDisplayController(  905):  devcapab: 0
D/WifiDisplayController(  905):  status: 3
D/WifiDisplayController(  905):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  905):  WFD CtrlPort: 0
D/WifiDisplayController(  905):  WFD MaxThroughput: 0
D/WifiP2pService(  905): sending p2p persistent groups changed broadcast
D/WifiP2pService(  905): InactiveState
D/WifiP2pService(  905): InactiveState{ when=-10ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-10ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDisplayController(  905): Successfully set WFD info.
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
V/AudioService(  905): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  905):     Client/Owner: Client
V/AudioService(  905):     GroupId: 
V/AudioService(  905):     Passphrase: 
V/AudioService(  905):     SessionId: 0
V/AudioService(  905):     IP Address: }
D/HtcEffectManagerBase(  905): onEventChanged id=5 status=false
,D/HtcEffectManager(  905): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  905): convertEffect before=902
,D/HtcEffectManager(  905): convertEffect after=902
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  905):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  905):  primary type: 10-0050F204-5
D/WifiDisplayController(  905):  secondary type: null
D/WifiDisplayController(  905):  wps: 0
D/WifiDisplayController(  905):  grpcapab: 0
D/WifiDisplayController(  905):  devcapab: 0
D/WifiDisplayController(  905):  status: 3
D/WifiDisplayController(  905):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  905):  WFD CtrlPort: 7236
D/WifiDisplayController(  905):  WFD MaxThroughput: 50
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 3951): nl80211: Event message available
D/wpa_supplicant( 3951): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 3951): Got an original EVENT_SCAN_RESULTS,
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3951): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 3951): nl80211: Survey data missing
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3951): Sorted scan results
I/wpa_supplicant( 3951): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 3951): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 3951): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 3951): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 3951): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 3951): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 3951): Add randomness: count=2 entropy=0
D/wpa_supplicant( 3951): Add randomness: count=3 entropy=1
D/wpa_supplicant( 3951): Add randomness: count=4 entropy=2
D/wpa_supplicant( 3951): Add randomness: count=5 entropy=3
D/wpa_supplicant( 3951): Add randomness: count=6 entropy=4
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 3951): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3951): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3951): wpa_supplicant_pick_network+
I/wpa_supplicant( 3951): Selecting BSS from priority group 1
I/wpa_supplicant( 3951): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3951): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3951): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 3951): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 3951): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 3951):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 3951):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 3951): Start print parameters
I/wpa_supplicant( 3951): wpa_s->wpa_state is 3
I/wpa_supplicant( 3951): wpa_s->br_have_IP is 0
I/wpa_supplicant( 3951): isConcurrentMode() is 0
I/wpa_supplicant( 3951): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 3951): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 3951): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 3951): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 3951): wpa_s->reassociate is 0
I/wpa_supplicant( 3951): wpa_s->is_screen_on 1
I/wpa_supplicant( 3951): wpa_s->ifname wlan0
I/wpa_supplicant( 3951): End print parameters
I/wpa_supplicant( 3951): selected network = 2
D/wpa_supplicant( 3951): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85534e8  current_ssid=0x0
D/wpa_supplicant( 3951): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3951): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 3951): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 3951): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 3951): check if in concurrent case
I/wpa_supplicant( 3951): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 3951): wpa_supplicant_associate, 1777
D/wpa_supplicant( 3951): wpa_supplicant_associate, 1780
D/wpa_supplicant( 3951): wpa_supplicant_associate, 1795
D/wpa_supplicant( 3951): RSN: PMKSA cache search - network_ctx=0xb85534e8 try_opportunistic=0
D/wpa_supplicant( 3951): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3951): RSN: No PMKSA cache entry found
I/wpa_supplicant( 3951): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3951): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3951): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 3951): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3951): nl80211: Unsubscribe mgmt frames handle 0xb8552718 (mode change)
D/wpa_supplicant( 3951): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8552718
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951),: nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Register frame type=0xd0 nl_handle=0xb8552718
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3951): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 3951):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3951):   * freq=2412
D/wpa_supplicant( 3951):   * Auth Type 0
D/wpa_supplicant( 3951):   * WPA Versions 0x2
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 3951): nl80211: Connect request send successfully
D/wpa_supplicant( 3951): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3951): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 3951): reply (632) for get BSS: id=0
I/wpa_supplicant( 3951): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3951): freq=5220
I/wpa_supplicant( 3951): level=-51
I/wpa_supplicant( 3951): tsf=0000000108381911
I/wpa_supplicant( 3951): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3951): ssid=NG7005g
I/wpa_supplicant( 3951): ====
I/wpa_supplicant( 3951): id=1
I/wpa_supplicant( 3951): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 3951): freq=2412
I/wpa_supplicant( 3951): level=-54
I/wpa_supplicant( 3951): tsf=0000000108381936
I/wpa_supplicant( 3951): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 3951): ssid=01ABC
I/wpa_supplicant( 3951): ====
I/wpa_supplicant( 3951): id=2
I/wpa_supplicant( 3951): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3951): freq=2412
I/wpa_supplicant( 3951): level=-54
I/wpa_supplicant( 3951): tsf=0000000108381946
I/wpa_supplicant( 3951): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3951): ssid=NG700
I/wpa_supplicant( 3951): ====
I/wpa_supplicant( 3951): id=3
I/wpa_supplicant( 3951): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 3951): freq=2427
I/wpa_supplicant( 3951): level=-76
I/wpa_supplicant( 3951): tsf=0000000108381957
I/wpa_supplicant( 3951): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 3951): ssid=Gonzos
I/wpa_supplicant( 3951): ====
I/wpa_supplicant( 3951): id=4
I/wpa_supplicant( 3951): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 3951): freq=2462
I/wpa_supplicant( 3951): level=-91
I/wpa_supplicant( 3951): tsf=0000000108381968
I/wpa_supplicant( 3951): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 3951): ssid=UPC Wi-Free
I/wpa_supplicant( 3951): ####
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/wpa_supplicant( 3951): EAPOL: disable timer tick
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 108381911, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 108381936, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 108381946, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 108381957, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1200): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 108381968, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3951): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3951): nl80211: Event message available
D/wpa_supplicant( 3951): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 3951): nl80211: Connect event
D/wpa_supplicant( 3951): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 3951): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3951): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 3951): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3951): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3951): Add randomness: count=7 entropy=5
I/wpa_supplicant( 3951): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 3951): TDLS: Remove peers on association
D/wpa_supplicant( 3951): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3951): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 3951): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 3951): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 3951): htc_wext_set_keepalive +
I/wpa_supplicant( 3951): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 3951): getPrivFuncNum +	
I/wpa_supplicant( 3951): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3951): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3951): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3951): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 3951): Get randomness: len=32 entropy=6
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Associated
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,I/bt-btu  ( 3891): btu_task received preload complete event
,D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/bt-btm  ( 3891): btm_acl_device_down
D/bt-btm  ( 3891): btm_acl_reset_paging
,D/bt-btm  ( 3891): btm_acl_set_discing
,D/Tethering(  905): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3951): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85529f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 3951):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  905): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 3951): EAPOL: External notification - portValid=1
I/wpa_supplicant( 3951): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/wpa_supplicant( 3951): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fc2b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 3951):    broadcast key
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 3951): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 3951): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3951): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3951): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 3951): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 3951): wlan0: Connect to SSID: NG700
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/wpa_supplicant( 3951): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 3951): netlink: Operstate: linkmode=-1, operstate=6,
,I/wpa_supplicant( 3951): set send_ind_to_ndc = 0
I/wpa_supplicant( 3951): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3951): htc_wext_set_TX_TRACKING - ret = 0,
D/wpa_supplicant( 3951): EAPOL: External notification - portValid=1
D/wpa_supplicant( 3951): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 3951): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 3951): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 3951): EAP: EAP entering state DISABLED,
D/wpa_supplicant( 3951): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 3951): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 3951): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3951): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 3951): EAPOL authentication completed successfully
I/wpa_supplicant( 3951): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...,
,I/bt-btm  ( 3891): btm_reset_complete
,I/bt-btm  ( 3891): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3891): Start reading local supported commands
,D/bt-btm  ( 3891): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3891): BTM reads next extended features page (1)
,D/bt-btm  ( 3891): BTM reads next extended features page (2)
D/bt-btm  ( 3891): BTM reached last extended features page (2)
,D/bt-btm  ( 3891): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/bt-btm  ( 3891): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3891): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,D/bt-btm  ( 3891): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3891): btm_read_ble_wl_size 
D/bt-btm  ( 3891): btm_read_white_list_size_complete 
,D/bt-btm  ( 3891): btm_get_ble_buffer_size 
D/bt-btm  ( 3891): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3891): btm_read_ble_local_supported_features 
D/bt-btm  ( 3891): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3891): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3891): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3891): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3891): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3891): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3891): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3891):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3891): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3891): BTM_SetInquiryMode
I/bt-btm  ( 3891): BTM_SetPageScanType
I/bt-btm  ( 3891): BTM_SetInquiryScanType
D/bt-btm  ( 3891): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3891): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3891): BTM_BleLoadLocalKeys
D/bt-btm  ( 3891): BTM_BleLoadLocalKeys
I/bt-btm  ( 3891): BTM_Sec: application registered
E/bt-btm  ( 3891): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fc3941 
I/bt-btm  ( 3891): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3891): SMP_Register state=0
E/bt-btm  ( 3891): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fc3941 
I/bt-btm  ( 3891): BTM_Sec: application registered
D/bt-btm  ( 3891): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3891): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3891): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3891): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3891): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3891): BTM_RegBusyLevelNotif
I/bt-att  ( 3891): GATT_Register
D/bt-att  ( 3891): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3891): allocated gatt_if=3
I/bt-att  ( 3891): GATT_StartIf gatt_if=3
D/bt-att  ( 3891): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3891): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btm  ( 3891): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3891): BTM_AllocateSCN
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3891): BTM_AllocateSCN
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btm  ( 3891): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3891):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3891):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3891):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3891):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3891):                : sec: 0x2090, service name [] (up to 21 chars saved)
,I/bt-btm  ( 3891): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3891):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3891):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3891):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3891): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3891): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
D/bt-avp  ( 3891): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3891): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
E/bt-btif ( 3891): Write Extended Inqui
I/bt-btm  ( 3891): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3891):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: b0:c5:59:3f:75:69
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3891): GATT_Register
D/bt-att  ( 3891): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3891): allocated gatt_if=4
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0,
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3891): GATT_StartIf gatt_if=4
D/bt-att  ( 3891): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3891): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3891): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3891): BTM_GetHCIConnHandle
I/bt-btm  ( 3891): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 3891): btif_storage_get_adapter_property se
E/bt-btif ( 3891): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3891): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3891): Address is:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:1 len:14
I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:7 len:4
D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/BluetoothAdapterProperties( 3891): Scan Mode:20
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3891): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:8 len:60
D/BluetoothAdapter( 3891): getBluetoothService(): entry
D/BluetoothAdapter( 3891): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3891): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b77a40
D/BluetoothDevice( 3891): getService : Register callback
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
D/BluetoothAdapterProperties( 3891): Adding bonded device:B0:C5:59:3F:75:69
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/BluetoothAdapterProperties( 3891): Adding bonded device:7C:F9:0E:51:18:22
D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/BluetoothAdapterProperties( 3891): Adding bonded device:80:01:84:8A:B3:68
D/BluetoothAdapterProperties( 3891): Adding bonded device:F4:F1:E1:5C:3B:E2
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/BluetoothAdapterProperties( 3891): Adding bonded device:14:B4:84:21:3B:49
D/BluetoothAdapterProperties( 3891): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 3891): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3891): Adding bonded device:90:E7:C4:F6:69:77
D/BluetoothAdapterProperties( 3891): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 3891): Adding bonded device:38:94:96:B5:06:DC
I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
D/WISPrService( 3274): >>>>>WISPrService start isConnected = false<<<<<
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
D/WISPrService( 3274): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  905): New client listening to asynchronous messages
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
,I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
D/WifiStateMachine(  905): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): WiFioffload: update mobile network = Unknown
D/WifiNative-wlan0(  905):    returned true
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): Power_Mode_Type mode = 1
I/wpa_supplicant( 3951): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  905):    returned null
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(425bd218): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@44121cb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@44121cb0 target=com.android.internal.util.StateMachine$SmHandler }
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
I/QuickSettingWifi( 1108): receive.wifiConnect:false wifiAPname:null elapse:1
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BluetoothRemoteDevices( 3891): Remote class is:5898764
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
I/bt-btif ( 3891): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3891): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
D/BluetoothRemoteDevices( 3891): Remote class is:5898764
I/bt-btif ( 3891): BTA_JvEnable
I/bt-btm  ( 3891): BTM_ReadConnectability
I/bt-btm  ( 3891): BTM_ReadDiscoverability
I/bt-btm  ( 3891): BTM_SetDiscoverability
I/bt-btm  ( 3891): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3891): br_edr_supported=0x2
I/bt-btm  ( 3891): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3891): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3891): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3891): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3891): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3891): BTM_SetConnectability
I/bt-btm  ( 3891): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3891): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3891): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3891): BTM_SetDiscoverability
I/bt-btm  ( 3891): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3891): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3891): br_edr_supported=0x0
I/bt-btm  ( 3891): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3891): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3891): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3891): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3891): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3891): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3891): BTM_SetConnectability
I/bt-btm  ( 3891): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3891): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3891): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3891): bta_pan_co_init
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3891): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3891):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3891):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3891): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3891):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3891): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3891):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btif ( 3891): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3891): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3891): ScanMode =  20
D/BluetoothAdapterProperties( 3891): State =  11
I/bt-btif ( 3891): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3891): Setting state to 12
I/BluetoothAdapterState( 3891): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterService( 3891): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=11 new=12
I/bt-btm  ( 3891): BTM_SetDiscoverability
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/bt-btm  ( 3891): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3891): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3891): br_edr_supported=0x0
I/bt-btm  ( 3891): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3891): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3891): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3891): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3891): evt_type=0x3 p-cb->evt_type=0x3 
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/bt-btm  ( 3891): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3891): BTM_SetConnectability
I/bt-btm  ( 3891): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3891): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3891): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3891): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3891): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3891): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothAdapterProperties( 3891): Scan Mode:21
I/bt-btif ( 3891): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3891): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3891): Discoverable Timeout:120
D/BluetoothHeadset( 1108): onBluetoothStateChange: up=true
E/bt_mct  ( 3891): hci lib postload completed
I/BluetoothAdapterState( 3891): Entering On State
D/BluetoothAdapterService(1102254672)( 3891): Get Bonded Devices being called
D/BluetoothHeadset( 1216): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3891): getBondedDevices: length=10
D/BluetoothHeadset( 1108): Proxy object connected
D/BluetoothHeadset( 1216): Proxy object connected
D/BluetoothHeadset( 1216): onBluetoothStateChange: up=true
I/QuickSettingMiniLite( 1108): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e2d888
D/BluetoothPhoneService( 1216): BluetoothHeadset onServiceConnected
D/BluetoothPan(  905): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1216): Proxy object connected
D/BluetoothA2dp(  905): onBluetoothStateChange: up=true
D/BluetoothPan(  905): BluetoothPAN Proxy object connected
D/BluetoothAdapter( 1216): 1103608672: getState(). Returning 12
D/BluetoothHeadset(  905): onBluetoothStateChange: up=true
D/BluetoothManagerService(  905): Bluetooth State Change Intent: 11 -> 12
D/BluetoothHeadset(  905): Proxy object connected
,I/IntentController( 1108): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothAdapter(  905): 1112021512: getState(). Returning 12
D/BluetoothAdapter( 1200): 1105324672: getState(). Returning 12
V/BluetoothPbapReceiver( 3891): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(1102254672)( 3891): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3891): getBondedDevices: length=10
V/BluetoothPbapReceiver( 3891): ***********state = 12
D/BluetoothAdapter( 1200): getBluetoothService(): entry
D/BluetoothAdapterService(1102254672)( 3891): Get Bonded Devices being called
D/BluetoothAdapter( 1200): getBluetoothService(): callingUser = 0 callingUid = 10029 callingAppId = 10029
D/BluetoothAdapterProperties( 3891): getBondedDevices: length=10
D/BluetoothA2dp(  905): Proxy object connected
D/BluetoothAdapter( 1200): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b9b490
D/BluetoothDevice( 1200): getService : Register callback
D/BluetoothAdapter(  905): 1112021512: getState(). Returning 12
D/PMS     (  905): acquireWL(438e49a0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1200 10029 null
D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMasReceiver( 3891): Bluetooth STATE CHANGED to 12
V/BluetoothSapReceiver( 3891): SapReceiver onReceive 
V/BluetoothSapReceiver( 3891): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3891):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3891): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 12
D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 12
D/HtcBtWidget_BTWidgetProvider( 3918): onBTStateChanged() for widget: 
V/BluetoothMasService( 3891): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3891): Manager Instance is not NULL
D/PMS     (  905): acquireWL(43b5caa0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3274 1000 null
W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  905): releaseWL(43b5caa0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  905): acquireWL(44145430): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3274 1000 null
D/HtcBtWidget_BTWidgetProvider( 3918): updateWidget(context) for widget: 
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@438eb7a0:true
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3274): new LocationAgent instance!!
D/EmailUtils( 3891): ============NULL aList========
V/EmailUtils( 3891): <-getEmailAccountIdList
V/BluetoothSapService( 3891): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3891): state: 12
D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 12
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/HtcTagManager( 3274): HtcTagManager construction complete
W/ContextImpl( 3891): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 3891): Starting SAP server process
V/BluetoothPbapService( 3891): Handler(): got msg=1
V/BluetoothPbapService( 3891): Pbap Service startRfcommSocketListener
V/BluetoothMasService( 3891): handleMessage: mIsEmailEnabledtrue
V/BluetoothPbapService( 3891): Pbap Service initSocket
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtMns   ( 3891): BluetoothMns: isEmailEnabled: true
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
D/BluetoothAdapter( 3891): getBluetoothService(): entry
D/BluetoothMasService( 3891): Map_prev 1
D/BluetoothInputDevice( 3274): BluetoothInputDevice()
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 7
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
D/BluetoothInputDevice( 3274): BluetoothInputDevice(): Binding service...
W/BluetoothAdapter( 3891): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothServiceJni( 3891): SOCK FLAG = 1 ***********************
I/bt-btif ( 3891): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btif ( 3891): BTA_JvRfcommStartServer
I/bt-btm  ( 3891): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
,I/bt-btm  ( 3891):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3891): getBluetoothService(): entry
V/BluetoothPbapService( 3891): Succeed to create listening socket 
V/BluetoothPbapService( 3891): Accepting socket connection...
,W/BluetoothAdapter( 3891): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPan( 3274): BluetoothPan()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
E/BluetoothServiceJni( 3891): SOCK FLAG = 3 ***********************
I/bt-btif ( 3891): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:12
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 8
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btif ( 3891): BTA_JvRfcommStartServer
I/bt-btm  ( 3891): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3891):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
,D/BluetoothPan( 3274): BluetoothPan(): Binding service...
W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 1108): 1104974168: getState(). Returning 12
,D/BluetoothAdapter( 3891): getBluetoothService(): entry
W/BluetoothAdapter( 3891): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 1108): 1104974168: getState(). Returning 12
,D/BluetoothMap( 3274): Create BluetoothMap proxy object
,D/BluetoothManagerService(  905): registerStateChangeCallback+
E/BluetoothServiceJni( 3891): SOCK FLAG = 3 ***********************
I/bt-btif ( 3891): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btif ( 3891): BTA_JvRfcommStartServer
I/bt-btm  ( 3891): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3891):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
I/QuickSettingBluetooth( 1108): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1108): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothManagerService(  905): Registered receivers: 9
,E/BluetoothMap( 3274): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothSap( 3274): BluetoothSap() call bindService
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,D/BluetoothManagerService(  905): Registered receivers: 10
,D/BluetoothPbap( 3274): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 11
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
,D/BluetoothPbap( 3274): BluetoothPbap(): Binding service...
W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothA2dp( 3274): BluetoothA2dp()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 12
,D/BluetoothSapService( 3891): Sap_prev 1
V/BluetoothSapService( 3891): SAP Service startRfcommListenerThread
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
,D/BluetoothA2dp( 3274): BluetoothA2dp(): Binding service...
,V/BluetoothSapService( 3891): Sap Service initRfcommSocket
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothAdapter( 3891): getBluetoothService(): entry
W/BluetoothAdapter( 3891): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothHeadset( 3274): BluetoothHeadset()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 13
E/BluetoothServiceJni( 3891): SOCK FLAG = 3 ***********************
I/bt-btif ( 3891): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btif ( 3891): BTA_JvRfcommStartServer
I/bt-btm  ( 3891): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3891):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3891): Succeed to create listening socket 
V/BluetoothSapService( 3891): Accepting socket connection...
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
,D/BluetoothHeadset( 3274): BluetoothHeadset(): Binding service...
,W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
V/TAG     ( 3891): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3891): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b6e290
D/BluetoothAdapter( 1108): 1104974168: getState(). Returning 12
,D/HtcTagManager( 3274): startProxy
,W/ContextImpl( 3274): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,I/QuickSettingMiniLite( 1108): updateLiteState:no connect device!
,V/BluetoothPbapService( 3891): Pbap Service onBind
,W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3274): LocalBluetoothProfileManager construction complete
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/DockEventReceiver( 3274): finishStartingService: stopping service
D/BluetoothPan( 3274): BluetoothPAN Proxy object connected
D/PanProfile( 3274): Bluetooth service connected
D/BluetoothInputDevice( 3274): Proxy object connected
D/HidProfile( 3274): Bluetooth service connected
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
I/BluetoothFtpService( 3891): Ftp Service onCreate
D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 12
D/BluetoothA2dp( 3274): Proxy object connected
D/A2dpProfile( 3274): Bluetooth service connected
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothMasReceiver( 3891): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3891): getBluetoothService(): entry
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
D/BluetoothFtpService( 3891): Ftp_prev 1
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3958): onCreate: going to find gatt base service first.
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3891): getBluetoothService(): entry
W/BluetoothAdapter( 3891): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3891): SOCK FLAG = 1 ***********************
I/bt-btif ( 3891): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btif ( 3891): BTA_JvRfcommStartServer
I/bt-btm  ( 3891): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3891):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3891): Run Accept thread
D/BluetoothAdapter( 3891): 1102272848: getState(). Returning 12
V/BluetoothMasService( 3891): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3891): Manager Instance is not NULL
W/BluetoothAdapter( 3891): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3891): SOCK FLAG = 0 ***********************
I/bt-btif ( 3891): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3891): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3891): Write Extended Inquiry Response to controller
I/bt-btif ( 3891): BTA_JvRfcommStartServer
I/bt-btm  ( 3891): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3891):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3891): Accept thread started.
D/BluetoothHeadset( 3274): Proxy object connected
D/HeadsetProfile( 3274): Bluetooth service connected
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/wpa_supplicant( 3951): EAPOL: startWhen --> 0
D/wpa_supplicant( 3951): EAPOL: disable timer tick
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44030798:true
D/BluetoothAdapter( 3274): 1103857896: getState(). Returning 12
D/[HTC,_BLE][Constants]( 3958):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3958):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3958):  + discoverServicesOnBonded = false
D/EmailUtils( 3891): ============NULL aList========
V/EmailUtils( 3891): <-getEmailAccountIdList
D/BluetoothMasService( 3891): Map_prev 1
D/SapServerProfile( 3274): Bluetooth service connected
D/BluetoothPbap( 3274): Proxy object connected
D/PbapServerProfile( 3274): Bluetooth service connected
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/PMS     (  905): releaseWL(44145430): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3958):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3958): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b371a0
D/[HTC_BLE][Constants]( 3958): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3958): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3958): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3958): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3958): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 3958): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3958): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3274): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3958): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3958): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3958): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b371a0
D/HtcTagProfile( 3274): setup proxy
D/HtcPxpProfile( 3274): setup proxy
,D/HtcFmpProfile( 3274): setup proxy
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3958): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b371a0
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3958): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b371a0, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b42b58
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3958): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b371a0
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43b62968:true
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3801): new LocationAgent instance!!
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,D/HtcTagManager( 3801): HtcTagManager construction complete
,D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
,D/BluetoothInputDevice( 3801): BluetoothInputDevice()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 14
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
,D/BluetoothInputDevice( 3801): BluetoothInputDevice(): Binding service...
,D/RingtoneManager( 3958): getExternalStorageState=mounted
,D/BluetoothPan( 3801): BluetoothPan()
,W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 15
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
,D/BluetoothPan( 3801): BluetoothPan(): Binding service...
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,D/BluetoothMap( 3801): Create BluetoothMap proxy object
V/LightsService(  905): setLight #0: color=#26
,W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[-1]: Crocus
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[0]: Crocus
D/BluetoothManagerService(  905): Registered receivers: 16
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[5]: Hangouts Message
E/BluetoothMap( 3801): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[11]: Thalia
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3958):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothSap( 3801): BluetoothSap() call bindService
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 17
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3958): BleProfilesStateMachine is initialized...
,D/BluetoothPbap( 3801): BluetoothPbap()
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3958): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3958): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3958): initScanModeInterface: true
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 18
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/BluetoothPbap( 3801): BluetoothPbap(): Binding service...
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42330058:true
,W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3958): loadDeviceConfiguration() init =true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3958):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE][Constants]( 3958):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3958):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 3958):  + discoverServicesOnBonded = false
,D/BluetoothA2dp( 3801): BluetoothA2dp()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 19
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
,D/BluetoothA2dp( 3801): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3801): BluetoothHeadset()
W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 20
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3958): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b42b58
,D/BluetoothHeadset( 3801): BluetoothHeadset(): Binding service...
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,D/HtcTagManager( 3801): startProxy
,W/ContextImpl( 3801): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3801): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
,V/LightsService(  905): setLight #0: color=#22
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/LocalBluetoothProfileManager( 3801): setBluetoothStateOn
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/HtcTagManager( 3801): startProxy
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/BluetoothAdapterService(1102254672)( 3891): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3891): getBondedDevices: length=10
D/BluetoothAdapter( 3801): getBluetoothService(): entry
D/BluetoothAdapter( 3801): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3801): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b718a8
D/BluetoothDevice( 3801): getService : Register callback
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/HtcTagManager( 3801): addHtcTagProfiles
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,V/LightsService(  905): setLight #0: color=#1c
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/HtcTagManager( 3801): addHtcTagProfiles
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/HtcTagManager( 3801): addHtcTagProfiles
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/HtcTagManager( 3801): addHtcTagProfiles
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/HtcTagManager( 3801): addHtcTagProfiles
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/HtcTagManager( 3801): addHtcTagProfiles
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
,D/HtcTagManager( 3801): addHtcTagProfiles
,V/LightsService(  905): setLight #0: color=#15
D/BluetoothAdapter( 1200): 1105324672: getState(). Returning 12
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
D/BluetoothAdapterService(1102254672)( 3891): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3891): getBondedDevices: length=10
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/HtcTagManager( 3801): addHtcTagProfiles
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/HtcTagManager( 3801): addHtcTagProfiles
E/BluetoothDevice( 3801): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/HtcTagManager( 3801): addHtcTagProfiles
D/BluetoothInputDevice( 3801): Proxy object connected
D/HidProfile( 3801): Bluetooth service connected
D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
D/AuthorizationBluetoothService( 1347): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1347): Proximity feature is not enabled.
D/BluetoothPan( 3801): BluetoothPAN Proxy object connected
E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/PanProfile( 3801): Bluetooth service connected
D/SapServerProfile( 3801): Bluetooth service connected
D/BluetoothPbap( 3801): Proxy object connected
D/PbapServerProfile( 3801): Bluetooth service connected
D/BluetoothA2dp( 3801): Proxy object connected
D/A2dpProfile( 3801): Bluetooth service connected
,D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
,D/BluetoothHeadset( 3801): Proxy object connected
,D/HeadsetProfile( 3801): Bluetooth service connected
,D/BluetoothAdapter( 3801): 1102283184: getState(). Returning 12
,V/LightsService(  905): setLight #0: color=#14
D/HtcTagManager( 3801): onServiceConnected
D/HtcTagProfile( 3801): setup proxy
D/HtcPxpProfile( 3801): setup proxy
D/HtcFmpProfile( 3801): setup proxy
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1200): getBluetoothClass(): COD is 5898764
D/PMS     (  905): releaseWL(438e49a0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): Power_Mode_Type mode = 0
,I/wpa_supplicant( 3951): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2",
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler },
D/PMS     (  905): releaseWL(425bd218): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!,
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72,
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3951): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 3951): WiFi gateway: 0x101a8c0
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19342 delay=15s
,V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiWatchdogStateMachine(  905): WAN detection
,D/WISPrService( 3274): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
,D/MDST    (  905): default: setTeardownRequested(true)
,D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@42487608
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
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
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
I/QuickSettingWifi( 1108): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(4330fae8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4330fae8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WIFI_ICON( 1108): WifiActivity: 3
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/CaptivePortalTracker(  905): NoActiveNetworkState
V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43132220): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/ConnectivityHelper( 1245): [onReceive] WIFI(1): CONNECTED
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/libc    (  363): [NET] +++++ res_nsend xid =bfb8 +++++
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/libc    (  363): [NET] NOT IN CACHE
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  905): Found interface wlan0
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3325): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1245/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1535/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3347/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3325/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43b87ff0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/,WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 110
D/libc    (  363): [NET]res_nsend:resplen=104
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
,D/PMS     (  905): acquireWL(432fc6e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(4417f390): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4078 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  905): acquireWL(42f5b478): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10029}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
D/PMS     (  905): releaseWL(4417f390): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2165/10021)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4093 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/PMS     (  905): acquireWL(42679e60): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
,I/IntentController( 1108): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1523): [EventService] EVENT_RESET_THEME_TIMESTAMP
,I/FeedActionBar( 1245): updateLastUpdatedTime(in String) LAST UPDATED 15:25
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/PMS     (  905): releaseWL(43b87ff0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/DotMatrix( 1523): [EventService] isTheSameDay:false,timestamp is early than today:true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): WiFioffload: SignalStrength: =97
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  905):    returned true
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43af32a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43af32a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42627af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42627af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4247dca0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  905): NTP server returned: 1449671238403 (Wed Dec 09 15:27:18 CET 2015) reference: 111432 certainty: 15 system time offset: -211
D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME_FINISHED
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(4247dca0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): releaseWL(43132220): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4238b020): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,W/dalvikvm( 1958): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/DelayedSyncController( 4078): Delaying sync.
D/PMS     (  905): releaseWL(4238b020): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(41b5af30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(42679e60): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/ACRA    ( 4093): ACRA is enabled for com.facebook.katana, intializing...
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ACRA    ( 4093): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/ACRA    ( 4093): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(41e53650): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
,D/PMS     (  905): releaseWL(41b5af30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4242d808): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/jxcore-log( 3846): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3846): 
,E/Auth.Api.Credentials( 1958): [CredentialSyncAdapter] Unknown sync event.
,W/SystemClassLoaderAdder( 4093): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,D/DelayedSyncController( 4078): Delaying sync.
,V/DexLibLoader( 4093): Preparing secondary program dexes.
V/DexLibLoader( 4093): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4093): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4093): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4093): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4093): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4093): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
D/PMS     (  905): releaseWL(4242d808): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(41ec65c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(41e53650): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/DexLibLoader( 4093): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4093): Dex already copied
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/OdexVerifier( 4093): Odex verification is skipped.
,V/DexLibLoader( 4093): Creating class loader
,D/PMS     (  905): releaseWL(41ec65c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
V/DexLibLoader( 4093): Finished creating class loader
V/DexLibLoader( 4093): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4093): Dex already copied
D/OdexVerifier( 4093): Odex verification is skipped.
V/DexLibLoader( 4093): Creating class loader
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4093): Finished creating class loader
V/DexLibLoader( 4093): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4093): Dex already copied
D/OdexVerifier( 4093): Odex verification is skipped.
V/DexLibLoader( 4093): Creating class loader
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4093): Finished creating class loader
V/DexLibLoader( 4093): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4093): Dex already copied
D/OdexVerifier( 4093): Odex verification is skipped.
V/DexLibLoader( 4093): Creating class loader
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4093): Finished creating class loader
V/DexLibLoader( 4093): Verifying classes from secondary dexes.
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/DexLibLoader( 4093): DexLibLoader.ensureDexLoaded took 131 ms
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4301f768): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(432fc6e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1108): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): acquireWL(433db7b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
D/PMS     (  905): releaseWL(4301f768): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(425b3250): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(425b3250): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PhoneStatusBar( 1108): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,W/DriveInitializer( 1958): Awaiting to be initialized
,W/DriveInitializer( 1958): Background init thread started
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 1958): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,W/DriveInitializer( 1958): Background init thread ended
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(438f2b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(433db7b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(438f2b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  905): acquireWL(440b0730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42f5b478): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  905): acquireWL(43783f00): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10029}
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(440b0730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4267ec48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4267ec48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43ae9f90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43783f00): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  905): releaseWL(43ae9f90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1108): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/PhoneStatusBar( 1108): removeIcon slot=sync_active index=7 viewIndex=0
,E/BTIF_CORE( 3891): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3891): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3891): Wake lock released
,W/dalvikvm( 4093): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4093): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4093): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4093): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4093): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4093): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4093): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4093): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4093): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4093): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e0bc +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/WIFI_ICON( 1108): WifiActivity: 2
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,W/fb4a(:<default>):StaticBindingVerifier( 4093): Verify
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.59.123.86
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4093): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4093): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4093): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  905): Disable JIT of com.htc.bgp
,D/Process (  905): killProcessQuiet, pid=1295
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4136 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
I/ActivityManager(  905): Killing 1295:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,I/CalendarProvider2( 4136): Created com.android.providers.calendar.CalendarAlarmManager@41b5c968(com.android.providers.calendar.HtcCalendarProvider@41b44cf0)
,D/CalendarProvider2( 4136): wait start:true
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarProvider2( 4136): wait end:false
I/ActivityManager(  905): Recipient 1295
,I/ActivityManager(  905): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4153 uid=10055 gids={50055, 1023, 3003, 5012}
W/fb4a(:<default>):UserScope( 4093): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 4093): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4093): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4093): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 4093): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4093): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4093): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4093): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4093): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4093): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4093): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4093): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4093): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4093): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4093): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4093): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4093): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4093): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4093): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4093): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4093): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4093): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/PluginProvider( 4153): PluginProvider onCreate
,D/PluginProvider( 4153): current plugin count: 18
,D/HtcAppUPService( 4153): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4093): Grow heap (frag case) to 9.927MB for 39954-byte allocation
,I/dalvikvm-heap( 4093): Grow heap (frag case) to 10.002MB for 79892-byte allocation
,D/AutoSetting( 4153): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/Process (  905): killProcessQuiet, pid=3450
I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4170 uid=10079 gids={50079, 3003, 5012}
,I/ActivityManager(  905): Killing 3450:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4153/10055)
,D/AutoSetting( 4153): service - onCreate()
,I/dalvikvm-heap( 4093): Grow heap (frag case) to 10.068MB for 84664-byte allocation
,D/AutoSetting( 4153): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 4153): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/LocationManagerService(  905): request 42349f10 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4153): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 4153): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 4153): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 4153): service - handleMessage() setting current location null
D/AutoSetting( 4153): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4153): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4153/10055)
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3450
,D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4170): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4170): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4170/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4170/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4170/10079)
,D/PMS     (  905): acquireWL(42619f10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.NetworkChangeReceiver: pid=4187 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  905): acquireWL(42588b38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1449594304089 min interval config: 0 actual interval: 76936992
D/PMS     (  905): releaseWL(42619f10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1958): Checking schedule, now: 1449671241089 next: 1449594334058
,I/CheckinService( 1958): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
,I/dalvikvm-heap( 4093): Grow heap (frag case) to 10.282MB for 75760-byte allocation
,I/CheckinService( 1958): Preparing to send checkin request
,I/EventLogService( 1958): Accumulating logs since 1449670460373
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{433151e0 u0 ReceiverList{433150c0 4093 com.facebook.katana/10027/u0 remote:432fb7f8}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ca4e70 u0 ReceiverList{43ca4e30 4093 com.facebook.katana/10027/u0 remote:43127438}}
,I/DeviceManagement( 4187): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4187 dbg=false s=true
,I/DeviceManagement( 4187): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
,I/DeviceManagement( 4187): WorkflowService: Starting workflow service
,I/DeviceManagement( 4187): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41b49c98] args=[Bundle[mParcelledData.dataSize=804]]
I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4203 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,I/DeviceManagement( 4187): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 4187): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
,I/DeviceManagement( 4187): NetworkChangeWorkflow: ==================================================
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027),
,I/DeviceManagement( 4187): ModelRegistry: Loading model meta data from resources...
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,I/DeviceManagement( 4187): SessionStateController: Checking invariants...
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  905): acquireWL(43112ab8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4203): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4203): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/PMS     (  905): releaseWL(43112ab8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4203): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4203): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4203): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
D/WifiService(  905): New client listening to asynchronous messages
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,I/DeviceManagement( 4187): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 4187): SessionStateController: Checking invariants...
D/WIFI_ICON( 1108): WifiActivity: 3
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4093): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): acquireWL(43c37bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029}
V/AlarmManager(  905): sending alarm PendingIntent{41e974d0: PendingIntentRecord{43678210 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
D/PMS     (  905): releaseWL(43c37bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
,D/AccFlag ( 1216): sku_id=99
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4093): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ContactMessageStore( 1216): notify MmsSms
D/AccFlag ( 1216): sense_version=6.0
D/AccFlag ( 1216): sku_id=99
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,D/AccFlag ( 1216): sku_id=99
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4203/10151)
,V/WebViewChromiumFactoryProvider( 4203): Binding Chromium to main looper Looper (main, tid 1) {41b1b688}
,I/LibraryLoader( 4203): Expected native library version number "",actual native library version number ""
,I/chromium( 4203): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4203): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(43bd6e50): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4203): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(4405be88): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(4405be88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,I/DeviceManagement( 4187): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 67
,D/AccFlag ( 1216): sku_id=99
,I/Adreno-EGL( 4203): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4203): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4203): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4203): Local Branch: 
I/Adreno-EGL( 4203): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4203): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4203):                  aa63bbd948f41d15fc72f585e
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
,D/AccFlag ( 1216): sku_id=99
,D/PMS     (  905): acquireWL(4410fe18): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,I/NSApplication( 4203): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4203/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4203/10151)
,I/DeviceManagement( 4187): Perf: *** Cache update - start...
,I/DeviceManagement( 4187): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 4187): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4187): Perf: *** Enabled app cache update - complete: 1 ms
,I/ActivityManager(  905): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4244 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/DeviceManagement( 4187): Perf: *** Config cache update - start...
I/DeviceManagement( 4187): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4187): ConfigCacheController: *** Updating stale config cache entries...
,W/dalvikvm( 4187): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
,W/dalvikvm( 4187): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 4187): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1958/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
W/System.err( 4187): Starting the internal HTTP client
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3951): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/DeviceManagement( 4187): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEwLTE0VDEwOjI4OjM4LjU4Mlo
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(41d96e18): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4244 10160 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 1347): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4244/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4244/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4244/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4244/10160)
,D/PMS     (  905): acquireWL(420f6008): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4244 10160 null
,D/PMS     (  905): releaseWL(41d96e18): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1347): [NET] getaddrinfo-, 1
D/libc    ( 1347): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
I/DeviceManagement( 4187): DeviceClientResource: Active network...
I/DeviceManagement( 4187):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3dd7 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
I/CalendarProvider2( 4136): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4136): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
,D/BuildInfo( 4187): Created new instance: com.htc.cs.lib.hms.BuildInfo@41db32c0
,I/DeviceManagement( 4187): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
,D/Process (  905): killProcessQuiet, pid=3738
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  905): killProcessQuiet, pid=3760
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3738:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/PMS     (  905): releaseWL(420f6008): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  905): Killing 3760:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
,I/ActivityManager(  905): Recipient 3738
,D/libc    ( 4187): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4187): [NET] getaddrinfo-, 1
,D/libc    ( 4187): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3760
,D/libc    ( 4187): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 272
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1347): [NET] getaddrinfo_proxy-, success
,I/iu.SyncManager( 1958): SYNC; picasa accounts
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,D/NetworkLogImpl( 1958): Loaded NetworkSpeedPredictor
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 1958): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/iu.UploadsManager( 1958): num queued entries: 0
I/iu.UploadsManager( 1958): num updated entries: 0
,I/iu.SyncManager( 1958): NEXT; no task
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/libc    ( 4187): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4187): [NET] getaddrinfo-,err=8
D/libc    ( 4187): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4187): [NET] getaddrinfo-, 1
,D/libc    ( 4187): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =698e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/AlertReceiver( 3787): beginStartingService
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
D/PMS     (  905): acquireWL(438e39b0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3787 10013 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
D/PMS     (  905): acquireWL(41bf2a88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1347): [NET] getaddrinfo-, 1
,D/libc    ( 1347): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4c7d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=204
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4187): [NET] getaddrinfo_proxy-, success
D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
,D/AlertService( 3787): start to updateAlertNotification!
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4284 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 215
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,W/WeatherRequest( 1108): request cur loc, but there is no sys cur
,D/libc    ( 1347): [NET] getaddrinfo_proxy-, success
,D/AlertService( 3787): No fired or scheduled alerts
,D/HtcAlertUtils( 3787): -- cancelReminderNotification --
,D/HtcAlertUtils( 3787): broadcastExistReminder!
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3787): stopSelfResult true
D/PMS     (  905): releaseWL(438e39b0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/WeatherUtility( 4284): can't get weather sync account
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4299 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1347): [NET] getaddrinfo-,err=8
,W/WeatherRequest( 4284): request cur loc, but there is no sys cur
,W/Settings( 4284): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1245): com.htc.widget.weatherclock (true,33751552)
D/PMS     (  905): acquireWL(42f66918): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4299 10071 null
D/PMS     (  905): acquireWL(425677e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4299 10071 null
D/PMS     (  905): releaseWL(42f66918): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/RemoteViews.Performance( 1245): com.htc.widget.weatherclock 2 9 17
,D/TodoTaskshortcut( 4299): update TASK shortcut>
I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4313 uid=10090 gids={50090, 3003, 5012, 1028}
,I/TodoTaskNotifyService( 4299): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 4299): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4299): stopSelfResult true
,D/Process (  905): killProcessQuiet, pid=3534
,I/WorldClock.Global( 4313): isHtcDevice = true
D/PMS     (  905): releaseWL(425677e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  905): Killing 3534:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,I/GCM     ( 1347): GCM config loaded
,I/WorldClock.Global( 4313): isHtcDevice = true
W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4313): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4331 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 4313): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4313): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1108): receive(android.intent.action.ALARM_CHANGED,1,false)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,I/ActivityManager(  905): Recipient 3534
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/Process (  905): killProcessQuiet, pid=3482
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3482:com.android.vending/u0a74 (adj 15): empty #17
,D/TimeService( 4331): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449671242255
,D/Process (  905): killProcessQuiet, pid=3822
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3822:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3822
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(41e6a958): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1958 10029 null
,D/PMS     (  905): acquireWL(43315e90): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4405eef8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42582868): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4405eef8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,D/PMS     (  905): releaseWL(41e6a958): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  905): releaseWL(43315e90): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  905): releaseWL(41bf2a88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1449594304089 min interval config: 0 actual interval: 76938215
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
,D/PMS     (  905): releaseWL(42582868): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,D/PMS     (  905): acquireWL(42f8e518): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,I/ActivityManager(  905): Recipient 3482
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,I/DeviceManagement( 4187): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4187): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4187): DeviceClientResourceController: handleDirectives: []
,W/dalvikvm( 4187): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 4187): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 4187): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4187): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 4187): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 4187): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4187): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4187): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
,W/dalvikvm( 4187): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4187): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 4187): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,D/PMS     (  905): releaseWL(42f8e518): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
E/dalvikvm( 4187): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 4187): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4187): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 4187): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 4187): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 4187): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 4187): isCompatible false
I/System.out( 4187): createObjectMapper
,I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
,I/System.out( 4187): isCompatible false
I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4351 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4363 uid=10041 gids={50041}
,I/DeviceManagement( 4187): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 4187): DeviceClientResource: Active network...
I/DeviceManagement( 4187):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=11 [35][4][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
,D/libc    ( 4187): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4187): [NET] getaddrinfo-, 1
,D/libc    ( 4187): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/Process (  905): killProcessQuiet, pid=3982
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Delay finish: com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent
,I/ActivityManager(  905): Killing 3982:com.htc.widget.process2/u0a50 (adj 15): empty #17
D/libc    ( 4187): [NET] getaddrinfo_proxy-, success
D/libc    ( 4187): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4187): [NET] getaddrinfo-,err=8
D/libc    ( 4187): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4187): [NET] getaddrinfo-, 1
D/libc    ( 4187): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =284 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4187): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  905): Recipient 3982
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 4351): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4351): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4351): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4351): install
I/MultiDex( 4351): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
I/MultiDex( 4351): loading existing secondary dex files
I/MultiDex( 4351): load found 3 secondary dex files
I/MultiDex( 4351): install done
,I/Icing   ( 1958): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,W/dalvikvm( 4351): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4351): VFY: unable to resolve instance field 46
,W/dalvikvm( 4351): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4351): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/Icing   ( 1958): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/PMS     (  905): releaseWL(4410fe18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4351): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4351): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4351): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4351): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 4351): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
,W/dalvikvm( 4351): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
W/dalvikvm( 4351): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4351): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=11 [9][1][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/NativeLibraryUtils( 4351): Install completed successfully. count=13 extracted=0
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421cfae0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
,W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
I/PMS     (  905): Going to sleep due to screen timeout...
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  905): Couldn't get kernel wake lock stats
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421cfae0, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420bd250
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42efd8a0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/dalvikvm( 4351): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/dalvikvm( 4351): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 4351): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/WVCdm   (  370): PrepareKeyRequest: nonce=172522306
,W/dalvikvm( 4351): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4351): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 4351): Using platform SSLCertificateSocketFactory
,D/libc    ( 4351): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4351): [NET] getaddrinfo-,err=8
D/libc    ( 4351): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4351): [NET] getaddrinfo-, 1
D/libc    ( 4351): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c243 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11
D/libc    (  363): [NET]res_nsend:resplen=86
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4351): [NET] getaddrinfo_proxy-, success
I/DeviceManagement( 4187): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4187): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4187): DeviceClientResourceController: handleDirectives: []
I/System.out( 4187): isCompatible false
I/System.out( 4187): createObjectMapper
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
,I/System.out( 4187): isCompatible false
,D/ProviderChangeReceiver( 3787): ---------------------------------------------------
,D/ProviderChangeReceiver( 3787): ProviderChangeReceiver onReceive, start to update notification!
,I/ActivityManager(  905): Resuming delayed broadcast
,D/AlertService( 3787): start to updateAlertNotification!
D/AlertService( 3787): No fired or scheduled alerts
,D/HtcAlertUtils( 3787): -- cancelReminderNotification --
,D/HtcAlertUtils( 3787): broadcastExistReminder!
W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  905): killProcessQuiet, pid=3918
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Killing 3918:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3918
,D/PMS     (  905): acquireWL(4237eca0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4299 10071 null
,D/PMS     (  905): acquireWL(42318fc0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4299 10071 null
,D/PMS     (  905): acquireWL(42030000): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4299 10071 null
,D/PMS     (  905): releaseWL(4237eca0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.notification.NotifyReceiver
,D/PMS     (  905): acquireWL(42318fc0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4299 10071 null
,D/PMS     (  905): releaseWL(42030000): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4299): java.lang.NullPointerException
W/System.err( 4299): java.lang.NullPointerException
W/System.err( 4299): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4299): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4299): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4299): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4299): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4299): stopSelfResult true
D/PMS     (  905): releaseWL(42318fc0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/DeviceManagement( 4187): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,I/DeviceManagement( 4187): DeviceClientResource: Active network...
I/DeviceManagement( 4187):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4393 uid=10078 gids={50078}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [5][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (4187/10098)
,D/libc    ( 4187): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4187): [NET] getaddrinfo-, 1
,D/libc    ( 4187): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4187): [NET] getaddrinfo_proxy-, success
D/libc    ( 4187): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4187): [NET] getaddrinfo-,err=8
D/libc    ( 4187): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4187): [NET] getaddrinfo-, 1
,D/libc    ( 4187): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c323 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4187): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4351): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4351): [NET] getaddrinfo-,err=8
D/libc    ( 4351): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4351): [NET] getaddrinfo-,err=8
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 313ms
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=3846
D/NfcService( 1232): ScreenObserver: OFF
D/NfcService( 1232): applyRouting - 0
V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42337308),
D/NfcService( 1232): applyRouting -2
W/ResourceType( 3846): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3846): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b281f0 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  905): acquireWL(423372d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMN     (  905): wakingUp
D/PMS     (  905): releaseWL(423372d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1108): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/PMS     (  905): acquireWL(420673f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/WindowManager(  905): No lock screen! windowToken=null
I/BatteryService(  905): n_update end
D/PMN     (  905): onScreenOn
D/PMS     (  905): releaseWL(420673f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/SMSBackup( 4393): Got a database change event
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 2165): [MTP][onReceive]+android.intent.action.USER_PRESENT
,I/HtcPowerSaver(  905): << updateStatus
D/MtpService( 2165): [MTP][onReceive]-
,D/NfcService( 1232): applyRouting - 0
,D/NfcService( 1232): applyRouting -2
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  905): acquireWL(424ef038): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/PMS     (  905): releaseWL(424ef038): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/Process (  905): killProcessQuiet, pid=3937
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19343 delay=15s
I/ActivityManager(  905): Killing 3937:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
,I/ClockThread( 1108): stop update clock
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): SET_SCREEN_ON:On
I/wpa_supplicant( 3951): htc_wext_set_keepalive +
I/wpa_supplicant( 3951): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3951): getPrivFuncNum +	
I/wpa_supplicant( 3951): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3951): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3951): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3951): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 3951): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=10 [19][2][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  370): ParamSet string: screen_state=on
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3951): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:93, mTXpacketCount:0, avgLinkspeed:72,mAvgTxRate54
D/WifiStateMachine(  905): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/WearableService( 1200): callingUid 10029, callindPid: 1200
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
D/NetworkPolicy(  905): updateScreenOn: false
,E/MDM     ( 1200): [70] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=30 [10][3][0]
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/LocationInitializer( 1958): Restart initialization of location
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(435869a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(435869a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42e7e2f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42e7e2f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3958): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3958): onScreenOn: 1449671243348
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3958): onScreenOn: 1449671243348
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420bd250
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420bd250, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42efd8a0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
,D/PMS     (  905): acquireWL(43c9cf30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1347): location=null
D/PMS     (  905): acquireWL(42f29398): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
D/PMS     (  905): releaseWL(43c9cf30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): releaseWL(42f29398): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
D/AuthorizationBluetoothService( 1347): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1347): Proximity feature is not enabled.
I/ActivityManager(  905): Recipient 3937
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19343 mDataStallAlarmIntent=PendingIntent{41ef19e8: PendingIntentRecord{43921d50 android broadcastIntent}}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3951): SET_SCREEN_ON:Off
I/wpa_supplicant( 3951): htc_wext_set_keepalive +
I/wpa_supplicant( 3951): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3951): getPrivFuncNum +	
I/wpa_supplicant( 3951): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3951): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3951): get_ip_address source addr = c0a80175
I/wpa_supplicant( 3951): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 3951): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,D/PMS     (  905): acquireWL(438ebe00): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,V/GmsCoreStatsServiceLauncher( 1958): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/wpa_supplicant( 3951): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/AutoSetting( 4153): receiver - intent: android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  905): updateScreenOn: false
,D/PMS     (  905): releaseWL(438ebe00): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ContactMessageStore( 1216): start background delete task...
W/fb4a(:<default>):UserScope( 4093): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ContactMessageStore( 1216): size: 0 , 0
D/ContactMessageStore( 1216): Background delete complete
W/fb4a(:<default>):UserScope( 4093): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/TetherSettings( 3274): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3274): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3274): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3274): Cust_ConnectToPC   : spcsc>false
D/        ( 3274): Cust_ConnectToPC   : IPT>true
D/        ( 3274): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3274): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3274): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3274): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3274): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=25 [4][1][0]
,D/AutoSetting( 4153): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3274): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3274): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3274): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3274):  defaultType:0
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
I/ActivityManager(  905): Resuming delayed broadcast
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(43c998d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43c998d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
D/PMS     (  905): acquireWL(42c0ec78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4426 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  905): releaseWL(42c0ec78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3958): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3958): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3958): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3958): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3958): onScreenOff
D/AutoSetting( 4153): service - mHandler: cancel location update
,D/AutoSetting( 4153): service -           changes count: 0
,W/ContextImpl( 4426): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): acquireWL(42419f30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4426 1000 null
D/SmartSyncUtils( 4426): isEpsOn(), nState = 0
,D/PMS     (  905): releaseWL(42419f30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4426): getMobilePolicyEnabled, result = true
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  905): killProcessQuiet, pid=3325
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3325:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(436e4aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,W/ContextImpl( 4426): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(436e4aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/SmartSyncUtils( 4426): isEpsOn(), nState = 0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
D/SmartSyncUtils( 4426): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4426): isEpsOn(), nState = 0
,D/WifiService(  905): New client listening to asynchronous messages
I/ActivityManager(  905): Recipient 3325
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/fb4a(:<default>):LocalFbBroadcastManager( 4093): Called registerBroadcastReceiver twice.
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42efd8a0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42efd8a0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
D/MediaRouterService(  905): Client com.google.android.music (pid 3325): Died!
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42efd8a0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42efd8a0
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42efdde8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42efdde8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2022703567
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4093/10027)
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/libc    ( 4093): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4093): [NET] getaddrinfo-,err=8
D/libc    ( 4093): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4093): [NET] getaddrinfo-, 1
,D/libc    ( 4093): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =93f6 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
I/DeviceManagement( 4187): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4187): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4187): DeviceClientResourceController: handleDirectives: []
I/System.out( 4187): isCompatible false
I/System.out( 4187): createObjectMapper
I/System.out( 4187): isCompatible false
,I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
I/System.out( 4187): isCompatible false
,I/System.out( 4187): isCompatible false
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 29
D/libc    (  363): [NET]res_nsend:resplen=74
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4093): [NET] getaddrinfo_proxy-, success
,I/global  ( 4093): call createSocket() return a new socket.
D/libc    ( 4093): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
D/libc    ( 4093): [NET] getaddrinfo-, SUCCESS
,I/DeviceManagement( 4187): ConfigCacheController: *** Update config cache: updating 3 entries...
,I/DeviceManagement( 4187): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,W/Settings( 4351): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/DeviceManagement( 4187): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 4187): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 4187): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4187): AlarmController: Scheduling TTL alarm for: 2015.12.10 at 15:00:02.444 CET (due to: com.htc.reportagent)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4187, uid=10098, userID:0
,I/DeviceManagement( 4187): Perf: *** Config cache update - complete: 2672 ms
,I/DeviceManagement( 4187): Perf: *** Cache update - complete: 2677 ms
,I/DeviceManagement( 4187): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41b49c98]
,I/DeviceManagement( 4187): WorkflowService: Stopping workflow service
,D/Process (  905): killProcessQuiet, pid=4093
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4093:com.facebook.katana/u0a27 (adj 15): empty #17
,I/Adreno-EGL( 4351): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4351): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4351): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4351): Local Branch: 
I/Adreno-EGL( 4351): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4351): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4351):                  aa63bbd948f41d15fc72f585e
W/ProcessCpuTracker(  905): Skipping unknown process pid 4451
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4351/10029)
,I/ActivityManager(  905): Recipient 4093
,D/WifiService(  905): Client connection lost with reason: 4
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(43bd6e50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4351): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4351): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4351): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4351): Local Branch: 
I/Adreno-EGL( 4351): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4351): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4351):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4351): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4351): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4351): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4351): Local Branch: 
I/Adreno-EGL( 4351): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4351): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4351):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,D/libc    ( 1958): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1958): [NET] getaddrinfo-,err=8
D/libc    ( 1958): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1958): [NET] getaddrinfo-, 1
,D/libc    ( 1958): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4c1e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1958): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1958): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1958): [NET] getaddrinfo-,err=8
,D/libc    ( 1958): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1958): [NET] getaddrinfo-,err=8
D/libc    ( 1958): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1958): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1958): Sending checkin request (12282 bytes)
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=17 [29][5][0]
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/CheckinTask( 1958): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1958): Checking schedule, now: 1449671245591 next: 1450194182586
,I/CheckinService( 1958): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,D/CheckinService( 1958): Recording last checkin time for package unspecified as 1449671245609
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,D/PMS     (  905): releaseWL(42588b38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  905): acquireWL(426e6f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1347/10029)
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,D/PMS     (  905): releaseWL(426e6f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 4203): Thread[GAThread,5,main]: No campaign data found.
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Process (  905): killProcessQuiet, pid=4078
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  905): killProcessQuiet, pid=4170
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4078:com.android.chrome/u0a96 (adj 15): empty #17
I/ActivityManager(  905): Killing 4170:com.google.android.setupwizard/u0a79 (adj 15): empty #18
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4170
I/ActivityManager(  905): Recipient 4078
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3347
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3347:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3347
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.htc.cs.dm
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1245): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/Launcher( 1245): Deferring update until onResume
D/Launcher( 1245): waitUntilResume // bindAppsUpdated
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4463 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
E/ExternalAccountType( 1316): Unsupported attribute readOnly
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/dalvikvm-heap( 4244): Grow heap (frag case) to 15.207MB for 1821008-byte allocation
,W/dalvikvm( 4463): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
W/dalvikvm( 4463): VFY: unable to resolve instance field 46
W/dalvikvm( 4463): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 4463): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4463): MmsConfig.loadMmsSettings
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  905):   Scheme: "smsto"
V/JNIHelp ( 4463): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ProviderInstaller( 4463): Installed default security provider GmsCore_OpenSSL
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4486 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4463, uid=10111, userID:0
,W/Settings( 4463): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
,D/MessageFrequencyProvider( 4486): onCreate
,V/GetPrviateResource( 4486): GetPrviateResource
,V/GetPrviateResource( 4486): GetPrviateResource
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4463, uid=10111, userID:0
,D/MmsCustomizationProvider( 4486): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4463, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4463, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4463, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4463, uid=10111, userID:0
,D/MmsCustomizationProvider( 4486): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/PMS     (  905): acquireWL(438f6768): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4463 10111 null
I/Babel   ( 4463): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4463): MmsConfig.loadFromDatabase
,E/Babel   ( 4463): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4463): MmsConfig.loadFromResources
,E/Babel   ( 4463): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4463): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 4153): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4153): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4187
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 4187:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2555): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  905): Recipient 4187
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MessageCustFlag( 4486): sense_version=6.0
,D/BTAccessoryUtil( 4486): createReceiver
D/PMS     (  905): releaseWL(438f6768): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/BTAccessoryUtil( 4486): registerReceiver return intent = null
D/MessageCustFlag( 4486): sku_id=99
,W/SystemReader( 4486): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  905): acquireWL(423ad928): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4486): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4486): networkCode: 
,D/MessageCustFlag( 4486): sku_id=99
D/MmsConfig( 4486): SIE smsPri: null
,D/MmsConfig( 4486): networkCode: 
,D/HtcTelephonyCapability( 4486): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4486): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4486): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4486): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  905): releaseWL(423ad928): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(41c1c630): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(41c1c630): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425dcd30): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425dcd30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42454868): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42454868): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(421fb088): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(421fb088): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  905): acquireWL(42469cf8): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42469cf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(41f851f8): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(41f851f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(431286e8): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 +
,I/Prism.WidgetManager( 1245): onLoadItems() +
D/PMS     (  905): releaseWL(431286e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(4258e2e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4244 10160 null
,D/PMS     (  905): releaseWL(4258e2e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/IcingCorporaProvider( 2555): UpdateCorporaTask done [took 701 ms] updated apps [took 701 ms] 
,D/PackageBroadcastService( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4514 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/PackageBroadcastService( 1958): Null package name or gms related package.  Ignoreing.
,D/PMS     (  905): acquireWL(4256ade8): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  905): Unable to load service info ResolveInfo{423f22f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PMS     (  905): releaseWL(4256ade8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4514, uid=10074, userID:0
,D/Finsky  ( 4514): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4514/10074)
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4514/10074)
,D/Finsky  ( 4514): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
W/dalvikvm( 4514): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4514): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4514): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4514, uid=10074, userID:0
,D/Ads     ( 4514): Skipping gmscore version check
,D/Finsky  ( 4514): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4514): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4514): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/Prism.WidgetManager( 1245): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1245): onLoadItems() -
,I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 -
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4514): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/[PluginManager]RegisterService( 4153): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 4153): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2555): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,D/Process (  905): killProcessQuiet, pid=4203
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4203:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(425970b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4244 10160 null
,D/PMS     (  905): releaseWL(425970b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PackageBroadcastService( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PeopleContactsSync( 1958): CP2 sync disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1958, uid=10029, userID:0
D/PMS     (  905): acquireWL(425f33c0): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425f33c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Recipient 4203
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2555): UpdateCorporaTask done [took 128 ms] updated apps [took 128 ms] 
,D/PhoneApp( 1216): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1216): -- N1 =0
,D/PhoneApp( 1216): -- N2 =0
,D/PhoneApp( 1216): -- N3 =0
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,W/PackageManager(  905): Unable to load service info ResolveInfo{44065bc0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,V/GmsNetworkLocationProvi( 1200): DISABLE
,I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/PMS     (  905): acquireWL(43c07ac0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43c07ac0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c53458): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43c53458): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4486): mNeedToUpdateDate2 start
,D/MmsConfig( 4486): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4486): startAsyncQueryReports ---
,D/SettingsManager( 4486): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b254d8
D/MmsAsyncWorkHandler( 4486): 
D/MmsAsyncWorkHandler( 4486): HM tk = 20001
,D/ReportIndicatorCache( 4486): MSG_QUERY_REPORTS >>
I/Messaging( 4486): mccmnc> 
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1216):  phoneType = -1
D/MmsSmsV2Provider( 1216): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4486): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4486): [DraftCache/1] refresh
,D/MmsConfig( 4486): networkCode: 
,D/Messaging( 4486): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 42
,D/AccFlag ( 1216): sku_id=99
D/PhoneStorageUtil( 4486): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4486): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4486): createReceiver
,D/MessageCustFlag( 4486): sense_version=6.0
,D/Jerry   ( 4486): start to preload cursor >>>>>>>
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1216):  phoneType = -1
D/MmsSmsV2Provider( 1216): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4486): [DraftCache/454] rebuildCache
D/TelephUtils( 1216): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
V/MmsProvider( 1216): Update uri=content://mms, match=0
,V/MmsProvider( 1216): selection=st=129 AND m_type!=134
,D/Messaging( 4486): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4486): TransactionService is going to be woken up.
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 42
D/MmsSmsV2Provider( 1216):  phoneType = -1
,D/MmsSmsV2Provider( 1216): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/TransactionService( 4486): 1-Creating TransactionService
,D/Messaging( 4486): mNeedToUpdateDate2: false
V/TransactionService( 4486): onStartCommand: 1
,D/MmsSystemEventReceiver( 4486): unRegisterForConnectionStateChanges
V/TransactionService( 4486): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4486): Loading previous transactions.
,D/LocationProviderProxy(  905): applying state to connected service
,D/LocationProviderProxy(  905): applying state to connected service
,D/Finsky  ( 4514): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  905): acquireWL(43708a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
V/AlarmManager(  905): sending alarm PendingIntent{42f9a210: PendingIntentRecord{42fa5cf0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449671254274, Int=0
,W/dalvikvm( 4514): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1216):  phoneType = -1
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1216): device_type: 1
D/PMS     (  905): releaseWL(43708a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/PMS     (  905): acquireWL(436fda30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43b3ff20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(436fda30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 42
,D/Jerry   ( 1216): URI_DRAFT
D/TransactionService( 4486): Force set service start id to 1
V/TransactionService( 4486): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4486): unRegisterForConnectionStateChanges
,D/TransactionService( 4486): stopSelfResult: true, mLastHandledServiceId: 1
,D/PMS     (  905): releaseWL(43b3ff20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (4514/10074)
V/TransactionService( 4486): Destroying TransactionService
D/DraftCache( 4486): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4486): [DraftCache/454] rebuildCache time: 1
D/MmsAsyncWorkHandler( 4486): 
D/MmsAsyncWorkHandler( 4486): HM tk = 20002
D/Messaging( 4486): ViewCache CreatePreload
D/Messaging( 4486): ViewCache CreatePreloadOnlyMultipleOpsList
D/Cust_MMSMS( 4486): _has_set_default_values_2=true
V/TransactionService( 4486): 4-Handling incoming message: { when=-7ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1216):  phoneType = -1
D/MmsSmsV2Provider( 1216): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4486): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 4486): def_index: 0
,D/MsgPreferenceUtils( 4486): globalIndex = 1
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/AccFlag ( 1216): sku_id=99
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/MsgPreferenceUtils( 4486): phone state: true
D/MsgPreferenceUtils( 4486): sd state: false
,D/MsgPreferenceUtils( 4486): vIndex = 0
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1216): sku_id=99
,D/libc    ( 4514): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4514): [NET] getaddrinfo-,err=8
D/libc    ( 4514): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4514): [NET] getaddrinfo-, 1
,D/libc    ( 4514): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =cf3 +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4514): [NET] getaddrinfo_proxy-, success
,I/global  ( 4514): call createSocket() return a new socket.
D/libc    ( 4514): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4514): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4514): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4514): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4514): untagSocket(69) failed with errno -22
,D/Finsky  ( 4514): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 +
,I/Prism.WidgetManager( 1245): onLoadItems() +
,W/NetworkManagementSocketTagger( 4514): untagSocket(69) failed with errno -22
,E/Prism.WidgetManager( 1245): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1245): onLoadItems() -
,I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 -
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43c3ba88 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4514): untagSocket(69) failed with errno -22
,D/Finsky  ( 4514): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.android.chrome to true
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4514/10074)
,W/dalvikvm( 4514): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Finsky  ( 4514): [1] InstallerImpl.requestInstall: Request install of com.google.android.gms v=8489036 pri=2 for auto_update
,D/Finsky  ( 4514): [1] InstallerImpl.kick: Installer kick - starting com.google.android.gms
,D/Finsky  ( 4514): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4514): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  905): acquireWL(420c84b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
,V/AlarmManager(  905): sending alarm PendingIntent{424bd630: PendingIntentRecord{43aff190 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1449671256900, Int=0
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  905): acquireWL(42444f30): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4514 10074 null
,D/PMS     (  905): releaseWL(420c84b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/DeviceConnectionService( 1200): client connected with version: 8296000
D/Finsky  ( 4514): [485] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4514): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4514): [NET] getaddrinfo-,err=8
D/libc    ( 4514): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4514): [NET] getaddrinfo-, 1
,D/libc    ( 4514): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  363): [NET] +++++ res_nsend xid =699d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 277
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4514): [NET] getaddrinfo_proxy-, success
,I/GAV4    ( 4463): Thread[GAThread,5,main]: No campaign data found.
,W/NetworkManagementSocketTagger( 4514): untagSocket(69) failed with errno -22
,W/SQLiteConnectionPool( 1958): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/Finsky  ( 4514): [1] DownloadImpl.setState: Duplicate state set for 'com.google.android.gms' (0). Already in that state
,D/Finsky  ( 4514): [1] DownloadQueueImpl.add: Download com.google.android.gms added to DownloadQueue
,D/Finsky  ( 4514): [1] DownloadImpl.setState: com.google.android.gms from 0 to 1.
,D/PMS     (  905): releaseWL(42444f30): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
D/Finsky  ( 4514): [1] StartNextDownloadRunnable.run: Download com.google.android.gms starting
,D/Process (  905): killProcessQuiet, pid=4284
,I/ActivityManager(  905): Killing 4284:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4284
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 4514): [466] DownloadQueueImpl$7.run: Enqueued com.google.android.gms as content://downloads/my_downloads/185
,D/Finsky  ( 4514): [1] DownloadImpl.setState: com.google.android.gms from 1 to 2.
,D/Finsky  ( 4514): [1] DownloadQueueImpl.onStart: com.google.android.gms: onStart
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2165/10021)
,D/Finsky  ( 4514): [1] DownloadQueueImpl.notifyProgress: com.google.android.gms: onProgress 0/-1 Status: 190.
,I/DownloadManager( 2165): Download 185 starting
D/PMS     (  905): acquireWL(43c94a98): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2165 10021 WorkSource{10074}
D/ConnectivityService(  905): getAllNetworkInfo called by  (2165/10021)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/Finsky  ( 4514): [1] DownloadQueueImpl.notifyProgress: com.google.android.gms: onProgress 0/-1 Status: 192.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2165/10021)
W/ActivityThread( 2165): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=5 [92][5][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/libc    ( 2165): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2165): [NET] getaddrinfo-,err=8
D/libc    ( 2165): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2165): [NET] getaddrinfo-, 1
,D/libc    ( 2165): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d53f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2165): [NET] getaddrinfo_proxy-, success
,D/PMS     (  905): acquireWL(426e2c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(426e2c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2165/10021)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/libc    ( 2165): [NET] getaddrinfo+,hn 25(0x72352d2d2d736e),sn(),family 0,flags 4
D/libc    ( 2165): [NET] getaddrinfo-,err=8
D/libc    ( 2165): [NET] getaddrinfo+,hn 25(0x72352d2d2d736e),sn(),family 0,flags 1024
D/libc    ( 2165): [NET] getaddrinfo-, 1
D/libc    ( 2165): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 25(0x72352d2d2d736e),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d830 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 1799
D/libc    (  363): [NET]res_nsend:resplen=88
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2165): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2165/10021)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=14 [50][7][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=25 [4][1][0]
,D/PMS     (  905): acquireWL(42efeeb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42efeeb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  905): acquireWL(4267ed88): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4267ed88): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(435db660): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/PMS     (  905): releaseWL(435db660): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  905): acquireWL(432f9e18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/PMS     (  905): releaseWL(432f9e18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (4514/10074)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=8 [3783][304][0]
,D/PMS     (  905): acquireWL(430ad760): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/PMS     (  905): releaseWL(430ad760): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  905): acquireWL(43ac8308): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3951): Wireless event: cmd=0x8c02 len=35
I/wpa_supplicant( 3951): WEXT: Custom wireless event: 'PERF_LOCK freq=medium cpu=2'
I/wpa_supplicant( 3951): receive event: PERF_LOCK freq=medium cpu=2
,I/wpa_supplicant( 3951): wlan0: PERF_LOCK freq=medium cpu=2
,D/WifiStateMachine(  905): PERF_LOCK_EVENT received,
D/WifiPerfLock(  905): acquire(): request=PERF_LOCK freq=medium cpu=2
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiPerfLock(  905): acquire(): parsed str freq=medium cpu=2
,D/WifiPerfLock(  905): lock CPU freq=3 cpu=2
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/PMS     (  905): acquireHCC(4406b620): CPU_MIN_FREQ WifiPerfLock 0x100 905 1000 null
D/PMS     (  905): acquireHCC(430dbfc8): CPU_MIN_NUM WifiPerfLock 0x400 905 1000 null
,D/PMS     (  905): releaseWL(43ac8308): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/DownloadManager( 2165): Download 185 finished with status SUCCESS
,D/Finsky  ( 4514): [1] DownloadBroadcastReceiver.onReceive: Intent received at DownloadBroadcastReceiver
D/PMS     (  905): releaseWL(43c94a98): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10074}
,D/Finsky  ( 4514): [1] DownloadQueueImpl.notifyProgress: com.google.android.gms: onProgress 21130562/21130562 Status: 200.
,D/Finsky  ( 4514): [1] DownloadImpl.setState: com.google.android.gms from 2 to 3.
,D/Finsky  ( 4514): [1] DownloadQueueImpl.onComplete: com.google.android.gms: onComplete
,D/Finsky  ( 4514): [1] DownloadQueueImpl.remove: Download com.google.android.gms removed from DownloadQueue
D/Finsky  ( 4514): [1] InstallerTask.advanceState: Prepare to patch com.google.android.gms (com.google.android.gms) from content://downloads/my_downloads/185 format 2
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (4514/10074)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=10 [4005][409][0]
,V/Herrevad( 1958): NQAS connected
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiManager( 1958): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
,D/ConnectivityService(  905): getNetworkInfo networkType=17 called by com.google.android.gms (1958/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/WifiManager( 1958): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/Finsky  ( 4514): [490] InstallerTask$8.doInBackground$1a3e6397: Patch apply task for com.google.android.gms (com.google.android.gms) (format 2) completed in -3016 ms
,D/Finsky  ( 4514): [1] InstallerTask$8.onPostExecute: Successfully applied patch to update com.google.android.gms (com.google.android.gms)
,D/Finsky  ( 4514): [1] InstallerTask.advanceState: Begin install of com.google.android.gms
,D/PackageManager(  905): installPackage , uri:file:, flags:2, installer:com.android.vending, uid:10074, pid:4514, userId:UserHandle{0}
,I/ActivityManager(  905): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4618 uid=10019 gids={50019, 1028, 1015, 1023, 2001, 1035, 5001}
,W/ActivityManager(  905): No content provider found for permission revoke: file:
,D/Finsky  ( 4514): [1] PackageVerificationReceiver.onReceive: Skipping verification because own installation
,D/Finsky  ( 4514): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (4514/10074)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (4514/10074)
,W/ActivityManager(  905): No content provider found for permission revoke: file:
,I/PackageManager(  905): Copying native libraries to /data/app-lib/vmdl1213430542
,W/Resources(  905): Converting to boolean: TypedValue{t=0x3/d=0x21cc "false" a=4 r=0x7f120ac5}
,W/ResourceType(  905): Failure getting entry for 0x7f1303bb (t=18 e=955) in package 0 (error -75) name=com.google.android.gms
,D/wpa_supplicant( 3951): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3951): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3951): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3951): Wireless event: cmd=0x8c02 len=19
I/wpa_supplicant( 3951): WEXT: Custom wireless event: 'PERF_UNLOCK'
I/wpa_supplicant( 3951): receive event: PERF_UNLOCK
,I/wpa_supplicant( 3951): wlan0: PERF_UNLOCK
D/WifiStateMachine(  905): PERF_UNLOCK_EVENT received
D/WifiPerfLock(  905): release()
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/PMS     (  905): releaseHCC(4406b620): CPU_MIN_FREQ WifiPerfLock 0x100 null
D/PMS     (  905): releaseHCC(430dbfc8): CPU_MIN_NUM WifiPerfLock 0x400 null
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(44182730): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): acquireWL(4409b0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{4236df80: PendingIntentRecord{424a4af8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140756, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{41d5d710: PendingIntentRecord{424eaec0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=141598, Int=0
D/PMS     (  905): acquireWL(43bddc10): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  363): [NET] +++++ res_nsend xid =b173 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  905): releaseWL(4409b0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4356c5d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43bddc10): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4356c5d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  905): Force stopping com.google.android.gms appid=10029 user=-1: replace sys pkg
,D/Process (  905): killProcessQuiet, pid=1200
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 1200:com.google.android.gms.persistent/u0a29 (adj 1): stop com.google.android.gms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.reporting.service.ReportingAndroidService in 11000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 20999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 30999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 40998ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 50998ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 60997ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 70997ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 80996ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 90996ms
,I/ActivityManager(  905): Killing 4351:com.google.android.gms.unstable/u0a29 (adj 15): stop com.google.android.gms
D/Process (  905): killProcessQuiet, pid=4351
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,D/Process (  905): killProcessQuiet, pid=1958
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 1958:com.google.android.gms/u0a29 (adj 9): stop com.google.android.gms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 100988ms
,D/Process (  905): killProcessQuiet, pid=1347
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 1347:com.google.process.gapps/u0a29 (adj 6): stop com.google.android.gms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 110979ms
I/ActivityManager(  905):   Force stopping service ServiceRecord{430b8780 u0 com.google.android.gms/com.google.android.location.geocode.GeocodeService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{4260b110 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{43b72200 u0 com.google.android.gms/.analytics.service.AnalyticsService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{42bf92f0 u0 com.google.android.gms/com.google.android.location.fused.service.FusedProviderService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{43c62ed0 u0 com.google.android.gms/com.google.android.location.fused.FusedLocationService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{44098f08 u0 com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{42548538 u0 com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{436f5270 u0 com.google.android.gms/com.google.android.location.network.NetworkLocationService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{425dcfb8 u0 com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService}
I/ActivityManager(  905):   Force stopping service ServiceRecord{425bd5a8 u0 com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker}
I/ActivityManager(  905):   Force stopping service ServiceRecord{4243aca8 u0 com.google.android.gms/.common.stats.GmsCoreStatsService}
W/PackageManager(  905): Package com.google.android.gms desires unavailable shared library com.google.android.ble; ignoring!
W/PackageManager(  905): Trying to update system app code path from /data/app/com.google.android.gms-2.apk to /data/app/com.google.android.gms-1.apk
,D/LocationManagerService(  905): Location listener died
D/LocationManagerService(  905): Location listener died
D/GpsLocationProvider(  905): GPS status listener died
,D/CarGpsProvider(  905): GPS Mock status listener died
,I/LocationManagerService(  905): remove com.google.android.gms 4249e2b0
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,I/LocationManagerService(  905): remove com.google.android.gms 42536af0
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 14
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/WifiService(  905): Client connection lost with reason: 4
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,I/PackageManager(  905): Running dexopt on: com.google.android.gms
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/PackageManager(  905): Package com.google.android.gms declares lib com.google.android.gms that is not declared on system image; skipping
W/PackageManager(  905): Code path for pkg : com.google.android.gms changing from /data/app/com.google.android.gms-2.apk to /data/app/com.google.android.gms-1.apk
I/ActivityManager(  905): Force stopping com.google.android.gms appid=10029 user=-1: update pkg
,W/PackageManager(  905): Resource path for pkg : com.google.android.gms changing from /data/app/com.google.android.gms-2.apk to /data/app/com.google.android.gms-1.apk
,D/AutoSetting( 4153): service - mHandler: update timezone
,W/PackageSettings(  905): Skipping PackageSetting{4224e158 com.example.hello/10396} due to missing metadata
,W/PackageManager(  905): Not granting permission android.permission.READ_LOGS to package com.htc.ptg (protectionLevel=50 flags=0xbe44)
W/PackageManager(  905): Unknown permission com.android.smspush.WAPPUSH_MANAGER_BIND in package com.android.phone
W/PackageManager(  905): Unknown permission com.tmobile.driving.permission.READ_DRIVING_MODE_SETTINGS in package com.android.phone
W/PackageManager(  905): Unknown permission com.htc.permission.ACCESS_NOTES in package com.android.phone
,W/PackageManager(  905): Unknown permission com.htc.socialnetwork.plurk.permission.useprovider in package com.android.phone
W/PackageManager(  905): Unknown permission com.htc.htctwitter.permission.useprovider in package com.android.phone
W/PackageManager(  905): Unknown permission htc.friendstream.permission.SYSTEM_USE in package com.android.phone
W/PackageManager(  905): Unknown permission com.tmobile.vvm.application.permission.ACCESS_PROVIDER in package com.android.phone
,W/PackageManager(  905): Unknown permission com.htc.sense.socialplugins.permission.USE_SOCIAL_COMPONENT in package com.android.phone
W/PackageManager(  905): Unknown permission com.htc.permission.SOCIAL_NETWORK in package com.android.phone
W/PackageManager(  905): Unknown permission com.htc.socialnetwork.permission.useprovider in package com.android.phone
W/PackageManager(  905): Unknown permission com.htc.HTCSpeaker.ACCESS_VR in package com.android.phone
W/PackageManager(  905): Unknown permission htc.socialmanager.permission.USE_SOCIALSERVICE in package com.android.phone
W/PackageManager(  905): Unknown permission com.htc.permission.vdmc.ACCESS_HTCDM_PROPERTY in package com.android.phone
W/PackageManager(  905): Unknown permission com.kddi.android.iida.iidahome.permission.BUBBLE_NOTIFICATION in package com.android.phone
W/PackageManager(  905): Unknown permission htc.socialmanager.permission.READ_SOCIAL_DATABASE in package com.android.phone
,W/PackageManager(  905): Unknown permission htc.socialmanager.permission.WRITE_SOCIAL_DATABASE in package com.android.phone
W/PackageManager(  905): Unknown permission htc.socialmanager.permission.SOCIAL_HOST in package com.android.phone
W/PackageManager(  905): Unknown permission htc.permission.weather.USE_DATA in package com.android.phone
W/PackageManager(  905): Unknown permission com.htc.vvm.permission.READ_VOICE_MAIL in package com.android.phone,
W/PackageManager(  905): Unknown permission com.itsoninc.android.permission.USE_ITSON_SERVICE in package com.android.phone
W/PackageManager(  905): Unknown permission com.cequint.ecid.CALLER_ID_LOOKUP in package com.android.phone
W/PackageManager(  905): Unknown permission com.verizon.vzwavs.permission.READ in package com.android.phone
W/PackageManager(  905): Unknown permission com.verizon.vzwavs.permission.WRITE in package com.android.phone,
W/PackageManager(  905): Unknown permission com.android.gallery3d.permission.GALLERY_PROVIDER in package com.android.bluetooth
W/PackageManager(  905): Unknown permission com.htc.HTCSpeaker.ACCESS_VR in package com.android.bluetooth
W/PackageManager(  905): Unknown permission android.permission.MMS_SEND_OUTBOX_MSG in package com.android.bluetooth
,W/PackageManager(  905): Unknown permission com.android.email.permission.ACCESS_PROVIDER in package com.android.bluetooth
,W/PackageManager(  905): Unknown permission com.htc.permission.ACCESS_NOTES in package com.android.providers.calendar
,W/PackageManager(  905): Unknown permission com.dropbox.android.provider.ACCOUNT_INFO_READ in package com.htc.cloudstorage.dropbox
,W/PackageManager(  905): Unknown permission com.htc.permission.vdmc.ACCESS_HTCDM_PROPERTY in package com.htc.htcpowermanager
,W/PackageManager(  905): Unknown permission com.twitter.android.permission.AUTH_APP in package com.htc.sense.socialnetwork.twitter
,W/PackageManager(  905): Unknown permission com.htc.launcher.permission.APP_DEFAULT in package com.htc.lockscreen
,W/PackageManager(  905): Unknown permission android.permission.READ_OWNER_DATA in package com.google.android.setupwizard
,W/PackageManager(  905): Unknown permission android.permission.WRITE_OWNER_DATA in package com.google.android.setupwizard
,W/PackageManager(  905): Unknown permission com.htc.permission.ACCESS_VOWIFI in package com.android.settings
W/PackageManager(  905): Unknown permission com.htc.laputa.permission.FOOTPRINTPICKER in package com.htc.android.locationpicker
W/PackageManager(  905): Unknown permission com.htc.laputa.permission.GEOCODER_PROVIDER in package com.htc.android.locationpicker
W/PackageManager(  905): Unknown permission com.htc.laputa.permission.LB_CONTENT_PROVIDER in package com.htc.android.locationpicker
,W/PackageManager(  905): Unknown permission com.foursquare.permission.VENUE_SEARCH in package com.htc.android.locationpicker
W/PackageManager(  905): Unknown permission com.google.android.voicesearch.SHORTCUTS_ACCESS in package com.google.android.googlequicksearchbox
W/PackageManager(  905): Unknown permission com.google.android.voicesearch.ACCESS_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  905): Unknown permission com.android.browser.permission.PRELOAD in package com.google.android.googlequicksearchbox
,W/PackageManager(  905): Unknown permission com.google.android.ears.permission.WRITE in package com.google.android.googlequicksearchbox
W/PackageManager(  905): Unknown permission com.google.android.apps.googlevoice.permission.AUTO_SEND in package com.google.android.googlequicksearchbox
,W/PackageManager(  905): Unknown permission com.google.android.launcher.permission.CONTENT_REDIRECT in package com.google.android.googlequicksearchbox
W/PackageManager(  905): Unknown permission com.facebook.orca.provider.ACCESS in package com.facebook.katana
W/PackageManager(  905): Unknown permission com.amazon.device.messaging.permission.RECEIVE in package com.facebook.katana
W/PackageManager(  905): Unknown permission com.sec.android.provider.badge.permission.READ in package com.facebook.katana
W/PackageManager(  905): Unknown permission com.sec.android.provider.badge.permission.WRITE in package com.facebook.katana
W/PackageManager(  905): Unknown permission com.sonyericsson.home.permission.BROADCAST_BADGE in package com.facebook.katana
W/PackageManager(  905): Unknown permission com.facebook.home.permission.WRITE_BADGES in package com.facebook.katana
,W/PackageManager(  905): Unknown permission com.nokia.pushnotifications.permission.RECEIVE in package com.facebook.katana
,W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.SECURE_VIEW in package com.htc.music
,W/PackageManager(  905): Unknown permission com.htc.vvm.permission.READ_VOICE_MAIL in package com.android.providers.telephony
,W/PackageManager(  905): Unknown permission android.permission.WRITE_SYNC_STATS in package com.google.android.apps.docs
W/PackageManager(  905): Unknown permission android.permission.ACCESS_DRMRPC in package com.htc.mirrorlinkserver
,W/PackageManager(  905): Unknown permission WRITE_EXTERNAL_STORAGE in package com.htc.mirrorlinkserver
,W/PackageManager(  905): Unknown permission com.dropbox.android.provider.ACCOUNT_INFO_READ in package com.htc.android.htcsetupwizard
W/PackageManager(  905): Unknown permission com.htc.vzwba.permission.baplus.contactsync in package com.htc.android.htcsetupwizard
W/PackageManager(  905): Unknown permission com.htc.permission.vdmc.ACCESS_HTCDM_PROPERTY in package com.htc.android.htcsetupwizard
W/PackageManager(  905): Unknown permission com.htc.syncml.permission_attaddressbook in package com.htc.android.htcsetupwizard
W/PackageManager(  905): Unknown permission com.vcast.mediamanager.CLOUD_PERMISSION in package com.htc.android.htcsetupwizard
W/PackageManager(  905): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.onetimeinitializer
,W/PackageManager(  905): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.onetimeinitializer
,W/PackageManager(  905): Unknown permission com.htc.android.mail.permission.READ_ATTACHMENT in package com.htc.lmw
,W/PackageManager(  905): Unknown permission com.htc.backuprestore.sd.permission.READ_RECORD in package com.htc.backupreset
,W/PackageManager(  905): Unknown permission com.westtek.jcp.PRINT in package com.infraware.docmaster
W/PackageManager(  905): Unknown permission com.htc.android.mail.permission.READ_ATTACHMENT in package com.htc.sense.mms
,W/PackageManager(  905): Unknown permission javax.microedition.gba.USE_GBA_SERVICE in package com.htc.sense.mms
W/PackageManager(  905): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.htc.sense.mms
,W/PackageManager(  905): Unknown permission com.itsoninc.android.permission.USE_ITSON_SERVICE in package com.htc.sense.mms
W/PackageManager(  905): Unknown permission com.fusionone.android.sync.permission.READ_WRITE_PROVIDERS in package com.android.providers.contacts
,W/PackageManager(  905): Unknown permission com.htc.album.permission.UseHtcGallery in package com.android.providers.contacts
,W/PackageManager(  905): Unknown permission com.htc.HTCSpeaker.ACCESS_VR in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.permission.vdmc.ACCESS_HTCDM_PROPERTY in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.BIND_SERVICE in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.CHAT_DATA_PROVIDER in package com.android.providers.contacts,
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.CHAT in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.NEW_CHAT in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.SHOW_SHARED_FILES in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.syncml.permission_attaddressbook in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.syncml.permission.READ_SYNCML_PROFILE in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.vvm.permission.PLAY_VVM in package com.android.providers.contacts
,W/PackageManager(  905): Unknown permission htc.friendstream.renrenwebplugin.permission.SYSTEM_USE in package com.android.providers.contacts
W/PackageManager(  905): Unknown permission com.htc.android.mail.permission.DELETE_ACCOUNT in package com.lmi.htc.rescuesecurity
W/PackageManager(  905): Unknown permission com.htc.android.mail.eassvc.account.mdm.DELETE in package com.lmi.htc.rescuesecurity
,W/PackageManager(  905): Unknown permission android.permission.RECEIVE_EMAIL_NOTIFICATION in package com.lmi.htc.rescuesecurity
W/PackageManager(  905): Unknown permission com.google.android.gallery3d.permission.PICASA_STORE in package com.google.android.apps.plus
W/PackageManager(  905): Unknown permission android.permission.REAL_GET_TASKS in package com.android.vending
,W/PackageManager(  905): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x40cabec5)
W/PackageManager(  905): Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.android.vending
W/PackageManager(  905): Unknown permission android.permission.USE_FINGERPRINT in package com.android.vending
W/PackageManager(  905): Unknown permission android.permission.GET_PACKAGE_IMPORTANCE in package com.android.vending
W/PackageManager(  905): Unknown permission android.permission.GET_ACCOUNTS_PRIVILEGED in package com.android.vending
W/PackageManager(  905): Unknown permission android.permission.INSTALL_GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  905): Unknown permission android.permission.GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  905): Unknown permission android.permission.REVOKE_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  905): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.android.vending
,W/PackageManager(  905): Not granting permission android.permission.BATTERY_STATS to package com.android.vending (protectionLevel=18 flags=0x40cabec5)
,W/PackageManager(  905): Unknown permission htc.permission.weather.USE_DATA in package com.htc.powersavinglauncher
,W/PackageManager(  905): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gsf (protectionLevel=2 flags=0x40883e45)
,W/PackageManager(  905): Unknown permission htc.permission.weather.USE_DATA in package com.android.keyguard
,W/PackageManager(  905): Unknown permission com.htc.launcher.permission.APP_DEFAULT in package com.android.keyguard
W/PackageManager(  905): Unknown permission com.htc.permission.match.BUNDLE_READ_WRITE in package com.nero.android.htc.sync
W/PackageManager(  905): Unknown permission com.htc.permission.match.BUNDLE_SERVICE in package com.nero.android.htc.sync
W/PackageManager(  905): Unknown permission com.htc.permission.match.BI_SERVICE in package com.nero.android.htc.sync
,W/PackageManager(  905): Unknown permission com.htc.mediamanager.ACTION_RECOVER_ZOE_BURST in package com.nero.android.htc.sync
W/PackageManager(  905): Unknown permission android.permission.WRITE_OWNER_DATA in package com.nero.android.htc.sync
,W/PackageManager(  905): Unknown permission android.permission.READ_OWNER_DATA in package com.nero.android.htc.sync
W/PackageManager(  905): Unknown permission com.htc.lucy.permission.RESTORE_STATUS_UPDATE in package com.nero.android.htc.sync
W/PackageManager(  905): Unknown permission com.htc.lucy.permission.BACKUP_STATUS_UPDATE in package com.nero.android.htc.sync
,W/PackageManager(  905): Unknown permission com.htc.providers.mediacollection.permission.ACCESS_MCP in package com.nero.android.htc.sync
W/PackageManager(  905): Unknown permission com.htc.accessory.permission.TEST in package com.htc.accessory
W/PackageManager(  905): Unknown permission android.Manifest.permission.MODIFY_PHONE_STATE in package com.htc.accessory
W/PackageManager(  905): Unknown permission com.htc.IR_CONTROLLER in package com.htc.accessory
,W/PackageManager(  905): Unknown permission com.htc.permission.ACCESS_IR_CONTROLLER in package com.htc.accessory
,W/PackageManager(  905): Not granting permission android.permission.ACCESS_ALL_DOWNLOADS to package com.htc.video (protectionLevel=2 flags=0x4088be45)
,W/PackageManager(  905): Unknown permission com.android.vending.billing.IBillingAccountService.BIND2 in package com.google.android.gsf.login
,W/PackageManager(  905): Unknown permission com.htc.permission.ACCESS_IR_CONTROLLER in package com.htc.wifidisplay
,W/PackageManager(  905): Not granting permission android.permission.BROADCAST_PACKAGE_REMOVED to package com.google.android.marvin.talkback (protectionLevel=2 flags=0xc9be45)
W/PackageManager(  905): Unknown permission com.htc.socialnetwork.plurk.permission.useprovider in package com.htc.htccontactwidgets
,W/PackageManager(  905): Unknown permission htc.opensense.permission.USE_BROADCAST in package com.htc.htccontactwidgets
,W/PackageManager(  905): Unknown permission com.htc.permission.vdmc.ACCESS_HTCDM_PROPERTY in package com.htc.CustomizationSetup
,W/PackageManager(  905): Not granting permission android.permission.ACCOUNT_MANAGER to package com.htc.aurora (protectionLevel=2 flags=0x4088be45)
,W/PackageManager(  905): Unknown permission com.ndoo.aurora.APP_UPDATE in package com.htc.aurora
,W/PackageManager(  905): Unknown permission com.htc.laputa.permission.LB_CONTENT_PROVIDER in package com.htc.AutoMotive.Traffic
W/PackageManager(  905): Unknown permission htc.permission.weather.USE_DATA in package com.htc.launcher
W/PackageManager(  905): Unknown permission htc.permission.weather.RECEIVER in package com.htc.launcher
W/PackageManager(  905): Unknown permission com.htc.stock.permission.ACCESS_STOCK_DATA in package com.htc.launcher
W/PackageManager(  905): Unknown permission com.htc.deals.permission.ACCESS_PROVIDER in package com.htc.launcher
W/PackageManager(  905): Unknown permission com.htc.deals.permission.SYNC_DATA in package com.htc.launcher
,W/PackageManager(  905): Unknown permission com.htc.permission.ACCESS_VIDEO_CENTER in package com.htc.launcher
,W/PackageManager(  905): Unknown permission com.htc.framework.permission.NO_EXTERNAL_APPLICATIONS_AVAILABLE in package com.htc.launcher
W/PackageManager(  905): Unknown permission com.htc.cs.dm.permission.CONFIGURATION in package com.htc.launcher
,W/PackageManager(  905): Unknown permission com.htc.cs.dm.permission.NAMESPACE_CHANGE in package com.htc.launcher
W/PackageManager(  905): Not granting permission android.permission.INTERACT_ACROSS_USERS_FULL to package com.htc.zero (protectionLevel=2 flags=0x40983e45)
,W/PackageManager(  905): Unknown permission com.htc.permission.APP_HMS in package com.htc.zero
W/PackageManager(  905): Unknown permission com.htc.gc.companion.permission.LAUNCH_PICKER in package com.htc.zero
,W/PackageManager(  905): Unknown permission com.android.launcher.permission.PRELOAD_WORKSPACE in package com.google.android.partnersetup
W/PackageManager(  905): Unknown permission htc.permission.weather.USE_DATA in package com.htc
W/PackageManager(  905): Unknown permission com.htc.adwagent.permission.RECEIVE_ADW_COMMAND in package com.htc.soundrecorder
,W/PackageManager(  905): Unknown permission com.htc.adwagent.permission.ACCESS_ADW_PROVIDER in package com.htc.soundrecorder
W/PackageManager(  905): Unknown permission com.htc.permission.cloudstorage.vdisk.USE_CLOUD in package com.htc.FilePicker
W/PackageManager(  905): Unknown permission com.htc.permission.cloudstorage.skydrive.USE_CLOUD in package com.htc.FilePicker
W/PackageManager(  905): Unknown permission com.htc.cloudstorage.mygoogledrive.AUTH in package com.htc.FilePicker
W/PackageManager(  905): Unknown permission com.htc.cloudstorage.mygoogledrive.SYNC in package com.htc.FilePicker
W/PackageManager(  905): Unknown permission com.htc.uploader.permission.ACCESS_UPLOADER in package com.htc.FilePicker
W/PackageManager(  905): Unknown permission htc.pluginmanager.permission.USE_BROADCAST in package com.htc.task.gtask
W/PackageManager(  905): Unknown permission htc.pluginmanager.permission.USE_PROVIDER in package com.htc.task.gtask
,W/PackageManager(  905): Unknown permission com.android.settings.permission.ACCESS_SETTINGS in package com.htc.htcgpswidget
,W/PackageManager(  905): Unknown permission com.westtek.jcp.PRINT in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.CHAT_DATA_PROVIDER in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.SHOW_SHARED_FILES in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.BIND_SERVICE in package com.htc.contacts,
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.CHAT in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.NEW_CHAT in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.rcs.permission.RCS in package com.htc.contacts
,W/PackageManager(  905): Unknown permission com.fusionone.android.sync.permission.READ_WRITE_PROVIDERS in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.vcast.mediamanager.CLOUD_PERMISSION in package com.htc.contacts
W/PackageManager(  905): Unknown permission htc.opensense.permission.USE_SERVICE in package com.htc.contacts
W/PackageManager(  905): Unknown permission htc.friendstream.renrenwebplugin.permission.SYSTEM_USE in package com.htc.contacts,
W/PackageManager(  905): Unknown permission htc.socialmanager.permission.USE_SOCIALSERVICE in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.flickr.permission.useprovider in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.syncml.permission.READ_SYNCML_PROFILE in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.syncml.permission_attaddressbook in package com.htc.contacts,
W/PackageManager(  905): Unknown permission com.htc.HTCSpeaker.ACCESS_VR in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.vvm.permission.PLAY_VVM in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.album.permission.UseHtcGallery in package com.htc.contacts
W/PackageManager(  905): Unknown permission htc.socialmanager.permission.SOCIAL_HOST in package com.htc.contacts,
W/PackageManager(  905): Unknown permission com.htc.permission.vdmc.ACCESS_HTCDM_PROPERTY in package com.htc.contacts
W/PackageManager(  905): Unknown permission com.htc.visual_search.permission.FEATUREDB_ACCESS in package com.htc.album
W/PackageManager(  905): Unknown permission com.htc.rcschat.permission.SECURE_VIEW in package com.htc.album
W/PackageManager(  905): Unknown permission com.aiqidii.mercury.permission.READS in package com.htc.album,
W/PackageManager(  905): Unknown permission com.westtek.jcp.PRINT in package com.htc.calendar
W/PackageManager(  905): Unknown permission com.htc.permission.ACCESS_NOTES in package com.htc.calendar
W/PackageManager(  905): Unknown permission com.htc.demoflo.permission.RECEIVE_DEMOFLO_STATE in package com.htc.demoflopackageinstaller
W/PackageManager(  905): Unknown permission com.android.remotecontrolservice.REMOTE_CONTROL in package com.lmi.htc.rescue
,W/PackageManager(  905): Not granting permission android.permission.ACCOUNT_MANAGER to package com.htc.csrecommend (protectionLevel=2 flags=0x4088be45)
,W/PackageManager(  905): Unknown permission com.htc.cs.dm.permission.NAMESPACE_CHANGE in package com.htc.csrecommend
,W/PackageManager(  905): Unknown permission com.android.settings.permission.ACCESS_WIRELESS_DISPLAY in package com.htc.framework
,W/PackageManager(  905): Unknown permission com.htc.permission.cloudstorage.skydrive.USE_CLOUD in package com.htc.providers.uploads
,W/PackageManager(  905): Unknown permission com.htc.permission.ACCESS_VOWIFI in package com.android.systemui
,W/PackageManager(  905): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.android.systemui
,W/PackageManager(  905): Unknown permission htc.permission.weather.USE_DATA in package com.htc.AutoMotive
W/PackageManager(  905): Unknown permission com.htc.cs.dm.permission.CONFIGURATION in package com.htc.sense.socialnetwork.facebook
W/PackageManager(  905): Unknown permission com.htc.cs.dm.permission.NAMESPACE_CHANGE in package com.htc.sense.socialnetwork.facebook
,W/PackageManager(  905): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.youtube (protectionLevel=2 flags=0x98be45)
,W/PackageManager(  905): Unknown permission com.chrome.permission.DEVICE_EXTRAS in package com.android.chrome
W/PackageManager(  905): Unknown permission com.sec.enterprise.knox.MDM_CONTENT_PROVIDER in package com.android.chrome
,W/PackageManager(  905): Unknown permission com.htc.adwagent.permission.RECEIVE_ADW_COMMAND in package com.htc.android.worldclock
,W/PackageManager(  905): Unknown permission com.htc.adwagent.permission.ACCESS_ADW_PROVIDER in package com.htc.android.worldclock
W/PackageManager(  905): Unknown permission htc.permission.weather.USE_DATA in package com.htc.android.worldclock
,W/PackageManager(  905): Unknown permission htc.pluginmanager.permission.USE_PROVIDER in package com.htc.htcdlnamiddlelayer
W/PackageManager(  905): Unknown permission com.htc.adwagent.permission.RECEIVE_ADW_COMMAND in package com.htc.task
W/PackageManager(  905): Unknown permission com.htc.adwagent.permission.ACCESS_ADW_PROVIDER in package com.htc.task,
,W/PackageManager(  905): Unknown permission htc.permission.weather.USE_DATA in package com.htc.task
W/PackageManager(  905): Unknown permission android.permission.OBSERVE_GRANT_REVOKE_PERMISSIONS in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.RECOVERY in package com.google.android.gms
,W/PackageManager(  905): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gms (protectionLevel=2 flags=0x40483ec5)
W/PackageManager(  905): Unknown permission android.permission.PROVIDE_TRUST_AGENT in package com.google.android.gms
W/PackageManager(  905): Unknown permission com.google.android.apps.enterprise.dmagent.permission.AutoSyncPermission in package com.google.android.gms
W/PackageManager(  905): Not granting permission android.permission.PACKAGE_USAGE_STATS to package com.google.android.gms (protectionLevel=18 flags=0x40483ec5)
,W/PackageManager(  905): Unknown permission android.permission.MANAGE_VOICE_KEYPHRASES in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.REAL_GET_TASKS in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.READ_WIFI_CREDENTIAL in package com.google.android.gms
,W/PackageManager(  905): Unknown permission android.permission.SCORE_NETWORKS in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.CONTROL_INCALL_EXPERIENCE in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.USER_ACTIVITY in package com.google.android.gms
,W/PackageManager(  905): Unknown permission android.permission.MODIFY_AUDIO_ROUTING in package com.google.android.gms
W/PackageManager(  905): Unknown permission com.google.android.wearable.READ_SETTINGS in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.INTENT_FILTER_VERIFICATION_AGENT in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.LOCAL_MAC_ADDRESS in package com.google.android.gms
,W/PackageManager(  905): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.BODY_SENSORS in package com.google.android.gms
W/PackageManager(  905): Unknown permission android.permission.NOTIFY_PENDING_SYSTEM_UPDATE in package com.google.android.gms
W/PackageManager(  905): Unknown permission com.google.android.launcher.permission.RECEIVE_LAUNCH_BROADCASTS in package com.google.android.gms
,W/PackageManager(  905): Unknown permission com.android.voicemail.permission.READ_VOICEMAIL in package com.google.android.gms
,W/PackageSettings(  905): Skipping PackageSetting{4224e158 com.example.hello/10396} due to missing metadata
,I/ActivityManager(  905): Force stopping com.google.android.gms appid=10029 user=0: pkg removed
,D/AutoSetting( 4136): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:true
D/DotMatrix( 1523): [EventService] mPackageInfoReceiver.onReceive, packageName: com.google.android.gms
,D/DotMatrix( 1523): [EventService] mPackageInfoReceiver.onReceive, replacing: true, mCoverOn: false
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_ADDED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:true
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1245): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/Launcher( 1245): Deferring update until onResume
,D/Launcher( 1245): waitUntilResume // bindAppsUpdated
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,D/AutoSetting( 4136): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/AutoSetting( 4136): service - onCreate()
W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/AutoSetting( 4136): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4136): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
I/ActivityManager(  905): Start proc com.google.android.gms.persistent for service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker: pid=4643 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/PMS     (  905): acquireWL(42f11b38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4463 10111 null
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,W/dalvikvm( 4643): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/Babel   ( 4463): Gms package replaced. Will trigger a restart of babel
W/dalvikvm( 4643): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,D/AutoSetting( 4136): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
I/MultiDex( 4643): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4643): install
D/AutoSetting( 4136): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4136): service - mHandler: update timezone
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
,I/MultiDex( 4643): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/Finsky  ( 4514): [455] PackageManagerHelper$OnCompleteListenerNotifier$1.packageInstalled: Package install status for com.google.android.gms is 1
I/MultiDex( 4643): Detected that extraction must be performed.
I/MultiDex( 4643): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.dex of size 6208904
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/MultiDex( 4643): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.dex
,I/MultiDex( 4643): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.dex of size 8190552
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/MultiDex( 4643): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.dex
I/MultiDex( 4643): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip of size 2442399
I/MultiDex( 4643): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip
I/MultiDex( 4643): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.dex of size 7647536
I/MultiDex( 4643): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.dex
I/MultiDex( 4643): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip of size 2874084
I/MultiDex( 4643): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip
I/MultiDex( 4643): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip of size 2912239
I/MultiDex( 4643): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,D/Finsky  ( 4514): [1] InstallerTask$3.installSucceeded: Successful install of com.google.android.gms
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/AutoSetting( 4136): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4136): service - processTimeZoneID() system nitz is valid: false (false)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4514): Failed to ensure directory: /storage/ext_sd/Android/data/com.android.vending/files
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/[PluginManager]RegisterService( 4153): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.google.android.gms
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/[PluginManager]RegisterService( 4153): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
D/PMS     (  905): releaseWL(42f11b38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,I/MultiDex( 4643): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
,I/MultiDex( 4643): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes1411231898.zip
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/ActivityManager(  905): Resuming delayed broadcast
,D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Prism.PackageStateRece_( 1245): action: android.intent.action.PACKAGE_REMOVED
,D/AutoSetting( 4136): service - processTimeZoneID() single-timezone, pop up dialog
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4659 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/AutoSetting( 4136): service - showManualTimeZoneSelector() send notification (single)
W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,W/PackageManager(  905): Unable to load service info ResolveInfo{42505f30 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_ADDED
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REPLACED
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,W/PackageManager(  905): Unable to load service info ResolveInfo{43191900 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
,W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REPLACED dat=package: flg=0x4000010 (has extras) }
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/RemoteDisplayProvider(  905): start
,I/RemoteViews( 1108): com.htc.htclocationservice (true,33751552)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1535/10029)
D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41c538d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/RemoteViews.Performance( 1108): com.htc.htclocationservice 2 11 3 11
,W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4675 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4659/10100)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4659/10100)
W/GAV2    ( 4659): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(435a1f38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=2 [39][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): acquireWL(43b6ec48): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 905 1000 WorkSource{10029}
,I/ActivityManager(  905): Start proc com.google.android.gms for service com.google.android.gms/.people.sync.metadata.ContactMetadataSyncService: pid=4695 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0,
I/ActivityManager(  905): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  905): Resuming delayed broadcast
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022918
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273,
D/PMS     (  905): releaseWL(435a1f38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4707 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(424976e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
V/AlarmManager(  905): sending alarm PendingIntent{42514730: PendingIntentRecord{43c85e60 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449671270754, Int=0
D/PMS     (  905): releaseWL(424976e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,W/dalvikvm( 4695): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/AppTag  ( 4707): getInstance(Context context)
I/MultiDex( 4695): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4695): install
,I/MultiDex( 4695): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4695): Detected that extraction must be performed.
,D/AppTag  ( 4707): getInstance(Context context)
,D/AppTag  ( 4707): onCreate()
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(4206f2c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4244 10160 null
,D/PMS     (  905): releaseWL(4206f2c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/MultiDex( 4695): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
,I/MultiDex( 4695): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-1413202703.zip
,W/GAV2    ( 4659): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  905): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=4725 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/GservicesProvider( 4725): Gservices pushing to system: true; secure/global: true
,D/Process (  905): killProcessQuiet, pid=4313
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 4313:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4313
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4725): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4725): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4725): install
,I/MultiDex( 4725): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4725): Detected that extraction must be performed.
,I/MultiDex( 4725): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
,I/MultiDex( 4725): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes1213430542.zip
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 +
,I/Prism.WidgetManager( 1245): onLoadItems() +
,E/Prism.WidgetManager( 1245): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1245): onLoadItems() -
,I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 -
,D/PMS     (  905): acquireWL(43785050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10111}
V/AlarmManager(  905): sending alarm PendingIntent{425e17f8: PendingIntentRecord{423fd5f8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=144757, Int=259200000
,V/AlarmManager(  905): sending alarm PendingIntent{43c4e128: PendingIntentRecord{42611b58 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=146549, Int=0
,D/PMS     (  905): releaseWL(44182730): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/AutoSetting( 4153): service - handleMessage() stop self
,D/AutoSetting( 4153): service - handleMessage() quit looper
,D/AutoSetting( 4153): service - onDestroy() END
,I/MultiDex( 4643): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
I/MultiDex( 4643): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip: 2898044
,I/MultiDex( 4643): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
,I/MultiDex( 4643): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-1200431167.zip
,D/PhoneApp( 1216): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1216): -- N1 =0
,D/PhoneApp( 1216): -- N2 =0
,D/PhoneApp( 1216): -- N3 =0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/MultiDex( 4695): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
I/MultiDex( 4695): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip: 2898044
,I/MultiDex( 4695): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
,I/MultiDex( 4695): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-1361190094.zip
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,V/AlarmManager(  905): sending alarm PendingIntent{4239ad98: PendingIntentRecord{425a1c00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=148693, Int=0
,I/MultiDex( 4725): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
I/MultiDex( 4725): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip: 2898044
,I/MultiDex( 4725): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
,I/MultiDex( 4725): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-2082519113.zip
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4463/10111)
,I/GAV2    ( 4659): Thread[GAThread,5,main]: No campaign data found.
,I/MultiDex( 4643): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
,I/MultiDex( 4643): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip: 3409737
,I/MultiDex( 4643): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4643): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-836300479.zip
,I/MultiDex( 4695): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
I/MultiDex( 4695): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip: 3409737
,I/MultiDex( 4695): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4695): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-1391880718.zip
,I/MultiDex( 4725): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
I/MultiDex( 4725): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip: 3409737
,I/MultiDex( 4725): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4725): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes479359416.zip
,I/MultiDex( 4643): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4643): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip: 2767034
,I/MultiDex( 4643): load found 3 secondary dex files
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=153029, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4659/10100)
,I/MultiDex( 4695): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4725): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4695): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip: 2767034
,I/MultiDex( 4695): load found 3 secondary dex files
,I/MultiDex( 4725): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip: 2767034
,I/MultiDex( 4725): load found 3 secondary dex files
,E/cutils-trace( 4747): Error opening trace file: No such file or directory (2)
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC <<
,E/cutils-trace( 4748): Error opening trace file: No such file or directory (2)
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43190eb8 u0 com.htc.htclocationservice/.AutoSettingService}
,V/AlarmManager(  905): sending alarm PendingIntent{426746c0: PendingIntentRecord{43c85e60 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449671287567, Int=0
,I/MultiDex( 4643): install done
,I/MultiDex( 4695): install done
,I/MultiDex( 4725): install done
,W/dalvikvm( 4725): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4725): VFY: unable to resolve instance field 36
,W/dalvikvm( 4725): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4725): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/dalvikvm( 4643): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4643): VFY: unable to resolve instance field 36
,W/dalvikvm( 4643): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4643): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4725): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,I/ProviderInstaller( 4643): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4695): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4695): VFY: unable to resolve instance field 36
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 4695): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4643): Installer failed to acquire lock.
D/NativeLibraryUtils( 4643): java.io.IOException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 4643): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
D/NativeLibraryUtils( 4643): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:177)
D/NativeLibraryUtils( 4643): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:587)
D/NativeLibraryUtils( 4643): 	at com.google.android.gms.common.util.ay.b(SourceFile:335)
D/NativeLibraryUtils( 4643): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
D/NativeLibraryUtils( 4643): Caused by: libcore.io.ErrnoException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 4643): 	at libcore.io.Posix.fcntlFlock(Native Method)
D/NativeLibraryUtils( 4643): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:54)
D/NativeLibraryUtils( 4643): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
D/NativeLibraryUtils( 4643): 	... 4 more
,V/JNIHelp ( 4695): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4643): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4643): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4643): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4643): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/DeviceConnectionService( 4643): client connected with version: 8296000
,D/NativeLibraryUtils( 4725): Install completed successfully. count=14 extracted=0
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 1379: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,I/GCoreNlp( 4643): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,I/ProviderInstaller( 4695): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43c46260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43c46260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  905): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 4695): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4208a538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.android.contacts.metadata, SERVER, latestRunTime 145307, reason: ServiceChanged, SyncResult: databaseError: true stats []
,D/SyncManager(  905): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, SERVER, latestRunTime 162244, reason: ServiceChanged
D/PMS     (  905): releaseWL(43b6ec48): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
,D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/GAv4-SVC( 4695): Google Analytics 8.4.89 is starting up.
,D/NativeLibraryUtils( 4695): Install completed successfully. count=14 extracted=0
,W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
,D/Process (  905): killProcessQuiet, pid=4331
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4331:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4331
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1535/10029)
,D/PMS     (  905): releaseWL(4208a538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44050828): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(44050828): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/LocationProviderProxy(  905): applying state to connected service
,W/NetworkManagementSocketTagger( 4514): untagSocket(69) failed with errno -22
,D/Volley  ( 4514): [464] BasicNetwork.performRequest: HTTP response for request=<[ ] https://android.clients.google.com/vending/api/ApiRequest 0xe8d195d1 NORMAL 6 ContentSyncRequestProto> [lifetime=16671], [size=33], [rc=200], [retryCount=0]
,D/Finsky  ( 4514): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
,D/Finsky  ( 4514): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
,D/Finsky  ( 4514): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Finsky  ( 4514): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/LocationProviderProxy(  905): applying state to connected service
,D/PMS     (  905): acquireWL(430d0bb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=3787
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3787:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3787
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(430d0bb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 4695): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.gms
,I/PackageBroadcastService( 4695): Null package name or gms related package.  Ignoreing.
,D/GeofencerStateMachine( 4643): Creating GeofencerStateMachine
,D/ChimeraCfgMgr( 4695): Reading stored module config
,W/ChimeraCfgMgr( 4695): Stored Chimera config has different version (current=2,stored=1), ignoring
,D/WifiService(  905): New client listening to asynchronous messages
D/ChimeraCfgMgr( 4695): Reading stored module config
,W/ChimeraCfgMgr( 4695): Stored Chimera config has different version (current=2,stored=1), ignoring
,D/GmsModuleFndr( 4695): Beginning GMS chimera module scan
W/dalvikvm( 4695): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4695): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 4695): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4695): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/asset   ( 4695): Copying FileAsset 0x5c7a6430 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,W/dalvikvm( 4643): Link of class 'Lcom/google/android/gms/common/util/bo;' failed
E/dalvikvm( 4643): Could not find class 'com.google.android.gms.common.util.bo', referenced from method com.google.android.gms.common.util.bm.a
W/dalvikvm( 4643): VFY: unable to resolve new-instance 2494 (Lcom/google/android/gms/common/util/bo;) in Lcom/google/android/gms/common/util/bm;
,W/dalvikvm( 4643): Link of class 'Lcom/google/android/gms/common/util/bo;' failed
,D/ChimeraCfgMgr( 4695): Beginning module configuration check
,D/ChimeraCfgMgr( 4695): Reading stored module config
D/PMS     (  905): acquireWL(42eff098): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42eff098): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/ChimeraCfgMgr( 4695): Stored Chimera config has different version (current=2,stored=1), ignoring
,D/ChimeraModuleApk( 4695): Loading chimera manifest from InstalledApk(com.google.android.play.games)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{4205fc50: PendingIntentRecord{42552d48 com.google.android.gms startService}}) : type=2 triggerAtTime=315360162920 win=-1 tElapsed=315360162920 maxElapsed=551880162917 interval=0 standalone=false
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023092
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.games,v34120000) from InstalledApk(com.google.android.play.games)
,D/ChimeraFileApk( 4695): Loading chimera manifest from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.maps,v8301000) from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk)
,D/ChimeraModuleApk( 4695): Loading chimera manifest from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.cast,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.games,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.gass,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.piccard,v1) from ContainerApk(com.google.android.gms)
,D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.vision,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgRslvr( 4695): Beginning module config resolution
D/ChimeraCfgRslvr( 4695): module(built-in,v0) has no external dependencies, accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.cast,v1) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.games,v34120000) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.gass,v1) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.kids,v3) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.maps,v8301000) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.piccard,v1) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.vision,v1) accepted
,D/ChimeraCfgRslvr( 4695): Module config resolution complete
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Loading module APK com.google.android.play.games
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 1377: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 4695): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 4695): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
W/dalvikvm( 4695): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/PMS     (  905): acquireWL(43c86dc0): PARTIAL_WAKE_LOCK  Icing 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{420c0010: PendingIntentRecord{4253ab30 com.google.android.gms startService}}) : type=2 triggerAtTime=315360163072 win=-1 tElapsed=315360163072 maxElapsed=551880163069 interval=0 standalone=false
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023194
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,D/PMS     (  905): acquireWL(4383f220): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 4695): Storage manager: low false usage 2.00MB avail 8.65GB capacity 9.23GB
,D/GCM     ( 4725): COMPAT: Multi user not supported
,W/dalvikvm( 4725): VFY: unable to resolve instance field 161
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
V/GeofencerHelper( 4643): Initializing geofence's system cache.
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/PMS     (  905): acquireWL(438fb7e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/GeofenceStateCache( 4643): Recovered 0 geofences.
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{430bfb60: PendingIntentRecord{4237bea8 com.google.android.gms startService}}) : type=2 triggerAtTime=315360163221 win=-1 tElapsed=315360163221 maxElapsed=551880163220 interval=0 standalone=false
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023197
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{433033d0: PendingIntentRecord{42292910 com.google.android.gms startService}}) : type=2 triggerAtTime=315360163232 win=-1 tElapsed=315360163232 maxElapsed=551880163231 interval=0 standalone=false
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023201
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,E/NetworkScheduler.SchedulerReceiver( 4725): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 4725): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{430bf968: PendingIntentRecord{420bc328 com.google.android.gms startService}}) : type=2 triggerAtTime=315360163241 win=-1 tElapsed=315360163241 maxElapsed=551880163241 interval=0 standalone=false
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,D/LocationManagerService(  905): request 436f3900 passive Request[POWER_NONE passive fastest=0] from com.google.android.gms(10029)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,I/GeofencerStateMachine( 4643): Network location disabled.
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
,D/PMS     (  905): acquireWL(4410ae40): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4463 10111 null
,W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4695): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4695): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/j/c;' failed
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{4409c170: PendingIntentRecord{440950f8 com.google.android.gms startService}}) : type=2 triggerAtTime=315360163296 win=-1 tElapsed=315360163296 maxElapsed=551880163296 interval=0 standalone=false
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 1398: Landroid/os/UserHandle;.isOwner ()Z
,W/Babel   ( 4463): Gms package replaced. Will trigger a restart of babel
I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  905): releaseWL(438fb7e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4410ae40): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,W/IcingInternalCorpora( 4695): getNumBytesRead when not calculated.
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4808 uid=10032 gids={50032, 3003, 5012}
,D/PMS     (  905): releaseWL(4383f220): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44066848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44066848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 1203: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/WearableService( 4643): callingUid 10029, callindPid: 4643
E/dalvikvm( 4643): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
,W/dalvikvm( 4643): VFY: unable to resolve check-cast 516 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,W/dalvikvm( 4643): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 4153): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4153): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1245): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  905): Resuming delayed broadcast
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@438f6de0:true
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/IcingCorporaProvider( 2555): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4826 uid=10098 gids={50098, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=3801
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 3801:com.android.settings:remote/1000 (adj 15): empty #17
,D/PMS     (  905): acquireWL(43c7f2d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Recipient 3801
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,E/GmsWearableNodeHelper( 4643): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/PMS     (  905): releaseWL(43c7f2d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/DeviceManagement( 4826): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4826 dbg=false s=true
,D/PMS     (  905): acquireWL(43b87ff0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 4643 10029 null
,I/Icing   ( 4695): updateResources: need to parse f{com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=4299
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4845 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Killing 4299:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4299
,W/dalvikvm( 4643): VFY: unable to find class referenced in signature (Lcom/android/location/provider/ActivityChangedEvent;)
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 3610: Lcom/android/location/provider/ActivityChangedEvent;.getActivityRecognitionEvents ()Ljava/lang/Iterable;
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/htcbackup-core( 4845): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 4845): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
W/ContextImpl( 4845): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/Icing   ( 4695): Removing corpus key 31323E6206FB8147FEA27FFA377F075022B8831A for package com.google.android.gms
,I/DeviceManagement( 4826): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 4826): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.qualcomm.timeservice, com.htc.backup, com.qualcomm.privinit, com.htc.android.htcloglevel, com.htc.feedback, com.htc.cirmodule, com.htc.home.personalize, com.htc.lockscreen, com.htc.backupreset, com.htc.guide, android, com.android.settings, com.android.providers.settings, com.htc.android.htcsetupwizard, com.htc.drive.activator, com.htc.smartdim, com.htc.mirrorlinkserver, com.android.CSDFunctionG, com.htc.usage, com.htc.htcpowermanager, com.htc.autobot.cargps.provider, com.htc.checkinprovider, com.android.location.fused, com.android.keychain, com.android.inputdevices]
I/ActivityManager(  905): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4861 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  905): killProcessQuiet, pid=4363
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/DeviceManagement( 4826): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/ActivityManager(  905): Killing 4363:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4363
,I/DeviceManagement( 4826): WorkflowService: Starting workflow service
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 4826): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b51190] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 4826): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 4826): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4826): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4826): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 4861):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  905): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,D/PMS     (  905): acquireWL(438e98c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(438e98c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationManagerService_CarGps(  905): addGpsStatusListener to CarGpsProvider
,D/LocationManagerService(  905): request 43beec18 passive Request[POWER_NONE passive fastest=0] from com.google.android.gms(10029)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,W/Settings( 4643): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43b87ff0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=4 [25][1][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
D/PMS     (  905): acquireWL(4378aa60): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 4643 10029 null
D/PMS     (  905): releaseWL(4378aa60): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,I/DeviceManagement( 4826): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 4826): SessionStateController: Checking invariants...
,I/DeviceManagement( 4826): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4826): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b51190]
,I/DeviceManagement( 4826): WorkflowService: Stopping workflow service
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(435ed398): PARTIAL_WAKE_LOCK  AsyncService 0x1 4244 10160 null
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): releaseWL(435ed398): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 4695): Internal init done: storage state 0
,D/Finsky  ( 4514): [1] GmsCoreHelper$GMSCoreNotifier$1.run: Set autoupdate of com.google.android.gms to 1 (install/update)
I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 4695): Post-init done
,I/Icing   ( 4695): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/Babel   ( 4463): Gms package replaced. Will trigger a restart of babel
D/PMS     (  905): acquireWL(43186480): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4463 10111 null
I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  905): releaseWL(43186480): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4393
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4393:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/[PluginManager]RegisterService( 4153): onHandleIntent, action: android.intent.action.PACKAGE_REPLACED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4153): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Recipient 4393
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.nero.android.htc.sync.installer for broadcast com.nero.android.htc.sync.installer/.OnNeroHTCUpgradeReceiver: pid=4884 uid=10072 gids={50072}
,D/OnNeroHTCUpgradeReceiver( 4884): received android.intent.action.PACKAGE_REPLACED data: package:com.google.android.gms
,I/ActivityManager(  905): Killing 4426:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4426
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/DeviceManagement( 4826): PackageUpdateReceiver: vvv Package replaced: [com.google.android.gms]
,I/DeviceManagement( 4826): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.google.android.gms, operation=2}]]
,I/DeviceManagement( 4826): WorkflowService: Starting workflow service
,I/DeviceManagement( 4826): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41cee970] args=[Bundle[mParcelledData.dataSize=128]]
I/DeviceManagement( 4826): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4826): PackageUpdateWorkflow: Package update: package=com.google.android.gms, operation=REPLACE
,I/DeviceManagement( 4826): PackageUpdateWorkflow: ==================================================
,I/ActivityManager(  905): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 4826): BackgroundController: *** Processing package change for appID=com.google.android.gms
,I/DeviceManagement( 4826): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.google.android.gms
,I/DeviceManagement( 4826): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41cee970]
,I/DeviceManagement( 4826): WorkflowService: Stopping workflow service
,I/ActivityManager(  905): Resuming delayed broadcast
,W/HtcCupdReceiver(Provider)( 4861):  @@@@@ Don't handle this action=android.intent.action.PACKAGE_REPLACED
D/KidModeUpgradeReceiver( 4707): Receive upgrade package:com.google.android.gms
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=4899 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  905): Recipient 4426
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4899): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4899): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4899): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4899): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4899): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4899/10151)
,V/WebViewChromiumFactoryProvider( 4899): Binding Chromium to main looper Looper (main, tid 1) {41b1f210}
,I/LibraryLoader( 4899): Expected native library version number "",actual native library version number ""
,I/chromium( 4899): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4899): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(4207a778): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  905): acquireWL(420c9480): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4899): BLUETOOTH permission is missing!
D/PMS     (  905): releaseWL(420c9480): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4899): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4899): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4899): Local Branch: 
I/Adreno-EGL( 4899): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4899): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4899):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4899): Starting up...
,D/Process (  905): killProcessQuiet, pid=4486
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4486:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/PackageBroadcastService( 4695): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.gms
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/GmsModuleFndr( 4695): Beginning GMS chimera module scan
W/asset   ( 4695): Copying FileAsset 0x5cae3bc0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,D/ChimeraCfgMgr( 4695): Beginning module configuration check
D/ChimeraCfgMgr( 4695): Module APKs unchanged, check complete
,I/PackageBroadcastService( 4695): Null package name or gms related package.  Ignoreing.
,W/dalvikvm( 4695): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,I/ActivityManager(  905): Recipient 4486
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/FileApkUtils( 4695): Spent 20ms computing apk sha1.
,D/FileApkUtils( 4695): Spent 24ms copying apk.
,D/FileApkUtils( 4695): Copied dynamite bytes to /data/data/com.google.android.gms/app_chimera/chimera-module-root/scratch-module-dir/MapsModule.apk
,D/FileApkUtils( 4695): Spent 4ms extracting native libraries.
D/DexOptUtils( 4695): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 4695): Pre-lollipop platform, odex will live alongside the dex.
D/DexOptUtils( 4695): Instantiating DexClassLoader to force creation of odex.
,D/DexOptUtils( 4695): Primary ABI of odexing process is armeabi-v7a
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,E/DynamiteModule( 4695): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 4695): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 4695): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 4695): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 4695): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 4695): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 4695): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 4695): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 4695): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 4695): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 4695): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:72)
E/DynamiteModule( 4695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DynamiteModule( 4695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 4695): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 4695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DynamiteModule( 4695): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 4695): Selected local version of com.google.android.gms.flags
,D/Icing   ( 4695): Loaded CLD2 Version V2.0 - 20141016
,D/DexOptUtils( 4695): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.dex
,D/DexOptUtils( 4695): Set odex to world readable.
D/DexOptUtils( 4695): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.odex
D/FileApkUtils( 4695): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/FileApkUtils( 4695): Deleting stale module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 4695): Beginning GMS chimera module scan
,W/asset   ( 4695): Copying FileAsset 0x5cadd970 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
,D/ChimeraCfgMgr( 4695): Beginning module configuration check
,D/ChimeraModuleApk( 4695): Loading chimera manifest from InstalledApk(com.google.android.play.games)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.games,v34120000) from InstalledApk(com.google.android.play.games)
,D/ChimeraFileApk( 4695): Loading chimera manifest from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.maps,v8489000) from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk)
,D/ChimeraModuleApk( 4695): Loading chimera manifest from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
,D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.cast,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.games,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.gass,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.piccard,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4695): Considering module(com.google.android.gms.vision,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgRslvr( 4695): Beginning module config resolution
,D/ChimeraCfgRslvr( 4695): module(built-in,v0) has no external dependencies, accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.cast,v1) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.games,v34120000) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.gass,v1) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.kids,v3) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.maps,v8489000) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.piccard,v1) accepted
D/ChimeraCfgRslvr( 4695): module(com.google.android.gms.vision,v1) accepted
,D/ChimeraCfgRslvr( 4695): Module config resolution complete
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/ActivityManager(  905): Resuming delayed broadcast
,D/AsyncTaskServiceImpl( 4695): Submit a task: k
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 4695): Processing package: com.google.android.gms
I/ActivityManager(  905): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,D/d       ( 4695): Database will be upgraded from 1 to 2
,D/d       ( 4695): Database upgraded to 2
,D/b       ( 4695): Look up (com.google.android.gms:8489036) returned no result
,D/k       ( 4695): Starting Hash for package com.google.android.gms:8.4.89 (2428711-036)
,D/k       ( 4695): Package com.google.android.gms's hash: a05ba025b6e6b4a49692d64a578be94965f04b9c510b10e0363a9fa4f9300b4e
,D/b       ( 4695): Look up (com.google.android.gms:8489036) returned no result
,D/k       ( 4695): Saved the app info in cache for package:com.google.android.gms.
,I/ActivityManager(  905): Resuming delayed broadcast
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/dalvikvm( 4643): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4643): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4643): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 4643): Using platform SSLCertificateSocketFactory
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 1401: Landroid/os/UserManager;.isManagedProfile ()Z
,I/PhenotypeConfigurator( 4643): Scheduling Phenotype for one-off execution 7903 seconds from now (1449671294356)
,W/InstanceID/Rpc( 4695): Found 10029
,W/InstanceID/Rpc( 4643): Found 10029
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
E/NetworkScheduler.SchedulerReceiver( 4725): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 4725): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  905): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
D/PMS     (  905): acquireWL(432fd280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(432fd280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/InstanceID/Rpc( 4725): Found 10029
,D/WifiService(  905): New client listening to asynchronous messages
,I/ActivityManager(  905): Resuming delayed broadcast
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 1512: Landroid/os/UserHandle;.isOwner ()Z
,I/PlatformStatsCollectorService( 4695): Start Settingsstats in 48396 seconds.
,I/PlatformStatsCollectorService( 4695): Start Dropbox in 79927 seconds.
,I/PlatformStatsCollectorService( 4695): Start Graphicsstats in 41613 seconds.
,I/PlatformStatsCollectorService( 4695): Start Fingerprintstats in 36975 seconds.
,I/PlatformStatsCollectorService( 4695): Start Procstats in 44114 seconds.
D/PMS     (  905): releaseWL(4207a778): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PlatformStatsCollectorService( 4695): Start Diskstats in 14575 seconds.
,I/PlatformStatsCollectorService( 4695): Start Notificationstats in 82236 seconds.
,I/PlatformStatsCollectorService( 4695): Start Netstats in 52615 seconds.
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
,W/asset   ( 4695): Copying FileAsset 0x5ca51df8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
,I/Icing   ( 4695): Indexing 3A8460E5C0632136E92B96392CBF2576E3D763BC from com.google.android.gms
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Icing   ( 4695): Indexing done 3A8460E5C0632136E92B96392CBF2576E3D763BC
,I/Icing   ( 4695): Indexing 109AFACE3A5344FDC3CF3805F5627D6A4D70525E from com.google.android.gms
,I/Icing   ( 4695): Indexing done 109AFACE3A5344FDC3CF3805F5627D6A4D70525E
,I/Icing   ( 4695): Indexing B0245FC6BB403F15105078251A01C8228A24A8C7 from com.google.android.gms
,I/Icing   ( 4695): Indexing done B0245FC6BB403F15105078251A01C8228A24A8C7
,I/Icing   ( 4695): Indexing E6D59F9FF0A2AF033E5C42092164416BD59759EF from com.google.android.gms
,I/Icing   ( 4695): Indexing done E6D59F9FF0A2AF033E5C42092164416BD59759EF
,I/PerfProfileCollectorService( 4695): Scheduling Perf Profile Collection every 86400 seconds
,I/StatsUploadService( 4695): Turn off alarms uploading
,I/StatsUploadService( 4695): Turn off networkusage uploading
,I/StatsUploadService( 4695): Turn off wakelocks uploading
,I/StatsUploadService( 4695): Turn off internal_service_connections uploading
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4967 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoTaskReceiver
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027273
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(43ca1208): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4463 10111 null
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  905): releaseWL(43ca1208): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/Icing   ( 4695): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4618
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/PMS     (  905): acquireWL(43701110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43785050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Killing 4618:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 4618
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(43701110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 1203: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.tapandpay.hce.service.TpHceService, state=2, flag=1, pid=4643, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.tapandpay.config.UpgradeNfcWalletReceiver, state=2, flag=1, pid=4643, uid=10029, userID:0
,E/MDM     ( 4643): [496] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 4725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,E/AuthorizationBluetoothService( 4725): Proximity feature is not enabled.
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Scheduler( 4695): Use legacy PeriodicScheduler
,I/Icing   ( 4695): updateResources: need to parse f{com.google.android.gms}
,D/GmsModuleFndr( 4695): Beginning GMS chimera module scan
,W/asset   ( 4695): Copying FileAsset 0x5cabbdb8 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
,D/ChimeraCfgMgr( 4695): Beginning module configuration check
,D/ChimeraCfgMgr( 4695): Module APKs unchanged, check complete
E/dalvikvm( 4695): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 4695): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 4695): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 4695): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 4695): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{43b4bb58: PendingIntentRecord{4260ed10 com.google.android.gms startService}}) : type=2 triggerAtTime=315360168559 win=-1 tElapsed=315360168559 maxElapsed=551880168557 interval=0 standalone=false
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Auth    ( 4725): [Change,LoginAccountsChangedIntentService] LoginAccountsChangedIntentService received unknown action: com.google.android.gms.auth.change.REFRESH
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4695/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,E/dalvikvm( 4643): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 4643): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 4643): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 4643): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 4643): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 4643): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 4643): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 4643): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/GCM     ( 4695): COMPAT: Multi user not supported
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,I/PeopleDatabaseHelper( 4695): Upgrading from version 700 to 1405
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/PMS     (  905): acquireWL(43160ea0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 4725): GcmService start Intent { act=com.google.android.gms.GMS_UPDATED cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.GMS_UPDATED
D/libc    ( 4725): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/libc    ( 4725): [NET] getaddrinfo-,err=8
D/libc    ( 4725): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 4725): [NET] getaddrinfo-, 1
D/libc    ( 4725): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =143e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4725): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4725): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 4725): [NET] getaddrinfo-,err=8
,W/dalvikvm( 4695): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 4695): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 4695): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 4695): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/FileApkUtils( 4695): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 4695): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 4695): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/GmsModuleFndr( 4695): Beginning GMS chimera module scan
,W/asset   ( 4695): Copying FileAsset 0x65a4b9c0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
,D/ChimeraCfgMgr( 4695): Beginning module configuration check
,V/AuthZen ( 4695): Handling intent: com.google.android.gms.GMS_UPDATED
,D/ChimeraCfgMgr( 4695): Module APKs unchanged, check complete
D/libc    ( 4725): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 4725): [NET] getaddrinfo-,err=8
,E/MDM     ( 4643): [507] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4695, uid=10029, userID:0
,I/LocationInitializer( 4695): Initializing location.
,D/LocationInitializer( 4695): Location services disabled.
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
I/GCM     ( 4725): GCM config loaded
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=4695, uid=10029, userID:0
,D/GCM     ( 4725): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,I/PeopleDatabaseHelper( 4695): cleanUpNonGplusAccounts done.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/AuthZenEventHandler( 4695): Handling event: com.google.android.gms.GMS_UPDATED
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,I/PeopleSync( 4695): requestContactSyncCleanup [5005f081]
D/AuthorizationBluetoothService( 4725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 4725): Proximity feature is not enabled.
I/DatabaseHelper( 4643): Upgrade database: oldVersion=3 newVersion=4
,I/DatabaseHelper( 4643): Indexing LogEvents by PlayLoggerContext id
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 4695): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4695): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/GMPM-SVC( 4695): Update service enabled state to: 1
,W/dalvikvm( 4695): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,E/BaseAppContext( 4695): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.measurement.AppMeasurementService, state=1, flag=1, pid=4695, uid=10029, userID:0
,D/PMS     (  905): acquireWL(41feec70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,I/Icing   ( 4695): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  905): acquireWL(420814e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.people/com.google/***** 0x1 905 1000 WorkSource{10029}
,D/PMS     (  905): releaseWL(41feec70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(42fa8c68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4725): [NET] getaddrinfo-,err=8
D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4725): [NET] getaddrinfo-, 1
,D/libc    ( 4725): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9056 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4725): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42ea0308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42ea0308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/MDM     ( 4643): [512] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/PMS     (  905): releaseWL(43160ea0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (4725/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4725): [NET] getaddrinfo-,err=8
,I/AuthZen ( 4695): Fetching signing key...
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4695, uid=10029, userID:0
D/PMS     (  905): releaseWL(42fa8c68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4695, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
D/AuthorizationBluetoothService( 4725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 4725): Proximity feature is not enabled.
D/PMS     (  905): acquireWL(43c63ff8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (4725/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/PMS     (  905): acquireWL(42e951a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/libc    ( 4725): [NET] getaddrinfo-,err=8
I/AuthZen ( 4695): Signing key fetched successfully!
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,I/PeopleSync( 4695): onPerformSync() [5005f081]
D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4725): [NET] getaddrinfo-,err=8
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (4725/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/PMS     (  905): acquireWL(423d3a80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.reminders/com.google/***** 0x1 905 1000 WorkSource{10029}
E/dalvikvm( 4695): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 4695): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,D/PMS     (  905): releaseWL(43c63ff8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42e951a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
D/PMS     (  905): acquireWL(42f6f7f8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,I/PlatformStatsCollectorService( 4695): Start Settingsstats in 27049 seconds.
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,I/PlatformStatsCollectorService( 4695): Start Dropbox in 44458 seconds.
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
D/PMS     (  905): releaseWL(42f6f7f8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,I/PlatformStatsCollectorService( 4695): Start Graphicsstats in 25204 seconds.
,I/Scheduler( 4643): Use legacy PeriodicScheduler
,I/PlatformStatsCollectorService( 4695): Start Fingerprintstats in 46356 seconds.
,D/GmsModuleFndr( 4695): Beginning GMS chimera module scan
,W/asset   ( 4695): Copying FileAsset 0x66cd4008 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43c45a00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/ChimeraCfgMgr( 4695): Beginning module configuration check
,D/ChimeraCfgMgr( 4695): Module APKs unchanged, check complete
,D/SystemEventReceiver( 4695): Received GMS_UPDATE broadcast
,D/PMS     (  905): releaseWL(43c45a00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/PlatformStatsCollectorService( 4695): Start Procstats in 56779 seconds.
,I/OcrUtils( 4695): Updating ocr activity enabled=false
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=4695, uid=10029, userID:0
,I/PlatformStatsCollectorService( 4695): Start Diskstats in 81483 seconds.
,I/PlatformStatsCollectorService( 4695): Start Notificationstats in 38844 seconds.
,I/MDM     ( 4695): [551] SitrepService.onHandleIntent: sending sitrep: [6, 0, [mHHhgfM5wK0KEYtCfO7a2vkYIYg], null]
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
,I/PlatformStatsCollectorService( 4695): Start Netstats in 24515 seconds.
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PeopleSync( 4695): Setting subscription: result=true [5005f081]
,I/PeopleSync( 4695): Starting sync, feed=null [5005f081]
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 4695): [551] a.<init>: mAccountName set to: thalitester@gmail.com
,I/PeopleContactsSync( 4695): CP2 sync start [5005f081]
,I/Icing   ( 4695): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(422ab2b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
D/PMS     (  905): releaseWL(423d3a80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.reminders/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  905): releaseWL(422ab2b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/Icing   ( 4695): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
D/BootCompletedReceiver( 4695): Will schedule periodic tasks:com.google.android.gms.GMS_UPDATED.
D/BootCompletedReceiver( 4695): Got a GmsCore update event.
D/BootCompletedReceiver( 4695): Will NOT schedule AdAttestation signal task because it's disabled.
I/Icing   ( 4695): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,W/ActivityManager(  905): Unable to start service Intent { act=com.google.android.gms.GMS_UPDATED pkg=com.google.android.gms } U=0: not found
,I/PhenotypeConfigurator( 4643): Scheduling Phenotype for one-off execution 5025 seconds from now (1449671296269)
,D/OcrModelManager( 4695): Updating downloaded model state (gcore updated)
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
,D/AuthorizationBluetoothService( 4725): Received GmsCore event: Intent { act=com.google.android.gms.GMS_UPDATED flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 4725): Proximity feature is not enabled.
,D/PMS     (  905): acquireWL(420799f0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 4725 10029 null
,I/PeopleContactsSync( 4695): CP2 cleanup done, kept= duration=118 ms
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,D/c       ( 4695): Creating table: affiliation
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=com.google.android.gms.GMS_UPDATED flg=0x10 pkg=com.google.android.gms } from com.android.vending (pid=4514, uid=10074) is not exported from uid 10029 due to receiver com.google.android.gms/.chromesync.sync.SyncReceiverService$Receiver
,D/PMS     (  905): acquireWL(4361cea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4361cea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(425ae7b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/PMS     (  905): releaseWL(425ae7b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 4695): Using Auth Proxy for data requests.
D/PMS     (  905): acquireWL(420c3cd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
D/PMS     (  905): releaseWL(420c3cd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PerfProfileCollectorService( 4695): Scheduling Perf Profile Collection every 86400 seconds
,I/PhenotypeConfigurator( 4695): Scheduling Phenotype for one-off execution 11987 seconds from now (1449671296414)
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
W/ActivityManager(  905): Unable to start service Intent { act=INITIALIZE_SUBSCRIPTIONS cmp=com.google.android.gms/.nearby.sharing.NearbySharingIntentService } U=0: not found
,D/WearInitializer( 4695): Running WearInitializer
,D/WearInitializer( 4695): enabled .WearableService
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wearable.service.WearableService, state=1, flag=1, pid=4695, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=1, flag=1, pid=4695, uid=10029, userID:0
,I/GAV2    ( 4899): Thread[GAThread,5,main]: No campaign data found.
,I/Icing   ( 4695): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 4695): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
,D/PMS     (  905): acquireWL(42530ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,I/PeopleContactsSync( 4695):   updateBabelActionMimeType
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(420799f0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/IcingInternalCorpora( 4695): getNumBytesRead when not calculated.
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(42530ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 4725): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 4725): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42602308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4725): [NET] getaddrinfo-,err=8
D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4725): [NET] getaddrinfo-, 1
,D/libc    ( 4725): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a079 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
I/PeopleContactsSync( 4695): Updated babel action mime type
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4725): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43c86dc0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(41e93808): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/PMS     (  905): acquireWL(42c0b940): PARTIAL_WAKE_LOCK  Icing 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42602308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1108): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4725): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4261f368): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): acquireWL(43a95900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4261f368): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4725): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [4][0][0]
I/PeopleContactsSync( 4695): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(420a3cb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4725): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(420a3cb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): releaseWL(42c0b940): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PeopleContactsSync( 4695): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/PhoneStatusBar( 1108): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,D/PMS     (  905): acquireWL(42631a80): PARTIAL_WAKE_LOCK  Icing 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,D/LocationInitializer( 4695): Restart initialization of location
D/PMS     (  905): releaseWL(43a95900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42631a80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 4695): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.gms.lockbox.LockboxService.a
,W/dalvikvm( 4695): VFY: unable to resolve check-cast 61 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/gms/lockbox/LockboxService;
D/PMS     (  905): acquireWL(43aefd90): PARTIAL_WAKE_LOCK  Icing 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4695, uid=10029, userID:0
,D/PMS     (  905): releaseWL(43aefd90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4267e850): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42a355b0): PARTIAL_WAKE_LOCK  Icing 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
,D/AccFlag ( 1216): sku_id=99
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/LocationInitializer( 4695): Restart initialization of location
D/PMS     (  905): releaseWL(42a355b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,D/PMS     (  905): releaseWL(4267e850): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationInitializer( 4695): Restart initialization of location
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 42
,D/AccFlag ( 1216): sku_id=99
,D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,D/AccFlag ( 1216): sku_id=99
,I/PeopleContactsSync( 4695): CP2 cleanup done, kept= duration=135 ms
,W/IcingInternalCorpora( 4695): getNumBytesRead when not calculated.
I/PeopleContactsSync( 4695): ===CP2 sync finished, success=true, time=2014,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
D/TelephUtils( 1216): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 42
,D/AccFlag ( 1216): sku_id=99
D/PMS     (  905): acquireWL(43c3b9f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(431dacc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,I/IcingCorporaProvider( 2555): UpdateCorporaTask done [took 7792 ms] updated apps [took 7792 ms] 
,D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1535/10029)
D/PMS     (  905): releaseWL(431dacc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43b75bd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  905): releaseWL(43c3b9f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(41e93808): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  905): releaseWL(43b75bd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/InstanceID/Rpc( 4695): Found 10029
,E/dalvikvm( 4643): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 4643): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,I/PeopleSync( 4695): ***Sync finished***, duration: 2320 [5005f081]
,D/PMS     (  905): acquireWL(42f6f5b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(43c1af28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,I/IntentController( 1108): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(420814e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.people/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  905): releaseWL(43c1af28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,D/PMS     (  905): releaseWL(42f6f5b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43a95410): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426661a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PhoneStatusBar( 1108): removeIcon slot=sync_active index=7 viewIndex=0
D/libc    ( 4695): [NET] getaddrinfo+,hn 22(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4695): [NET] getaddrinfo-,err=8
D/libc    ( 4695): [NET] getaddrinfo+,hn 22(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4695): [NET] getaddrinfo-, 1
D/libc    ( 4695): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =18c4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,D/PMS     (  905): releaseWL(426661a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440fe8c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=90
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 4695): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{4261bbc0: PendingIntentRecord{43c74b80 com.google.android.gms startService}}) : type=2 triggerAtTime=315360171432 win=-1 tElapsed=315360171432 maxElapsed=551880171431 interval=0 standalone=false
,D/PMS     (  905): releaseWL(440fe8c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4695): [NET] getaddrinfo+,hn 22(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4695): [NET] getaddrinfo-,err=8
E/dalvikvm( 4643): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.gms.lockbox.LockboxService.a
,W/dalvikvm( 4643): VFY: unable to resolve check-cast 61 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/gms/lockbox/LockboxService;
,D/PMS     (  905): acquireWL(43435e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43435e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43b72c10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 11: Landroid/accounts/AccountManager;.getPreviousName (Landroid/accounts/Account;)Ljava/lang/String;
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43b72c10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4695): [NET] getaddrinfo+,hn 22(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4695): [NET] getaddrinfo-,err=8
D/libc    ( 4695): [NET] getaddrinfo+,hn 22(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4695): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(43b94e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43b94e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42ea0188): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/GCoreFlp( 4643): No location to return for getLastLocation()
,W/FusedLocationProvider( 4643): location=null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(4260c7d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4260c7d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,W/GCoreFlp( 4643): No location to return for getLastLocation()
,W/FusedLocationProvider( 4643): location=null
,W/GeofencerStateMachine( 4643): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(433fb948): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(433fb948): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
D/PMS     (  905): acquireWL(43c62408): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
D/PMS     (  905): releaseWL(43c62408): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/ctxmgr  ( 4643): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
D/PMS     (  905): releaseWL(42ea0188): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(430af6e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/GCoreFlp( 4643): No location to return for getLastLocation()
,W/FusedLocationProvider( 4643): location=null
D/PMS     (  905): acquireWL(43c8dc18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
D/PMS     (  905): releaseWL(43c8dc18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(430af6e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4308f828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,I/MDM     ( 4695): [551] SitrepService.onHandleIntent: Sitrep successful
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=2, flag=1, pid=4695, uid=10029, userID:0
,W/ctxmgr  ( 4643): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 4643): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,D/PMS     (  905): releaseWL(4308f828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43a95410): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c918b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(43c918b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(437a14c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(437a14c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f01670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(42f01670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43667120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43667120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43654298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43654298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4695/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): acquireWL(43096170): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(430c52f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(430c52f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(433b42d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(433b42d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43096170): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43b47670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43b47670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4379a738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4379a738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4263e190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0],
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4263e190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4334c2b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4334c2b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43becdf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(43becdf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(436d3b58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(436d3b58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c554c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43c554c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(438402a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(438402a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44034710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(44034710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/PMS     (  905): acquireWL(43489b88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=5095 uid=10041 gids={50041}
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43489b88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4410fe70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(4410fe70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4409d188): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4409d188): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44066898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/PlaySystemBroadcastReceiver( 4695): Processed handlePeopleChanged at 173025
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/DataBroker( 4695): No player ID found and calling context is not the dest app
,D/PMS     (  905): releaseWL(44066898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 499: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(440029a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(440029a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 4136): service - handleMessage() stop self
,D/AutoSetting( 4136): service - onDestroy() END
,D/AutoSetting( 4136): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4136
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4136:com.htc.bgp/u0a14 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4136
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1245): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Launcher( 1245): Deferring update until onResume
,D/Launcher( 1245): waitUntilResume // bindAppsUpdated
D/PMS     (  905): acquireWL(438f9078): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4463 10111 null
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,I/[PluginManager]RegisterService( 4153): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4153): handle notify Blinkfeed plugin client changed
D/PMS     (  905): acquireWL(41d3d768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10111}
V/AlarmManager(  905): sending alarm PendingIntent{42067698: PendingIntentRecord{4242cac8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=164388, Int=259200000
D/PMS     (  905): releaseWL(438f9078): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
V/AlarmManager(  905): sending alarm PendingIntent{41d5d710: PendingIntentRecord{424eaec0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=175467, Int=0
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/IcingCorporaProvider( 2555): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  905): acquireWL(42ef70c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4244 10160 null
D/PMS     (  905): releaseWL(42ef70c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  905): acquireWL(424f90e0): PARTIAL_WAKE_LOCK  Icing 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4246c148): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4463 10111 null
,D/PackageBroadcastService( 4695): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4695): Null package name or gms related package.  Ignoreing.
D/PMS     (  905): releaseWL(4246c148): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/Icing   ( 4695): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  905): Unable to load service info ResolveInfo{426b6620 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/PMS     (  905): acquireWL(4208a148): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(41d3d768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/GCoreNlp( 4643): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  905): acquireWL(4206c320): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4206c320): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2555): UpdateCorporaTask done [took 525 ms] updated apps [took 525 ms] 
D/PMS     (  905): acquireWL(41b62648): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(41b62648): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42383d70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4208a148): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/LocationProviderProxy(  905): applying state to connected service
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): releaseWL(42383d70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): acquireWL(4395f6e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(420bb998): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4395f6e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(420bb998): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(438e7500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(438e7500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1108): closing low battery warning: level=100
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/Icing   ( 4695): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 +
,I/Prism.WidgetManager( 1245): onLoadItems() +
,I/Icing   ( 4695): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(424f90e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1245): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1245): onLoadItems() -
,I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 -
,D/PhoneApp( 1216): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1216): -- N1 =0
,D/PhoneApp( 1216): -- N2 =0
,D/PhoneApp( 1216): -- N3 =0
,D/PMS     (  905): acquireWL(44059108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
,V/AlarmManager(  905): sending alarm PendingIntent{4264c010: PendingIntentRecord{43c85e60 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449671306322, Int=0
,D/PMS     (  905): releaseWL(44059108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4514): [476] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4514): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  905): killProcessQuiet, pid=4675
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4675:com.android.keychain/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4675
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(4267bc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4267bc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42668c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d5d710: PendingIntentRecord{424eaec0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=206132, Int=0
,D/PMS     (  905): acquireWL(426b3308): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42a7e678): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42668c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=18 [11][2][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(4263b118): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 905 1000 WorkSource{10029}
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(43ba3798): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.games/com.google/***** 0x1 905 1000 WorkSource{10029}
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
D/PMS     (  905): releaseWL(426b3308): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  905): releaseWL(42a7e678): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4417a2f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4417a2f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(426722d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(426722d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  905): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 4695): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(432fb718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.android.contacts.metadata, SERVER, latestRunTime 145321, reason: ServiceChanged, SyncResult: databaseError: true stats []
D/PMS     (  905): releaseWL(4263b118): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
,D/SyncManager(  905): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, SERVER, latestRunTime 206619, reason: ServiceChanged
D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 1311: Landroid/os/PowerManager;.isInteractive ()Z
D/PMS     (  905): releaseWL(432fb718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43ba0540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1535/10029)
D/PMS     (  905): releaseWL(43ba0540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,V/AccountUtils( 4695): 0 accounts found with uca feature
,I/GamesSyncAdapter( 4695): Starting sync for 3a3529a
,I/GamesSyncAdapter( 4695): Sync duration for 3a3529a: 9
,E/ExternalAccountType( 1316): Unsupported attribute readOnly
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 349: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42515df0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43ba3798): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.games/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  905): releaseWL(42515df0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ChimeraCfgMgr( 4695): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4695): Module APK com.google.android.play.games already loaded
,E/dalvikvm( 4695): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method com.google.android.gms.games.ui.util.UiUtils.constructButtonBackground
,W/dalvikvm( 4695): VFY: unable to resolve new-instance 177 (Landroid/graphics/drawable/RippleDrawable;) in Lcom/google/android/gms/games/ui/util/UiUtils;
,D/PMS     (  905): acquireWL(43b70ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=213030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43b70ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(435df3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{41cecd28: PendingIntentRecord{43648478 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=229354, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{43b618c0: PendingIntentRecord{425f3100 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=234192, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5131 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{4227bb58: PendingIntentRecord{42161028 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449671327548, Int=10800000
,D/LocationManagerService(  905): getAllProviders()=[passive, gps, network]
D/PMS     (  905): releaseWL(435df3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (5131/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/Process (  905): killProcessQuiet, pid=4808
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4808:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4808
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(44095dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d5d710: PendingIntentRecord{424eaec0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=236244, Int=0
,D/PMS     (  905): acquireWL(42ef5fc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4331fe18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(44095dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): releaseWL(42ef5fc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4331fe18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(4395f080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(4395f080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4331c1a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(4331c1a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): Checking...
D/PowerUI ( 1108): closing low battery warning: level=100
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(426537e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=273030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426537e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42030fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{4207f410: PendingIntentRecord{425a1c00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=289405, Int=0
,D/PMS     (  905): releaseWL(42030fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c8bf08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=9 [31][3][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(433b55b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43c8bf08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(433b55b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(438f3078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(438f3078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(435ecdf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(435ecdf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f1f3e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(41ff4590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(430bcc38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42f1f3e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5152 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 5152): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 5152): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5152): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5152): install
,I/MultiDex( 5152): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5152): loading existing secondary dex files
,I/MultiDex( 5152): load found 3 secondary dex files
,I/MultiDex( 5152): install done
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 5152): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 5152): VFY: unable to resolve instance field 36
,W/dalvikvm( 5152): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
V/JNIHelp ( 5152): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,I/ProviderInstaller( 5152): Installed default security provider GmsCore_OpenSSL
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/GetConfigurationSnapshotOperation( 4643): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 5152): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 5152): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/WearableService( 4643): callingUid 10029, callindPid: 4643
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/dalvikvm( 5152): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 5152): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 5152): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 5152): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 5152): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 4695): Restart initialization of location
,E/MDM     ( 4643): [534] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/AuthorizationBluetoothService( 4725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 4725): Proximity feature is not enabled.
,I/PhenotypeFlagCommitter( 4643): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/PMS     (  905): acquireWL(436e42a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 4643): No location to return for getLastLocation()
,W/FusedLocationProvider( 4643): location=null
D/PMS     (  905): releaseWL(436e42a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/GoogleURLConnFactory( 4643): Using platform SSLCertificateSocketFactory
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/NativeLibraryUtils( 5152): Install completed successfully. count=14 extracted=0
,W/dalvikvm( 5152): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,W/dalvikvm( 5152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5152): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/GoogleURLConnFactory( 5152): Using platform SSLCertificateSocketFactory
,D/WVCdm   (  370): PrepareKeyRequest: nonce=1479995929
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/libc    ( 5152): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 5152): [NET] getaddrinfo-,err=8
D/libc    ( 5152): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 5152): [NET] getaddrinfo-, 1
,D/libc    ( 5152): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6086 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 5152): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4643): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
I/WVCdm   (  370): CdmEngine::CloseSession
D/libc    ( 4643): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4643): [NET] getaddrinfo-,err=8
D/libc    ( 4643): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4643): [NET] getaddrinfo-, 1
D/libc    ( 4643): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f4ef +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4643): [NET] getaddrinfo_proxy-, success
,D/libc    ( 5152): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 5152): [NET] getaddrinfo-,err=8
D/libc    ( 5152): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 5152): [NET] getaddrinfo-,err=8
,D/libc    ( 4643): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4643): [NET] getaddrinfo-,err=8
D/libc    ( 4643): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4643): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=10 [20][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,W/Uploader( 4643):  no longer exists, so no auth token.
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029),
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 5152): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 5152): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5152): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5152): Local Branch: 
I/Adreno-EGL( 5152): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5152): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5152):                  aa63bbd948f41d15fc72f585e
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4725): [NET] getaddrinfo-,err=8
D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4725): [NET] getaddrinfo-, 1
D/libc    ( 4725): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =87ef +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4725): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4725): [NET] getaddrinfo-,err=8
,D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4725): [NET] getaddrinfo-,err=8
D/libc    ( 4725): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4725): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=100 [1][1][0]
I/ClearcutLoggerApiImpl( 4695): disconnect managed GoogleApiClient
,D/PMS     (  905): releaseWL(41ff4590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425086f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(425086f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(438fffa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(438fffa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43167b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(435ef3b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(435ef3b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43167b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  905): acquireWL(4410fe70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
D/PMS     (  905): releaseWL(4410fe70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4643/10029)
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=50 [4][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3951): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3951): nl80211: survey data missing!
E/wpa_supplicant( 3951): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3951): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(430bcc38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c22c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43c22c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=4659
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4659:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4659
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(43b865c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b865c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43b5cb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43b5cb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3846): Connected to the server!
I/jxcore-log( 3846): 
,I/chromium( 3846): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  905): acquireWL(43ac9ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=333030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43ac9ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(43920f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43920f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1108): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4378cfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4378cfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(436791d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=393030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(436791d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43605180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{43af9df0: PendingIntentRecord{43b25560 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=416270, Int=300000
,D/PMS     (  905): releaseWL(43605180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  905): acquireWL(435a1d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(435a1d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(432fc408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(432fc408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(430fa898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=453030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(430fa898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(430c2408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(430c2408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42226010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42226010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4695): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4695): [NET] getaddrinfo-,err=8
,D/libc    ( 4695): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4695): [NET] getaddrinfo-, 1
,D/libc    ( 4695): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =bb73 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4695): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4695): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4695): [NET] getaddrinfo-,err=8
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(4211ae68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=513030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4211ae68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(420a3898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(420a3898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(41c9d808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(41c9d808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42424c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=573030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42424c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4216b1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4216b1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43b8b220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43b8b220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1216): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1216): sku_id=99
,D/ContactMessageStore( 1216): start background delete task...
,D/ContactMessageStore( 1216): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1216): size: 0 , 0
,D/ContactMessageStore( 1216): Background delete complete
,D/PMS     (  905): acquireWL(423e8f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=633030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(423e8f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41fe4ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PMS     (  905): releaseWL(41fe4ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(420d6cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=693030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(420d6cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41e65e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PMS     (  905): releaseWL(41e65e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(422676f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=753030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(422676f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4205c2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
D/PMS     (  905): releaseWL(4205c2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42611e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42611e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42076ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=813030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42076ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(438e5110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(438e5110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(423907d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{43af9df0: PendingIntentRecord{43b25560 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=716270, Int=300000
,V/AlarmManager(  905): sending alarm PendingIntent{41d92928: PendingIntentRecord{42491dc0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786674, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{41d5d710: PendingIntentRecord{424eaec0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=849036, Int=0
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,D/PMS     (  905): acquireWL(42a7e868): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(423907d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42046eb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42a7e868): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(42046eb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): acquireWL(41fce540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41fce540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43649e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=873030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43649e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42653528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42653528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425a1568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425a1568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(41b11038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=933030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41b11038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43bc6440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  905): releaseWL(43bc6440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42570448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42570448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(41b12980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=993030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41b12980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425f2a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{438e4ff0: PendingIntentRecord{425372d8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1015369, Int=0
,D/PMS     (  905): acquireWL(4211d9b8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{43af9df0: PendingIntentRecord{43b25560 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1016270, Int=300000
,V/AlarmManager(  905): sending alarm PendingIntent{4241c238: PendingIntentRecord{41c3f478 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449672047891, Int=900000
,V/AlarmManager(  905): sending alarm PendingIntent{425b7fc0: PendingIntentRecord{436616d8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449672143865, Int=0
,D/PMS     (  905): releaseWL(4211d9b8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): acquireWL(43677ed0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 4725 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5219 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (4725/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (4725/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43677ed0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 5219): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 5219): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 5219): MY_DEBUG = false
D/PMS     (  905): acquireWL(43602cc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5219 1000 null
,D/SmartSyncUtils( 5219): isEpsOn(), nState = 0
,D/PMS     (  905): releaseWL(425f2a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): releaseWL(43602cc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  905): acquireWL(438f4200): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5219 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5219): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5219): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5219): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 5219): SettingOnTime = 1449727200000, randomSettingOnTime = 1449725198000
,D/SmartSyncScreenOnOffTimeReceiver( 5219): SettingOffTime = 1449712800000, randomSettingOffTime = 1449719668000
,D/SmartSyncScreenOnOffTimeReceiver( 5219): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 5219): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 5219): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(438f4200): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/Process (  905): killProcessQuiet, pid=4884
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4884:com.nero.android.htc.sync.installer/u0a72 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4884
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(436f3c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(436f3c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44003838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44003838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(430bbbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1053030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(430bbbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4406f6f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4406f6f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43b37360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b37360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4403dfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1113030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4403dfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43af3a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43af3a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4377c7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4377c7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(440690c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1173030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(440690c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(436f45f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436f45f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4367bce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4367bce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(44063158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1233030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44063158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43780cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43780cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43b71290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b71290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(430ae760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1293030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(430ae760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(436645b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{43af9df0: PendingIntentRecord{43b25560 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1316270, Int=300000
,V/AlarmManager(  905): sending alarm PendingIntent{42600118: PendingIntentRecord{435a0eb8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449672260494, Int=1800000
,D/PMS     (  905): acquireWL(4375cb90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(436645b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  905): acquireWL(43ff9140): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4375cb90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 4695): Aggregate from 1449671241231 (log), 1449670460373 (data)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360162920
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163072
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163221
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163232
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163241
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360163296
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360168559
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360171432
,D/PMS     (  905): releaseWL(43ff9140): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(441d7e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(441d7e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(44151cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44151cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4410ae40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1353030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4410ae40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(440adc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): releaseWL(440adc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44004ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44004ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43c8c4e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1413029, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c8c4e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43c82c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43c82c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43c09098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c09098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43b931b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1473030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43b931b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43b8ad38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b8ad38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43b60240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43b60240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43b54448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1533030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43b54448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43b543a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b543a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43b54308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(43b54308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43a62558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1593030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43a62558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(438fb810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41d92928: PendingIntentRecord{42491dc0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1569071, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{43af9df0: PendingIntentRecord{43b25560 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1616270, Int=300000
,D/PMS     (  905): releaseWL(438fb810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): acquireWL(438f71a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(438f71a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4378ce30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4378ce30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4367aa50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1653030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4367aa50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43675758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43675758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4356a1b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(4356a1b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4331f968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1713030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4331f968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4331c398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4331c398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1523): [EventService] reorderNotification, total:1
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 3891): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=97
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
W/ContextImpl( 5219): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): acquireWL(43190650): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
,W/ctxmgr  ( 4643): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
D/TetherSettings( 3274): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3274): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3274): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3274): Cust_ConnectToPC   : spcsc>false
D/        ( 3274): Cust_ConnectToPC   : IPT>true
,D/        ( 3274): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3274): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3274): Index of the first 1 = -1
W/ctxmgr  ( 4643): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 4643): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 0.97, status=Status{statusCode=unknown status code: 7503, resolution=null}
W/Settings( 3274): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3274): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3274): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3274): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/PMS     (  905): releaseWL(43190650): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3274): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1108): status:2 level:97 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(426062b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426062b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=97
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:2 level:97 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(421acbe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1773030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(421acbe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41df6488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41df6488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=97
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:2 level:97 unsupport:false plugged:true
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(41c90de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41c90de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(41ca3828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1833030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  905): Prepared write state in 47ms
,I/ProcessStatsService(  905): Prepared write state in 28ms
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-43-06.bin
,D/PMS     (  905): releaseWL(41ca3828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425b9950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425b9950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(424338c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{420d3940: PendingIntentRecord{4207ddb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1893030, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(424338c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),D/CustomizationManager( 5269): ====startRecUseTime====
D/htc.customization.log.level( 5269):  is 
W/CustomizationLogLevel( 5269): Level value is invalid, use default level 2
D/CustomizationManager( 5269):  Read ACC file spent 0.102 (s)
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5269): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5269): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5269): Parsing tag category name = system
I/CustomizationCIDLoader( 5269): Parsing tag category name = application
I/CustomizationCIDLoader( 5269): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5269): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5269): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5269): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5269): Parsing tag category name = Settings
D/CustomizationManager( 5269):  Read CID file spent 0.156 (s)
D/CustomizationManager( 5269):  All configurations done spent 0.156 (s)
W/HtcNativeFlag( 5269): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5269): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5269): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5269): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=5269, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=3846
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 3846:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{42650068 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  905): Copying FileAsset 0x6d272d38 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/InputDispatcher(  905): channel '4406ff20 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  905): channel '4406ff20 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '4406ff20 com.test.thalitest.MainActivity (s)'
I/WindowState(  905): WIN DEATH: Window{4406ff20 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowManager(  905): WINDOW DIED Window{4406ff20 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 3846 uid 10389
W/PackageSettings(  905): Skipping PackageSetting{4224e158 com.example.hello/10396} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1523): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1523): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 4643): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1316): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(420312e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4643 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(420312e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1274): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1316): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1316): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1245): Deferring update until onResume
D/Launcher( 1245): waitUntilResume // bindAppsRemoved
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/[PluginManager]RegisterService( 4153): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/[PluginManager]RegisterService( 4153): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1245): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
E/ExternalAccountType( 1316): Unsupported attribute readOnly
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2555): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/cutils-trace( 5269): Error opening trace file: No such file or directory (2)
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5284 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  905): acquireWL(43c1ca98): PARTIAL_WAKE_LOCK  Icing 0x1 4695 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2555): UpdateCorporaTask done [took 270 ms] updated apps [took 270 ms] 
E/SQLiteDatabase( 5284): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5284): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5284): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5284): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5284): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5284): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5284): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5284): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5284): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5284): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5284): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5284): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5284): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5284): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5284): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5284): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5284): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5284): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5284): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5284): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5284): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5284): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5284): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5284): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5284): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5284): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5284): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5284): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5284): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5284): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5284): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5284): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5284): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5284): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5284): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5284): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5284): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5284): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5284): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5284): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5284): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5284): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5284): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5284): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5284): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5284): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5284): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5284): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5284): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5284): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5284): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5284): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5284): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5284): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5284): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5284): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5284): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5284): threadid=11: thread exiting with uncaught exception (group=0x416ebe30)
E/AndroidRuntime( 5284): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5284): Process: com.google.android.apps.docs, PID: 5284
E/AndroidRuntime( 5284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5284): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5284): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5284): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5284): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5284): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
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
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5302 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteDatabase( 5284): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5284): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5284): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5284): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5284): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5284): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5284): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5284): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5284): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5284): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5284): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5284): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5284): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5284): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5284): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 5284): killProcess, pid=5284
E/SQLiteOpenHelper( 5284): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5284): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5284): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5284): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5284): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5284): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5284): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5284): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5284): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5284): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5284): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5284): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5284): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5284): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5284): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5284): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 5284): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Recipient 5284
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 5284) has died.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 5302): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
E/SQLiteDatabase( 5302): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5302): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5302): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5302): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5302): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5302): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5302): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5302): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5302): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5302): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5302): threadid=10: thread exiting with uncaught exception (group=0x416ebe30)
D/PMS     (  905): acquireWL(41f33188): PARTIAL_WAKE_LOCK  AsyncService 0x1 4244 10160 null
D/PMS     (  905): releaseWL(41f33188): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/AndroidRuntime( 5302): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5302): Process: com.android.keychain, PID: 5302
E/AndroidRuntime( 5302): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5302): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5302): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5302): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5302): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5302): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5302): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5302): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5302): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Resuming delayed broadcast
E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 4695): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4695): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 4695): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteDatabase( 4695): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4695): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4695): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4695): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4695): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4695): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4695): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4695): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4695): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4695): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4695): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4695): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4695): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4695): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4695): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4695): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4695): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4695): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4695): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4695): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/PhenotypeInitializer( 4695): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 4695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 4695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 4695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 4695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 4695): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 4695): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 4695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 4695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 4695): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 4695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4695): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 4695): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 4695): threadid=42: thread exiting with uncaught exception (group=0x416ebe30)
E/AndroidRuntime( 4695): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4695): Process: com.google.android.gms, PID: 4695
E/AndroidRuntime( 4695): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4695): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4695): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4695): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4695): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4695): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4695): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4695): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4695): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
D/Process ( 4695): killProcess, pid=4695
D/Process ( 4695): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 5302): killProcess, pid=5302
D/Process ( 5302): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449673042249.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  905): Recipient 5302
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 5302) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4695
D/PMS     (  905): handleWLDeath(43c1ca98): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  905): Client connection lost with reason: 4
I/ActivityManager(  905): Process com.google.android.gms (pid 4695) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
I/ActivityManager(  905): Resuming delayed broadcast
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41badd38 +
I/Prism.WidgetManager( 1245): onLoadItems() +
W/PackageManager(  905): Unable to load service info ResolveInfo{4257b9b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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

```
