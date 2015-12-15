#### Test 50650278654db8c_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
,D/PMS     (  905): acquireWL(42d313d0): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  905): releaseWL(42d313d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(4238aaf8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  905): releaseWL(4238aaf8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(41be5ab0): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  905): releaseWL(41be5ab0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(424b41f0): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  905): releaseWL(424b41f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
D/CustomizationManager( 3831): ====startRecUseTime====
D/htc.customization.log.level( 3831):  is 
W/CustomizationLogLevel( 3831): Level value is invalid, use default level 2
D/CustomizationManager( 3831):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3831): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3831): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3831): Parsing tag category name = system
I/CustomizationCIDLoader( 3831): Parsing tag category name = application
I/CustomizationCIDLoader( 3831): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3831): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3831): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3831): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3831): Parsing tag category name = Settings
D/CustomizationManager( 3831):  Read CID file spent 0.089 (s)
D/CustomizationManager( 3831):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 3831): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3831): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3831): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3831): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3831
D/PMS     (  905): acquireHCC(422d0170): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(42246718): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x63b33cc8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1110506360
I/FeedHostManager( 1242): [onPause]
I/FeedProviderManager( 1242): onPause
I/FeedHostManager( 1242): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ced630
I/SocialFeedProvider( 1242): +onPause
I/SocialFeedProvider( 1242): -onPause
E/cutils-trace( 3831): Error opening trace file: No such file or directory (2)
D/PMS     (  905): acquireWL(41fe9618): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3844 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1242): [trimMemory] 20
W/asset   ( 3844): Copying FileAsset 0x5c7f9428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3844): Binding Chromium to main looper Looper (main, tid 1) {41a924b0}
I/LibraryLoader( 3844): Expected native library version number "",actual native library version number ""
I/chromium( 3844): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3844): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4222e908:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3844): 1101692888: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  905): acquireWL(42379880): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(4231dd70): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(4231dd70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3844): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3844): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3844): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3844): Local Branch: 
I/Adreno-EGL( 3844): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3844): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3844):                  aa63bbd948f41d15fc72f585e
W/chromium( 3844): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3844): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3844): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3844): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3844): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3844): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3844): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3844): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3844): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3844): CordovaWebView is running on device made by: HTC
,W/AwContents( 3844): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1242
,W/ResourceType( 3844): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3844): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ad9560, mServedView=org.apache.cordova.engine.SystemWebView{41a9f2f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1181): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1181): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Enable input method client, pid=3844
,W/AwContents( 3844): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +267ms
,D/PMS     (  905): releaseWL(41fe9618): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3844): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3844): JniHelper::setJavaVM(0x41569048), pthread_self() = 1662600896
,D/JX-Cordova( 3844): jxcore cordova android initializing
,I/dalvikvm-heap( 3844): Grow heap (frag case) to 11.584MB for 96598-byte allocation
,I/dalvikvm-heap( 3844): Grow heap (frag case) to 11.745MB for 217334-byte allocation
,I/dalvikvm-heap( 3844): Grow heap (frag case) to 11.920MB for 325996-byte allocation
,I/dalvikvm-heap( 3844): Grow heap (frag case) to 12.195MB for 488990-byte allocation
,I/dalvikvm-heap( 3844): Grow heap (frag case) to 12.601MB for 733480-byte allocation
,I/dalvikvm-heap( 3844): Grow heap (frag case) to 13.202MB for 1100216-byte allocation
,I/SensorManager(  905): mEventCount = 900
,I/dalvikvm-heap( 3844): Grow heap (frag case) to 15.489MB for 2475476-byte allocation
,I/dalvikvm-heap( 3844): Grow heap (frag case) to 17.467MB for 3713210-byte allocation
,W/jxcore-log( 3844): Initializing JXcore engine
,W/jxcore-log( 3844): JXcore engine is ready
,W/jxcore-log( 3844): Starting JXcore engine
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(422d0170): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42246718): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3844): Platform android
W/jxcore-log( 3844): 
,W/jxcore-log( 3844): Process ARCH arm
W/jxcore-log( 3844): 
,I/jxcore-log( 3844): JXcore Cordova bridge is ready!
I/jxcore-log( 3844): 
,W/jxcore-log( 3844): JXcore engine is started
,I/chromium( 3844): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3889 uid=10077 gids={50077}
,D/PMS     (  905): acquireWL(42311508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
,V/AlarmManager(  905): sending alarm PendingIntent{424fafd0: PendingIntentRecord{425a2280 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450201667204, Int=60000
,D/PMS     (  905): releaseWL(42311508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3889): SMSBackupAgentService started
,D/SMSBackup( 3889): Checking restore status
,D/SMSBackup( 3889): Restore complete
,D/SMSBackup( 3889): cancelCheckAlarm
,D/SMSBackup( 3889): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=2862
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2862:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2862
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(42379880): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3844): Toggling radios to true
I/jxcore-log( 3844): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): checking for enable restriction...
,D/BluetoothManagerService(  905): checkBTEasState, ret=true
I/BluetoothManagerService(  905): isBluetoothRestricted(): false
,D/BluetoothManagerService(  905): enable(): region ID = 6
D/BluetoothManagerService(  905): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 1
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 1464
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  905): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3844): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1315
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
D/WifiService(  905): setWifiEnabled: true pid=3844, uid=10348
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/ActivityManager(  905): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3904 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3844): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 3844): reconnect: Base Package Name=com.test.thalitest, uid=10348
,I/jxcore-log( 3844): Radios toggled
I/jxcore-log( 3844): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3844): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 3844): 
,I/jxcore-log( 3844): Perf Test app loaded loaded
I/jxcore-log( 3844): 
,D/PMS     (  905): acquireWL(423dee48): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
I/jxcore-log( 3844): check test folder
I/jxcore-log( 3844): 
I/jxcore-log( 3844): found test : ./testFindPeers.js
I/jxcore-log( 3844): 
,I/jxcore-log( 3844): found test : ./testSendData.js
I/jxcore-log( 3844): 
D/AdapterServiceConfig( 3904): Adding HeadsetService
D/AdapterServiceConfig( 3904): Adding A2dpService
D/AdapterServiceConfig( 3904): Adding HidService
D/AdapterServiceConfig( 3904): Adding HealthService
D/AdapterServiceConfig( 3904): Adding PanService
,D/AdapterServiceConfig( 3904): Adding GattService
,W/linker  ( 3904): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3904): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422e6560:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3904): make
,I/BluetoothAdapterState( 3904): Entering OffState
,I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3904): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:1 len:14
D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  905): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapter( 1422): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41d10fa0
,D/BluetoothAdapter( 1422): onBluetoothServiceUp done
D/BluetoothAdapter( 3844): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@425e2cb8
,D/BluetoothAdapter( 3844): onBluetoothServiceUp done
,D/BluetoothAdapter( 3904): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41aabd18
D/BluetoothAdapter( 3904): onBluetoothServiceUp done
,D/BluetoothAdapter(  905): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@422bcac0
,D/BluetoothAdapter(  905): onBluetoothServiceUp done
,D/BluetoothAdapter( 1106): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41ea79d0
,D/BluetoothAdapter( 1106): onBluetoothServiceUp done
,D/BluetoothAdapter( 1225): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bccfb8
,D/BluetoothAdapter( 1225): onBluetoothServiceUp done
,D/BluetoothAdapter( 1210): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41b975c0
,D/BluetoothAdapter( 1210): onBluetoothServiceUp done
,D/BluetoothAdapter( 1739): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@420a8cb8
D/BluetoothAdapter( 1739): onBluetoothServiceUp done
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3904): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3904): Setting state to 11
I/BluetoothAdapterState( 3904): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3904): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3904): make
,I/IntentController( 1106): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3904): StableState(): Entering Off State
,D/HeadsetService( 3904): Received start request. Starting profile...
D/HeadsetStateMachine( 3904): Version 1.6
,D/HeadsetStateMachine( 3904): make
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3930 uid=10037 gids={50037, 3002, 3001}
,I/HeadsetStateMachine( 3904): setCurrentDevice, the latest mCurrentDevice is:null
,I/BluetoothAdapterState( 3904): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/A2dpService( 3904): Received start request. Starting profile...
V/Avrcp   ( 3904): make
,D/Avrcp   ( 3904): fillIntentFilter()
,D/A2dpStateMachine( 3904): make
,D/A2dpStateMachine( 3904): Enter Disconnected: -2
,D/HidService( 3904): Received start request. Starting profile...
,D/HealthService( 3904): Received start request. Starting profile...
,I/QuickSettingBluetooth( 1106): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/PanService( 3904): Received start request. Starting profile...
D/BluetoothTethering(  905): supplyMessenger
,D/BluetoothTethering(  905): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  905): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  905): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 3904): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/HtcBtWidget_BTWidgetProvider( 3930): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3930): updateWidget(context) for widget: 
D/BtGatt.DebugUtils( 3904): handleDebugAction() action=null
D/BtGatt.GattService( 3904): Received start request. Starting profile...
,D/BtGatt.GattService( 3904): start()
V/BluetoothPbapService( 3904): Pbap Service onCreate
V/BluetoothPbapService( 3904): Starting PBAP service
,D/Process (  905): killProcessQuiet, pid=3393
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 11
,D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 11
,E/BluetoothMasService( 3904): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 3904): Add permission for SmsProvider.
,V/BluetoothMasService( 3904): Starting MAS instances
,D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 11
,I/MailMessageReceiver( 3904): reg:com.android.bluetooth.btservice.AdapterApp@41a9f280 with com.htc.util.mail.MailMessageReceiver@41adf500
,I/ActivityManager(  905): Killing 3393:com.google.android.music:main/u0a154 (adj 15): empty #17
I/MailManager( 3904): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41adf500
V/EmailUtils( 3904): Manager Instance is not NULL
,I/ActivityManager(  905): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3948 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,I/Choreographer( 3844): Skipped 92 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3844): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 3393): Died!
,D/Tethering(  905): interfaceAdded wlan0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/ActivityManager(  905): Recipient 3393
D/Tethering(  905): wlan0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): interfaceAdded p2p0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/PMS     (  905): releaseWL(423dee48): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/Tethering(  905): p2p0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 3904): ============NULL aList========
,V/EmailUtils( 3904): <-getEmailAccountIdList
,V/BluetoothMasService( 3904): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 11
V/BluetoothMasService( 3904): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3904): Manager Instance is not NULL
D/EmailUtils( 3904): ============NULL aList========
,V/EmailUtils( 3904): <-getEmailAccountIdList
V/BluetoothSapService( 3904): Sap Service onCreate
,V/BluetoothSapService( 3904): initBinder
V/BluetoothSapService( 3904): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41ae48f0
,V/BluetoothSapReceiver( 3904): BluetoothSapReceiver init
,D/BluetoothSapService( 3904): setSapService()
V/BluetoothSapService( 3904): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3904): state: 12
,D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 11
D/BluetoothAdapterService( 3904): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3904): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3904): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3904): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3904): Profile still not running:com.android.bluetooth.pan.PanService
,D/PanService( 3904): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterService( 3904): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3904): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  905): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  905): killProcessQuiet, pid=3681
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 3681:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/BluetoothMasReceiver( 3904): Bluetooth STATE CHANGED to 11
,I/ActivityManager(  905): Recipient 3681
,D/WifiService(  905): Client connection lost with reason: 4
,I/qcom-bluetooth( 3966): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3967 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 3984): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 3985): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3967): Received state change = 11
,I/qcom-bluetooth( 3987): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3988): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3989): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/WifiService(  905): New client listening to asynchronous messages
I/qcom-bluetooth( 3991): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/Process (  905): killProcessQuiet, pid=3376
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3376:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3376
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 3995): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 3995): Add randomness: count=1 entropy=0
D/wpa_supplicant( 3995): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3995): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 3995): Get randomness: len=20 entropy=1
D/wpa_supplicant( 3995): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3995): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 3995): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 3995): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3995): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 3995): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3995): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3995): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3995): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3995): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3995): update_config=1
D/wpa_supplicant( 3995): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3995): device_name='Android_63cc'
D/wpa_supplicant( 3995): manufacturer='HTC'
D/wpa_supplicant( 3995): model_name='HTC_PHONE'
D/wpa_supplicant( 3995): model_number='1234'
D/wpa_supplicant( 3995): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3995): p2p_oper_reg_class=126
D/wpa_supplicant( 3995): p2p_oper_channel=36
D/wpa_supplicant( 3995): p2p_ssid_postfix='-Android_63cc'
,D/wpa_supplicant( 3995): persistent_reconnect=1
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 3995): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3995): nl80211: RFKILL status not available
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3995): nl80211: Using driver-based roaming
D/wpa_supplicant( 3995): nl80211: TDLS supported
D/wpa_supplicant( 3995): nl80211: TDLS external setup
D/wpa_supplicant( 3995): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3995): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3995): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3995): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3995): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3995): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 3995): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3995): nl80211: Subscribe to mgmt frames with non-AP handle 0xb837b758
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb837b758
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3995): htc_wext_command_init +
E/wpa_supplicant( 3995): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 3995): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3995): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3995): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3995): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3995): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3995): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3995): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3995): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  905): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1106): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1106): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  905): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=3996 uid=10048 gids={50048}
,I/QuickSettingWifi( 1106): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,I/qcom-bluetooth( 4008): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/qcom-bluetooth( 4009): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/HtcWiFiWidget_WiFiWidgetProvider( 3996): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 3996): updateWidget(context) for widget: 
,D/Process (  905): killProcessQuiet, pid=3496
,I/ActivityManager(  905): Killing 3496:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/wpa_supplicant( 3995): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 3995):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3995):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3995):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3995): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3995): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0,
E/wpa_supplicant( 3995): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3995): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3995): nl80211: Flush PMKIDs
E/wpa_supplicant( 3995): send_and_recv error -22 - cmd 54
I/wpa_supplicant( 3995): State: DISCONNECTED -> INACTIVE
,I/bt-btu  ( 3904): btu_task pending for preload complete event
,D/wpa_supplicant( 3995): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3995): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3995): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3995): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3995): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3995): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3995): Using existing control interface directory.
D/wpa_supplicant( 3995): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 3995): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 3995): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
,D/wpa_supplicant( 3995): P2P: Own listen channel: 6
D/wpa_supplicant( 3995): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 3995): P2P: Add operating class 81,
I/wpa_supplicant( 3995): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3995): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3995): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3995): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3995): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3995): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3995): disable_scan_offload=1
D/wpa_supplicant( 3995): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 3995): update_config=1
D/wpa_supplicant( 3995): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3995): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3995): manufacturer='HTC'
D/wpa_supplicant( 3995): model_name='HTC Desire 820'
D/wpa_supplicant( 3995): model_number='HTC Desire 820'
D/wpa_supplicant( 3995): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 3995): persistent_reconnect=1
D/wpa_supplicant( 3995): p2p_disabled=1
D/wpa_supplicant( 3995): hs20=1
D/wpa_supplicant( 3995): interworking=1
D/wpa_supplicant( 3995): Line: 18 - start of a new network block
D/wpa_supplicant( 3995): key_mgmt: 0x2
D/wpa_supplicant( 3995): priority=1 (0x1)
,D/wpa_supplicant( 3995): signinfail=0 (0x0)
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3496
,D/wpa_supplicant( 3995): Priority group 1,
D/wpa_supplicant( 3995):    id=0 ssid='NG700'
I/wpa_supplicant( 3995): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3995): nl80211: RFKILL status not available
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 95
,D/wpa_supplicant( 3995): nl80211: Using driver-based roaming
D/wpa_supplicant( 3995): nl80211: TDLS supported
D/wpa_supplicant( 3995): nl80211: TDLS external setup
D/wpa_supplicant( 3995): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3995): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3995): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3995): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3995): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3995): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 3995): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3995): nl80211: Subscribe to mgmt frames with non-AP handle 0xb838b718
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718,
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3995): htc_wext_command_init +,
I/wpa_supplicant( 3995): htc_wext_command_init -
I/wpa_supplicant( 3995): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 3995): Don't set 00 to countryID.conf
D/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 3995): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 3995): nl80211: Use separate P2P group interface,
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3995): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3995): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3995): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3995): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3995): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 5250-5330 @ 80 MHz,
D/wpa_supplicant( 3995): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3995): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 3995): wapi_supplicant_init: Init WAI packet wlan0
,D/wpa_supplicant( 3995):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3995):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3995):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3995): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 3995): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 3995): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3995): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 3995): nl80211: Flush PMKIDs
,E/wpa_supplicant( 3995): send_and_recv error -22 - cmd 54,
,D/wpa_supplicant( 3995): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3995): TDLS: Driver uses external link setup
D/wpa_supplicant( 3995): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 3995): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3995): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3995): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3995): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3995): Using existing control interface directory.
,I/wpa_supplicant( 3995): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3995): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 3995): Auto country group 1: ch36
I/wpa_supplicant( 3995): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3995): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 3995): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 3995): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3995): random: Got 18/20 bytes from /dev/random
I/wpa_supplicant( 3995): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_905-2
D/wpa_supplicant( 3995): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 3995): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3995): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3995): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3995): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3995): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3995): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3995): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
V/RegulatoryObserver(  905): uevent:
V/RegulatoryObserver(  905): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
,V/RegulatoryObserver(  905): Regulatory Country Code:DE
D/wpa_supplicant( 3995): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 3995): nl80211: Event message available
D/wpa_supplicant( 3995): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0,
D/wpa_supplicant( 3995): nl80211: Regulatory domain change
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 1
,D/wpa_supplicant( 3995): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3995): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3995): nl80211: 5150-5250 @ 80 MHz,
D/wpa_supplicant( 3995): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 5470-5725 @ 80 MHz
,D/wpa_supplicant( 3995): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3995): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 3995): P2P: Add operating class 81
D/wpa_supplicant( 3995): P2P: Add operating class 115
,D/wpa_supplicant( 3995): P2P: Add operating class 116
D/wpa_supplicant( 3995): P2P: Add operating class 117
D/wpa_supplicant( 3995): P2P: Update channel list
D/wpa_supplicant( 3995): p2p0: Updating hw mode
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 1
D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 1
D/wpa_supplicant( 3995): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3995): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3995): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3995): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 3995): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3995): random: Got 2/2 bytes from /dev/random
D/wpa_supplicant( 3995): Get randomness: len=20 entropy=0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
V/RegulatoryObserver(  905): Start wifi-crda service to run crda.
V/RegulatoryObserver(  905): Country Code is DE
V/RegulatoryObserver(  905): Send broadcast country code message.
I/RegulatoryObserver(  905): Broadcast intent for crda country code: DE
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/wpa_supplicant( 3995): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): set wifi ON
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER MACADDR
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
I/IntentController( 1106): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiConfigStore(  905): Loading config and enabling all networks
D/WifiNative-wlan0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): list_network_info: ret=0x1, pos=0xb838e117 buf=0xb838e0e8
,I/wpa_supplicant( 3995): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3995): 0	NG700	any	
D/WifiNative-wlan0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  905): 0	NG700	any	
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 bssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 priority
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WIFI_ICON( 1106): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 3995): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 proto
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  905): Failed to look-up a string: W
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 group
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_as_cert
,D/HtcWiFiWidget_WiFiWidgetProvider( 3996): onWiFiStateChanged() for widget: 
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 limited
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 eap
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 phase2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/HtcWiFiWidget_WiFiWidgetProvider( 3996): updateWidget(context) for widget: 
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 password
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'client_cert'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
,D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 private_key
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 3995): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  905): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  905): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 3995): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3995): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET manufacturer HTC
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 3995): manufacturer='HTC'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_name HTC Desire 820
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 3995): model_name='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 3995): model_number='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 3995): config_methods='physical_display virtual_push_button'
I/wpa_supplicant( 3995): wpa_supplicant_scan enter
I/wpa_supplicant( 3995): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3995): ap_scan=1 , scan_req =1
I/wpa_supplicant( 3995): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET device_type 10-0050F204-5
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 3995): Scan req (ret=0) - timeout 10 secs
D/wpa_supplicant( 3995): nl80211: Event message available
D/wpa_supplicant( 3995): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  905): doBoolean: DISABLE_OFFLOAD
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET auto_interworking 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3995): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 3995): auto_interworking=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): SET_SCREEN_ON:On
I/wpa_supplicant( 3995): htc_wext_set_keepalive +
I/wpa_supplicant( 3995): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3995): getPrivFuncNum +	
I/wpa_supplicant( 3995): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3995): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 3995): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3995): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3995): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET ps 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 3995): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
W/Settings(  905): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  905): doBoolean: CTRL-DAT-AIR_MODE-0:1
,D/WifiP2pService(  905): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): SETBAND: 0
D/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 3995): P2P: Add operating class 81
D/wpa_supplicant( 3995): P2P: Add operating class 115
,D/wpa_supplicant( 3995): P2P: Add operating class 116
D/wpa_supplicant( 3995): P2P: Add operating class 117
D/wpa_supplicant( 3995): P2P: Update channel list
I/wpa_supplicant( 3995): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 3995): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3995): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 3995): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 3995): p2p_oper_reg_class=126
D/wpa_supplicant( 3995): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3995): P2P: New SSID postfix: -Android_63cc
,E/wpa_supplicant( 3995): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3995): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 3995): p2p_oper_channel=36
E/wpa_supplicant( 3995): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3995): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3995): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 3995): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 3995): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: BSS_FLUSH 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
,D/WifiMonitor(  905): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 3995): wpa_supplicant_scan enter
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 3995): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 3995): persistent_reconnect=1
I/wpa_supplicant( 3995): Recv Cmd 2: SET persistent_reconnect=1
D/WifiStateMachine(  905): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  905): P2pEnablingState
D/WifiP2pService(  905): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2p socket connection successful
D/WifiP2pService(  905): P2pEnabledState
D/WifiP2pService(  905): sending p2p connection changed broadcast
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_name Android_63cc
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 3995): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 3995): device_name='Android_63cc'
I/wpa_supplicant( 3995): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 3995): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 3995): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 3995): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 3995): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 3995): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 3995): Recv Cmd 2: SET device_type=10-0050F204-5
,D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 3995): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3995): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 3995): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 3995): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 3995): Single channel concurrency preference: sta
I/wpa_supplicant( 3995): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  905): doBoolean: P2P_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 3995): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 3995): P2P: Stopping find
D/wpa_supplicant( 3995): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 3995): P2P: State IDLE -> IDLE
,I/wpa_supplicant( 3995): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 3995): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 3995): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 3995): list_network_info: ret=0x22, pos=0xb838e10a buf=0xb838e0e8
I/wpa_supplicant( 3995): list_network_info: buf=network id / ssid / bssid / flags
,I/wpa_supplicant( 3995): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  905): doBoolean: AP_SCAN 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  905):    returned false
D/WifiNative-p2p0(  905): doBoolean: SET wifi_display 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 3995): CTRL_IFACE SET 'wifi_display'='1'
D/WifiDisplayController(  905): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  905): mWfdEnabled :false, networkInfo.isConnected() :false
,D/WifiP2pService(  905): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  905):  deviceAddress: 82:01:84:6b:e8:5d
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
D/WifiP2pService(  905): InactiveState{ when=-9ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-9ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 3995): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 3995): WFD: Update WFD IE
I/wpa_supplicant( 3995): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3995): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  905):    returned true
I/QuickSettingWifi( 1106): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  905): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  905): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
,D/wpa_supplicant( 3995): WFD: Set subelement 0
D/wpa_supplicant( 3995): WFD: Update WFD IE
I/wpa_supplicant( 3995): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3995): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  905):    returned true
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
D/WifiDisplayController(  905): Successfully set WFD info.
,I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  905):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  905):  primary type: 10-0050F204-5
D/WifiDisplayController(  905):  secondary type: null
D/WifiDisplayController(  905):  wps: 0
D/WifiDisplayController(  905):  grpcapab: 0
D/WifiDisplayController(  905):  devcapab: 0
D/WifiDisplayController(  905):  status: 3
D/WifiDisplayController(  905):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  905):  WFD CtrlPort: 7236
D/WifiDisplayController(  905):  WFD MaxThroughput: 50
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/wpa_supplicant( 3995): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 3995): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 3995): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 3995): nl80211: Event message available
D/wpa_supplicant( 3995): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 3995): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3995): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 3995): nl80211: Survey data missing
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3995): Sorted scan results
I/wpa_supplicant( 3995): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 3995): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 3995): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 3995): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 3995): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 3995): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 3995): Add randomness: count=2 entropy=0
D/wpa_supplicant( 3995): Add randomness: count=3 entropy=1
D/wpa_supplicant( 3995): Add randomness: count=4 entropy=2
D/wpa_supplicant( 3995): Add randomness: count=5 entropy=3
D/wpa_supplicant( 3995): Add randomness: count=6 entropy=4
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 3995): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3995): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3995): wpa_supplicant_pick_network+
I/wpa_supplicant( 3995): Selecting BSS from priority group 1
I/wpa_supplicant( 3995): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3995): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3995): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 3995): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 3995): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 3995):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 3995):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 3995): Start print parameters
I/wpa_supplicant( 3995): wpa_s->wpa_state is 3
I/wpa_supplicant( 3995): wpa_s->br_have_IP is 0
I/wpa_supplicant( 3995): isConcurrentMode() is 0
I/wpa_supplicant( 3995): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 3995): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 3995): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 3995): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 3995): wpa_s->reassociate is 0
I/wpa_supplicant( 3995): wpa_s->is_screen_on 1
I/wpa_supplicant( 3995): wpa_s->ifname wlan0
I/wpa_supplicant( 3995): End print parameters
I/wpa_supplicant( 3995): selected network = 2
D/wpa_supplicant( 3995): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb838c4e8  current_ssid=0x0
D/wpa_supplicant( 3995): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3995): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 3995): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 3995): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 3995): check if in concurrent case
,I/wpa_supplicant( 3995): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 3995): wpa_supplicant_associate, 1777
D/wpa_supplicant( 3995): wpa_supplicant_associate, 1780
D/wpa_supplicant( 3995): wpa_supplicant_associate, 1795
D/wpa_supplicant( 3995): RSN: PMKSA cache search - network_ctx=0xb838c4e8 try_opportunistic=0
D/wpa_supplicant( 3995): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3995): RSN: No PMKSA cache entry found
I/wpa_supplicant( 3995): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3995): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3995): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 3995): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 6
,D/wpa_supplicant( 3995): nl80211: Unsubscribe mgmt frames handle 0xb838b718 (mode change)
D/wpa_supplicant( 3995): nl80211: Subscribe to mgmt frames with non-AP handle 0xb838b718
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718,
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718,
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3995): nl80211: Register frame type=0xd0 nl_handle=0xb838b718
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3995): nl80211: Connect (ifindex=22)
,D/wpa_supplicant( 3995):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 3995):   * freq=2412
,D/wpa_supplicant( 3995):   * Auth Type 0
,D/wpa_supplicant( 3995):   * WPA Versions 0x2,
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 46,
,D/wpa_supplicant( 3995): nl80211: Connect request send successfully
,D/wpa_supplicant( 3995): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3995): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 3995): reply (617) for get BSS: id=0
I/wpa_supplicant( 3995): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3995): freq=5220
I/wpa_supplicant( 3995): level=-51
I/wpa_supplicant( 3995): tsf=0000000106861961
I/wpa_supplicant( 3995): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3995): ssid=NG7005g
I/wpa_supplicant( 3995): ====
I/wpa_supplicant( 3995): id=1
I/wpa_supplicant( 3995): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 3995): freq=2412
I/wpa_supplicant( 3995): level=-51
I/wpa_supplicant( 3995): tsf=0000000106861985
I/wpa_supplicant( 3995): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 3995): ssid=01ABC
I/wpa_supplicant( 3995): ====
I/wpa_supplicant( 3995): id=2
I/wpa_supplicant( 3995): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3995): freq=2412
I/wpa_supplicant( 3995): level=-51
I/wpa_supplicant( 3995): tsf=0000000106861995
I/wpa_supplicant( 3995): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3995): ssid=NG700
I/wpa_supplicant( 3995): ====
I/wpa_supplicant( 3995): id=3
I/wpa_supplicant( 3995): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 3995): freq=2462
I/wpa_supplicant( 3995): level=-89
I/wpa_supplicant( 3995): tsf=0000000106862006
I/wpa_supplicant( 3995): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 3995): ssid=UPC Wi-Free
I/wpa_supplicant( 3995): ====
I/wpa_supplicant( 3995): id=4
I/wpa_supplicant( 3995): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 3995): freq=2462
I/wpa_supplicant( 3995): level=-90
I/wpa_supplicant( 3995): tsf=0000000106862016
I/wpa_supplicant( 3995): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 3995): ssid=UPC0039325
I/wpa_supplicant( 3995): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStat,eMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 106861961, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 106861985, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 106861995, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 106862006, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 106862016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
I/bt-btu  ( 3904): btu_task received preload complete event
D/bt-btm  ( 3904): btm_acl_device_down
D/bt-btm  ( 3904): btm_acl_reset_paging
D/bt-btm  ( 3904): btm_acl_set_discing
I/bt-btm  ( 3904): btm_reset_complete
I/bt-btm  ( 3904): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
D/bt-btm  ( 3904): Start reading local supported commands
D/bt-btm  ( 3904): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 3904): BTM reads next extended features page (1)
D/bt-btm  ( 3904): BTM reads next extended features page (2)
D/bt-btm  ( 3904): BTM reached last extended features page (2)
D/bt-btm  ( 3904): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
D/bt-btm  ( 3904): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
D/bt-btm  ( 3904): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3904): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3904): btm_read_ble_wl_size 
D/bt-btm  ( 3904): btm_read_white_list_size_complete 
,D/bt-btm  ( 3904): btm_get_ble_buffer_size 
D/bt-btm  ( 3904): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3904): btm_read_ble_local_supported_features 
D/bt-btm  ( 3904): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3904): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3904): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3904): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3904): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3904): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3904): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3904):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3904): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3904): BTM_SetInquiryMode
I/bt-btm  ( 3904): BTM_SetPageScanType
I/bt-btm  ( 3904): BTM_SetInquiryScanType
D/bt-btm  ( 3904): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3904): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3904): BTM_BleLoadLocalKeys
D/bt-btm  ( 3904): BTM_BleLoadLocalKeys
I/bt-btm  ( 3904): BTM_Sec: application registered
E/bt-btm  ( 3904): BTM_SecRegister:p_cb_info->p_le_callback == 0x61f48941 
I/bt-btm  ( 3904): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3904): SMP_Register state=0
E/bt-btm  ( 3904): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61f48941 
I/bt-btm  ( 3904): BTM_Sec: application registered
D/bt-btm  ( 3904): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3904): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3904): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3904): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3904): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3904): BTM_RegBusyLevelNotif
I/bt-att  ( 3904): GATT_Register
D/bt-att  ( 3904): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3904): allocated gatt_if=3
I/bt-att  ( 3904): GATT_StartIf gatt_if=3
D/bt-att  ( 3904): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3904): gatt_find_the_connected_bda found=0 found_idx=7
D/wpa_supplicant( 3995): EAPOL: disable timer tick
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
,E/bt-btif ( 3904): Calling BTA_HhEnable
E/bt-btif ( 3904): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3904): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3904): BTM_AllocateSCN
I/bt-btif ( 3904): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3904): BTM_AllocateSCN
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btm  ( 3904): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3904):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3904):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3904):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3904):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3904):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3904):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3904):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3904):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3904): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3904): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
D/bt-avp  ( 3904): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3904): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btm  ( 3904): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-,btm  ( 3904):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3904): BTM_GetHCIConnHandle
I/bt-btm  ( 3904): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3904): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3904): BTM_GetHCIConnHandle
I/bt-btm  ( 3904): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3904): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3904): BTM_GetHCIConnHandle
I/bt-btm  ( 3904): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3904): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3904): BTM_GetHCIConnHandle
I/bt-btm  ( 3904): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 3904): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3904): BTM_GetHCIConnHandle
I/bt-btm  ( 3904): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3904): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3904): BTM_GetHCIConnHandle
I/bt-btm  ( 3904): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3904): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3904): GATT_Register
D/bt-att  ( 3904): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3904): allocated gatt_if=4
I/bt-att  ( 3904): GATT_StartIf gatt_if=4
D/bt-att  ( 3904): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3904): gatt_find_the_connected_bda found=0 found_idx=7
I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3904): Address is:80:01:84:8A:B3:68
I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:1 len:14
I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3904): Scan Mode:20
I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3904): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:8 len:36
D/BluetoothAdapter( 3904): getBluetoothService(): entry
D/BluetoothAdapter( 3904): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3904): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41aef7a8
D/BluetoothDevice( 3904): getService : Register callback
D/BluetoothAdapterProperties( 3904): Adding bonded device:B4:CE:F6:AB:A4:6A
D/BluetoothAdapterProperties( 3904): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 3904): Adding bonded device:34:FC:EF:9D:93:0B
D/BluetoothAdapterProperties( 3904): Adding bonded device:F4:F1:E1:5C:3B:E2
D/BluetoothAdapterProperties( 3904): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3904): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3904): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3904): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3904): Remote class is:5898764
I/bt-btif ( 3904): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3904): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3904): Remote class is:5898764
I/bt-btif ( 3904): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3904): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BluetoothRemoteDevices( 3904): Remote class is:5898764
D/wpa_supplicant( 3995): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3995): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3995): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3995): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 3995): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 3995): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3995): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3995): nl80211: Event message available
D/wpa_supplicant( 3995): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 3995): nl80211: Connect event
D/wpa_supplicant( 3995): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 3995): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3995): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 3995): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3995): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3995): Add randomness: count=7 entropy=5
I/wpa_supplicant( 3995): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 3995): TDLS: Remove peers on association
D/wpa_supplicant( 3995): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 3995): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 3995): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 3995): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 3995): htc_wext_set_keepalive +
I/wpa_supplicant( 3995): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 3995): getPrivFuncNum +	
I/wpa_supplicant( 3995): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3995): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 3995): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3995): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3995): Get randomness: len=32 entropy=6
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Setting MAC Address to c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
I/bt-btif ( 3904): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,E/BluetoothRemoteDevices( 3904): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,I/wpa_supplicant( 3995): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb838b9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 3995):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 3995): EAPOL: External notification - portValid=1
I/wpa_supplicant( 3995): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f6cb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 3995):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/BluetoothRemoteDevices( 3904): Remote class is:5898764
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 3995): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 3995): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 3995): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3995): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 3995): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3995): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 3995): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 3995): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 3995): set send_ind_to_ndc = 0
I/wpa_supplicant( 3995): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3995): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3995): EAPOL: External notification - portValid=1
D/wpa_supplicant( 3995): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 3995): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 3995): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 3995): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3995): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 3995): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 3995): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3995): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 3995): EAPOL authentication completed successfully
I/wpa_supplicant( 3995): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb,
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 3995): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3995): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3995): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  905): [isWifi] getHotspotEnabled: false
I/bt-btif ( 3904): HAL bt_hal_cbacks->remote_device_properties_cb
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
E/BluetoothRemoteDevices( 3904): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/BluetoothRemoteDevices( 3904): Remote class is:5898764
,I/bt-btif ( 3904): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3904): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothRemoteDevices( 3904): Remote class is:5898764
I/bt-btif ( 3904): BTA_JvEnable
I/bt-btm  ( 3904): BTM_ReadConnectability
,I/bt-btm  ( 3904): BTM_ReadDiscoverability
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/bt-btm  ( 3904): BTM_SetDiscoverability
I/bt-btm  ( 3904): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3904): br_edr_supported=0x2
I/bt-btm  ( 3904): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3904): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3904): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3904): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3904): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3904): BTM_SetConnectability
I/bt-btm  ( 3904): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3904): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3904): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3904): BTM_SetDiscoverability
I/bt-btm  ( 3904): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3904): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3904): br_edr_supported=0x0
I/bt-btm  ( 3904): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3904): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3904): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3904): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3904): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3904): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3904): BTM_SetConnectability
I/bt-btm  ( 3904): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3904): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3904): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3904): bta_pan_co_init
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3904): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3904):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3904):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3904): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3904):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3904): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3904):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller,
I/bt-btif ( 3904): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3904): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3904): ScanMode =  20
,D/BluetoothAdapterProperties( 3904): State =  11
I/bt-btm  ( 3904): BTM_SetDiscoverability
I/bt-btm  ( 3904): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3904): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3904): br_edr_supported=0x0
I/bt-btm  ( 3904): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3904): always disable adv in non-discoverable non-connectable mode if no scan rsp 
,D/bt-btm  ( 3904): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3904): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3904): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3904): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3904): BTM_SetConnectability
I/bt-btm  ( 3904): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3904): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3904): btm_ble_update_adv_flag new=0x0,
D/bt-btm  ( 3904): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3904): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3904): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/bt_mct  ( 3904): hci lib postload completed,
I/bt-btif ( 3904): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3904): Setting state to 12
I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3904): Scan Mode:21
I/BluetoothAdapterState( 3904): Bluetooth adapter state changed: 11-> 12
,I/bt-btif ( 3904): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterService( 3904): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterProperties( 3904): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3904): Discoverable Timeout:120,
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 3904): Entering On State
,D/BluetoothHeadset( 1106): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1101697448)( 3904): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3904): getBondedDevices: length=6
D/BluetoothHeadset( 1210): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1106): Proxy object connected
,I/QuickSettingMiniLite( 1106): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41da39c0
,D/BluetoothHeadset( 1210): Proxy object connected
,D/BluetoothPhoneService( 1210): BluetoothHeadset onServiceConnected
D/BluetoothHeadset( 1210): onBluetoothStateChange: up=true
,W/BluetoothHeadset( 1210): Proxy not attached to service
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
D/BluetoothAdapterService(1101697448)( 3904): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3904): getBondedDevices: length=6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1106): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/BluetoothHeadset( 1210): Proxy object connected
,D/BluetoothPan(  905): onBluetoothStateChange(on) call bindService
D/WIFI_ICON( 1106): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1739/10178)
,D/WISPrService( 3327): >>>>>WISPrService start isConnected = false<<<<<
,D/BluetoothHeadset(  905): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  905): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  905): Proxy object connected
,D/BluetoothAdapter(  905): 1111204840: getState(). Returning 12
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 11 -> 12
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,D/WifiService(  905): New client listening to asynchronous messages
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WISPrService( 3327): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/BluetoothPan(  905): BluetoothPAN Proxy object connected
D/BluetoothA2dp(  905): Proxy object connected
I/IntentController( 1106): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 3904): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3904): ***********state = 12
D/BluetoothAdapter(  905): 1111204840: getState(). Returning 12
D/BluetoothMasReceiver( 3904): Bluetooth STATE CHANGED to 12
V/BluetoothSapReceiver( 3904): SapReceiver onReceive 
V/BluetoothSapReceiver( 3904): action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
V/BluetoothSapReceiver( 3904):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3904): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 12
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 12
V/BluetoothMasService( 3904): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3904): Manager Instance is not NULL
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/PMS     (  905): acquireWL(424572b8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3327 1000 null
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  905): releaseWL(424572b8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/System.err(  905): java.lang.Throwable: stack dump
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3995): WiFioffload: SignalStrength: =97
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/HtcBtWidget_BTWidgetProvider( 3930): onBTStateChanged() for widget: 
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43f33b58:true
,D/WifiNative-wlan0(  905):    returned true
,I/LocationAgent( 3327): new LocationAgent instance!!
D/WifiStateMachine(  905): WiFioffload: set mMobileNetworkType= Unknown
D/HtcBtWidget_BTWidgetProvider( 3930): updateWidget(context) for widget: 
,D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE Unknown
D/PMS     (  905): acquireWL(43f32db8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3327 1000 null
D/WIFI_ICON( 1106): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/EmailUtils( 3904): ============NULL aList========
V/EmailUtils( 3904): <-getEmailAccountIdList
V/BluetoothSapService( 3904): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3904): state: 12
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): WiFioffload: update mobile network = Unknown
D/WifiNative-wlan0(  905):    returned true
D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 12
W/ContextImpl( 3904): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): Power_Mode_Type mode = 1
I/wpa_supplicant( 3995): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 61
D/HtcTagManager( 3327): HtcTagManager construction complete
D/WifiNative-wlan0(  905):    returned true
V/BluetoothSapService( 3904): Starting SAP server process
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
V/BluetoothPbapService( 3904): Handler(): got msg=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(435b04e8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false,
,V/BluetoothPbapService( 3904): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3904): Pbap Service initSocket
,V/BluetoothMasService( 3904): handleMessage: mIsEmailEnabledtrue
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BtMns   ( 3904): BluetoothMns: isEmailEnabled: true
,D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
I/QuickSettingWifi( 1106): receive.wifiConnect:false wifiAPname:null elapse:0
D/BluetoothAdapter( 3904): getBluetoothService(): entry
,W/BluetoothAdapter( 3904): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMasService( 3904): Map_prev 1
E/BluetoothServiceJni( 3904): SOCK FLAG = 1 ***********************
I/bt-btif ( 3904): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btif ( 3904): BTA_JvRfcommStartServer
I/bt-btm  ( 3904): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3904):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3904): Succeed to create listening socket 
V/BluetoothPbapService( 3904): Accepting socket connection...
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothAdapter( 3904): getBluetoothService(): entry
W/BluetoothAdapter( 3904): getBluetoothService() called with no BluetoothManagerCallback,
D/BluetoothInputDevice( 3327): BluetoothInputDevice()
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4400ceb0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4400ceb0 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothServiceJni( 3904): SOCK FLAG = 3 ***********************
I/bt-btif ( 3904): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btif ( 3904): BTA_JvRfcommStartServer
I/bt-btm  ( 3904): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3904):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
D/BluetoothInputDevice( 3327): BluetoothInputDevice(): Binding service...
D/BluetoothManagerService(  905): Registered receivers: 7
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3904): getBluetoothService(): entry
,W/BluetoothAdapter( 3904): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3904): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3904): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btif ( 3904): BTA_JvRfcommStartServer
I/bt-btm  ( 3904): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3904):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothAdapter( 1106): 1104410432: getState(). Returning 12
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 3327): BluetoothPan()
D/BluetoothAdapter( 1106): 1104410432: getState(). Returning 12
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 8
I/QuickSettingBluetooth( 1106): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1106): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
,D/BluetoothPan( 3327): BluetoothPan(): Binding service...
,D/BluetoothMap( 3327): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 9
,E/BluetoothMap( 3327): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothSap( 3327): BluetoothSap() call bindService
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,D/BluetoothManagerService(  905): Registered receivers: 10
,D/BluetoothSapService( 3904): Sap_prev 1
V/BluetoothSapService( 3904): SAP Service startRfcommListenerThread
D/BluetoothPbap( 3327): BluetoothPbap()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
V/BluetoothSapService( 3904): Sap Service initRfcommSocket
D/BluetoothManagerService(  905): Registered receivers: 11
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3904): getBluetoothService(): entry
,W/BluetoothAdapter( 3904): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
,D/BluetoothPbap( 3327): BluetoothPbap(): Binding service...
,E/BluetoothServiceJni( 3904): SOCK FLAG = 3 ***********************
I/bt-btif ( 3904): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btif ( 3904): BTA_JvRfcommStartServer
I/bt-btm  ( 3904): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3904):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3904): Succeed to create listening socket 
,V/BluetoothSapService( 3904): Accepting socket connection...
,D/BluetoothA2dp( 3327): BluetoothA2dp()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService(  905): Registered receivers: 12
D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
,D/BluetoothA2dp( 3327): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3327): BluetoothHeadset()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 13
D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
,D/BluetoothHeadset( 3327): BluetoothHeadset(): Binding service...
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothAdapter( 1106): 1104410432: getState(). Returning 12
V/TAG     ( 3904): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3904): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41ae6030
D/HtcTagManager( 3327): startProxy
,I/QuickSettingMiniLite( 1106): updateLiteState:no connect device!
,W/ContextImpl( 3327): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3327): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 3904): Pbap Service onBind
D/DockEventReceiver( 3327): finishStartingService: stopping service
D/BluetoothPan( 3327): BluetoothPAN Proxy object connected
D/PanProfile( 3327): Bluetooth service connected
D/BluetoothInputDevice( 3327): Proxy object connected
D/HidProfile( 3327): Bluetooth service connected
D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
D/BluetoothA2dp( 3327): Proxy object connected
I/BluetoothFtpService( 3904): Ftp Service onCreate
D/A2dpProfile( 3327): Bluetooth service connected
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 12
D/BluetoothMasReceiver( 3904): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
D/BluetoothAdapter( 3904): getBluetoothService(): entry
W/BluetoothAdapter( 3904): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3904): SOCK FLAG = 0 ***********************
I/bt-btif ( 3904): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
I/bt-btif ( 3904): BTA_JvRfcommStartServer
I/bt-btm  ( 3904): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3904):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3904): Accept thread started.
D/BluetoothFtpService( 3904): Ftp_prev 1
D/BluetoothHeadset( 3327): Proxy object connected
D/HeadsetProfile( 3327): Bluetooth service connected
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3967): onCreate: going to find gatt base service first.
D/BluetoothAdapter( 3327): 1103293584: getState(). Returning 12
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/SapServerProfile( 3327): Bluetooth service connected
D/BluetoothAdapter( 3904): getBluetoothService(): entry
D/BluetoothPbap( 3327): Proxy object connected
W/BluetoothAdapter( 3904): getBluetoothService() called with no BluetoothManagerCallback
D/PbapServerProfile( 3327): Bluetooth service connected
E/BluetoothServiceJni( 3904): SOCK FLAG = 1 ***********************
I/bt-btif ( 3904): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3904): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3904): Write Extended Inquiry Response to controller
,I/bt-btif ( 3904): BTA_JvRfcommStartServer
I/bt-btm  ( 3904): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
,I/bt-btm  ( 3904):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3904): Run Accept thread
D/BluetoothAdapter( 3904): 1101715624: getState(). Returning 12
V/BluetoothMasService( 3904): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3904): Manager Instance is not NULL
D/PMS     (  905): releaseWL(43f32db8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4304f730:true
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/EmailUtils( 3904): ============NULL aList========
,V/EmailUtils( 3904): <-getEmailAccountIdList
,D/BluetoothMasService( 3904): Map_prev 1
,D/[HTC_BLE][Constants]( 3967):  + defaultServices = 0
,D/[HTC_BLE][Constants]( 3967):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 3967):  + discoverServicesOnBonded = false
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3967):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3967): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf0f8
D/[HTC_BLE][Constants]( 3967): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3967): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3967): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3967): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3967): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 3967): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3967): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3327): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3967): Received state change = 12
D/HtcTagProfile( 3327): setup proxy
D/HtcPxpProfile( 3327): setup proxy
,D/HtcFmpProfile( 3327): setup proxy
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3967): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3967): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf0f8
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3967): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf0f8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3967): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf0f8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41abaab0
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3967): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf0f8
,W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42586d08:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3809): new LocationAgent instance!!
,D/HtcTagManager( 3809): HtcTagManager construction complete
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/BluetoothInputDevice( 3809): BluetoothInputDevice()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 14
D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/BluetoothInputDevice( 3809): BluetoothInputDevice(): Binding service...
,W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 3809): BluetoothPan()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 15
D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/BluetoothPan( 3809): BluetoothPan(): Binding service...
,D/BluetoothMap( 3809): Create BluetoothMap proxy object
,D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 16
,E/BluetoothMap( 3809): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothSap( 3809): BluetoothSap() call bindService
,D/BluetoothManagerService(  905): Registered receivers: 17
W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,D/BluetoothPbap( 3809): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 18
D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/BluetoothPbap( 3809): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 3809): BluetoothA2dp()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 19
D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/BluetoothA2dp( 3809): BluetoothA2dp(): Binding service...
W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothHeadset( 3809): BluetoothHeadset()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 20
D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/BluetoothHeadset( 3809): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3809): startProxy
,W/ContextImpl( 3809): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
,D/wpa_supplicant( 3995): EAPOL: startWhen --> 0
,D/wpa_supplicant( 3995): EAPOL: disable timer tick
,D/LocalBluetoothProfileManager( 3809): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3809): setBluetoothStateOn
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/HtcTagManager( 3809): startProxy
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
D/BluetoothAdapterService(1101697448)( 3904): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3904): getBondedDevices: length=6
D/BluetoothAdapter( 3809): getBluetoothService(): entry
D/BluetoothAdapter( 3809): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3809): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41ae9a28
,D/BluetoothDevice( 3809): getService : Register callback
,D/RingtoneManager( 3967): getExternalStorageState=mounted
,E/BluetoothDevice( 3809): getBluetoothClass(): COD is 5898764
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[5]: Hangouts Message
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[13]: Wintergreen
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3967):  + mAlertUri: content://settings/system/alarm_alert
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/HtcTagManager( 3809): addHtcTagProfiles
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3967): BleProfilesStateMachine is initialized...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3967): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3967): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3967): initScanModeInterface: true
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3967): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3967):  + mTag.getPrimaryDeviceList() = []
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/[HTC_BLE][Constants]( 3967):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3967):  + enableOnBonded = false
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43972798:true
,D/[HTC_BLE][Constants]( 3967):  + discoverServicesOnBonded = false
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3967): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41abaab0
,E/BluetoothDevice( 3809): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/HtcTagManager( 3809): addHtcTagProfiles
,E/BluetoothDevice( 3809): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/HtcTagManager( 3809): addHtcTagProfiles
,E/BluetoothDevice( 3809): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/HtcTagManager( 3809): addHtcTagProfiles
,E/BluetoothDevice( 3809): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/HtcTagManager( 3809): addHtcTagProfiles
,E/BluetoothDevice( 3809): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/HtcTagManager( 3809): addHtcTagProfiles
,D/BluetoothInputDevice( 3809): Proxy object connected
,D/HidProfile( 3809): Bluetooth service connected
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/BluetoothPan( 3809): BluetoothPAN Proxy object connected
D/PanProfile( 3809): Bluetooth service connected
D/SapServerProfile( 3809): Bluetooth service connected
D/BluetoothPbap( 3809): Proxy object connected
D/PbapServerProfile( 3809): Bluetooth service connected
D/BluetoothA2dp( 3809): Proxy object connected
,D/A2dpProfile( 3809): Bluetooth service connected
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/BluetoothHeadset( 3809): Proxy object connected
,D/HeadsetProfile( 3809): Bluetooth service connected
,D/BluetoothAdapter( 3809): 1101726512: getState(). Returning 12
,D/HtcTagManager( 3809): onServiceConnected
,D/HtcTagProfile( 3809): setup proxy
D/HtcPxpProfile( 3809): setup proxy
,D/HtcFmpProfile( 3809): setup proxy
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): Power_Mode_Type mode = 0
,I/wpa_supplicant( 3995): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(435b04e8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1106): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20333 delay=15s
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1106): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,I/IntentController( 1106): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  905): WAN detection
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1739/10178)
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3327): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [1][0][0]
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@423bffe8
,D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(42fdc478): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,I/QuickSettingWifi( 1106): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42fdc478): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4084 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/PMS     (  905): acquireWL(422ca828): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1242): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3740/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1422/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1739/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3415/10051)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1242/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1758/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c8ff +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3740/10100)
,D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42385270): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(425420f0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 101
D/libc    (  365): [NET]res_nsend:resplen=104
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  905): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4103 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,I/MusicStore( 4084): Database version: 95
D/PMS     (  905): releaseWL(425420f0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,W/ContextImpl( 4084): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  905): acquireWL(4237bbe0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
,D/PMS     (  905): acquireWL(423bbea8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 905 1000 WorkSource{10160}
,D/PMS     (  905): releaseWL(42385270): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1076 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1106): receive(android.intent.action.TIME_SET,4,false)
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4084): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/DotMatrix( 1530): [EventService] EVENT_RESET_THEME_TIMESTAMP
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4288d250): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(4288d250): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/FeedActionBar( 1242): updateLastUpdatedTime(in String) LAST UPDATED 18:46
,D/GpsLocationProvider(  905): NTP server returned: 1450201672545 (Tue Dec 15 18:47:52 CET 2015) reference: 109232 certainty: 9 system time offset: -1
,D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME_FINISHED
,D/DotMatrix( 1530): [EventService] isTheSameDay:false,timestamp is early than today:true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(422cfa98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(422cfa98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(422ca828): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4084): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42e4a020): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(423bbea8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  905): releaseWL(42e4a020): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4084): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4084): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4084, uid=10154, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42037278): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/DelayedSyncController( 4103): Delaying sync.
D/PMS     (  905): releaseWL(42037278): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43010008): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
D/PMS     (  905): releaseWL(4237bbe0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/MediaRouterService(  905): Client com.google.android.music (pid 4084): Registered
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
,I/MediaRouter( 4084): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/PMS     (  905): acquireWL(43fd39b8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
,D/PMS     (  905): releaseWL(43010008): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42d1d940): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42d1d940): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/DelayedSyncController( 4103): Delaying sync.
,I/NetworkMonitor( 4084): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4084/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43606f30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2203/10021)
D/PMS     (  905): releaseWL(43fd39b8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/PMS     (  905): releaseWL(43606f30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4131 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4084): getSelectedRoute
,I/NetworkMonitor( 4084): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4084/10154)
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4084, uid=10154, userID:0
,D/Process (  905): killProcessQuiet, pid=3708
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3708:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3708
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 4131): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4131): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4131): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4131): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4131): Preparing secondary program dexes.
,V/DexLibLoader( 4131): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4131): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4131): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4131): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4131): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4131): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4131): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4131): Dex already copied
D/OdexVerifier( 4131): Odex verification is skipped.
,V/DexLibLoader( 4131): Creating class loader
,V/DexLibLoader( 4131): Finished creating class loader
V/DexLibLoader( 4131): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4131): Dex already copied
D/OdexVerifier( 4131): Odex verification is skipped.
,V/DexLibLoader( 4131): Creating class loader
,V/DexLibLoader( 4131): Finished creating class loader
V/DexLibLoader( 4131): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4131): Dex already copied
D/OdexVerifier( 4131): Odex verification is skipped.
,V/DexLibLoader( 4131): Creating class loader
,V/DexLibLoader( 4131): Finished creating class loader
,V/DexLibLoader( 4131): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4131): Dex already copied
D/OdexVerifier( 4131): Odex verification is skipped.
,V/DexLibLoader( 4131): Creating class loader
,V/DexLibLoader( 4131): Finished creating class loader
,V/DexLibLoader( 4131): Verifying classes from secondary dexes.
,D/DexLibLoader( 4131): DexLibLoader.ensureDexLoaded took 113 ms
,D/WIFI_ICON( 1106): WifiActivity: 3
,D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216,
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1106): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 3844): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3844): 
,W/dalvikvm( 4131): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4131): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4131): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4131): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4131): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4131): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4131): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,W/dalvikvm( 4131): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4131): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4131): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,E/BTIF_CORE( 3904): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3904): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3904): Wake lock released
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =bef1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.59.123.86,
,W/fb4a(:<default>):StaticBindingVerifier( 4131): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420cf888
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420cf888, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421f67d0
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@424da590
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4131/10026)
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/fb4a(:<default>):BaseAnalyticsConfig( 4131): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4131): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  905): Disable JIT of com.htc.bgp
,D/Process (  905): killProcessQuiet, pid=1403
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4152 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
I/ActivityManager(  905): Killing 1403:com.htc.sense.hsp/u0a53 (adj 15): empty #17
,I/SensorManager(  905): mEventCount = 1050
,I/ActivityManager(  905): Recipient 1403
,W/fb4a(:<default>):UserScope( 4131): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4131): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4131): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 381ms
,D/PMS     (  905): nativeSetInteractive:false
,D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
,D/PMS     (  905): nativeSetAutoSuspend:true done
,D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@435386f8)
,I/IntentController( 1106): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1225): ScreenObserver: OFF
,D/NfcService( 1225): applyRouting - 0
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
D/PMN     (  905): wakingUp
I/InputMethodManagerService(  905): Disable input method client, pid=3844
I/WindowManager(  905): No lock screen! windowToken=null
,D/NfcService( 1225): applyRouting -2
D/PMS     (  905): acquireWL(43bad178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): acquireWL(435258b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
D/PMS     (  905): releaseWL(43bad178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/ResourceType( 3844): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3844): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a9f2f0 VFEDH.C. .F...... 0,0-720,1134 #64}
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): releaseWL(435258b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  905): onScreenOn
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20334 delay=15s
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2203): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1225): applyRouting - 0
,D/MtpService( 2203): [MTP][onReceive]-
,D/NfcService( 1225): applyRouting -2
D/PMS     (  905): acquireWL(43ee9dd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
D/PMS     (  905): releaseWL(43ee9dd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
,I/ClockThread( 1106): stop update clock
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3995): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): SET_SCREEN_ON:On
I/wpa_supplicant( 3995): htc_wext_set_keepalive +
I/wpa_supplicant( 3995): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3995): getPrivFuncNum +	
I/wpa_supplicant( 3995): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3995): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3995): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3995): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 3995): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  905):    returned true
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1106): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  905): updateScreenOn: false
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
,I/CalendarProvider2( 4152): Created com.android.providers.calendar.CalendarAlarmManager@41acac28(com.android.providers.calendar.HtcCalendarProvider@41ab2fb0)
,D/CalendarProvider2( 4152): wait start:true
E/dalvikvm( 4131): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4131): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4131): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4131): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4131): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4131): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4131): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4131): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4131): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4131): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4131): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4131): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4131): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4131): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4131): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4131): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4131): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4131): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/CalendarProvider2( 4152): wait end:false
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(4332ea28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1422 10028 null
D/PMS     (  905): acquireWL(43683e80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1195 10028 null
,D/PMS     (  905): releaseWL(4332ea28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3967): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3967): onScreenOn: 1450201675167
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3967): onScreenOn: 1450201675167
D/PMS     (  905): acquireWL(423ff628): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1195 10028 null
D/PMS     (  905): releaseWL(43683e80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421f67d0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421f67d0, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@424da590
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(42e3ebe0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 9.925MB for 39954-byte allocation
,D/PMS     (  905): releaseWL(42e3ebe0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/dalvikvm-heap( 4131): Grow heap (frag case) to 10.002MB for 79892-byte allocation
,D/GCM     ( 1341): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/PMS     (  905): releaseWL(423ff628): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/libc    ( 1341): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1341): [NET] getaddrinfo-,err=8
D/libc    ( 1341): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1341): [NET] getaddrinfo-, 1
,D/libc    ( 1341): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9ded +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  905): acquireWL(437d14d8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1341 10028 null
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 10.063MB for 84664-byte allocation
I/ActivityManager(  905): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4183 uid=10053 gids={50053, 1023, 3003, 5012}
,D/ContactMessageStore( 1210): notify MmsSms
,D/AccFlag ( 1210): sense_version=6.0
,D/AccFlag ( 1210): sku_id=99
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 273
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1341): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 10.089MB for 28144-byte allocation
,D/PluginProvider( 4183): PluginProvider onCreate
,D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,D/PluginProvider( 4183): current plugin count: 19
,D/HtcAppUPService( 4183): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4131/10026)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43f33be8 u0 ReceiverList{42e3f568 4131 com.facebook.katana/10026/u0 remote:42948898}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e51d48 u0 ReceiverList{42e51ce8 4131 com.facebook.katana/10026/u0 remote:42a61708}}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4131/10026)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4131/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4131/10026)
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [8][0][0]
,D/libc    ( 1341): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1341): [NET] getaddrinfo-,err=8
,D/AutoSetting( 4183): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityThread( 1341): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/PMS     (  905): acquireWL(431e8910): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
D/AlarmManager(  905): ACTION_SCREEN_OFF
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20334 mDataStallAlarmIntent=PendingIntent{434dabe0: PendingIntentRecord{424846c0 android broadcastIntent}}
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4183/10053)
D/PMS     (  905): releaseWL(431e8910): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4201 uid=10078 gids={50078, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=3740
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Killing 3740:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/PMS     (  905): acquireWL(437dc390): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,I/ActivityManager(  905): Recipient 3740
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/GCoreFlp( 1422): Unknown pending intent to remove.
,D/AutoSetting( 4183): service - onCreate()
D/PMS     (  905): acquireWL(42e87fe0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
D/PMS     (  905): releaseWL(42e87fe0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  905): acquireWL(43f6fe28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/wpa_supplicant( 3995): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3995): SET_SCREEN_ON:Off
I/wpa_supplicant( 3995): htc_wext_set_keepalive +
I/wpa_supplicant( 3995): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3995): getPrivFuncNum +	
I/wpa_supplicant( 3995): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3995): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3995): get_ip_address source addr = c0a80176
I/wpa_supplicant( 3995): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 3995): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
,D/AutoSetting( 4183): service - AddressCache: using context: com.htc.Weather
D/PMS     (  905): releaseWL(43f6fe28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  905): releaseWL(437dc390): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/LocationManagerService(  905): request 424b84f8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/AutoSetting( 4183): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 4183): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4183): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4183): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4183/10053)
,D/NetworkPolicy(  905): updateScreenOn: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1210): start background delete task...
D/ContactMessageStore( 1210): size: 0 , 0
D/ContactMessageStore( 1210): Background delete complete
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [2][0][0]
,D/MobileConnectivityChangeReceiver( 4201): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4201): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4201): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4201): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4131): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4201/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4201/10078)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4131): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4201/10078)
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4131): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4223 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(43ef8e28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1422 10028 null
D/PMS     (  905): releaseWL(43ef8e28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3967): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3967): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3967): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3967): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3967): onScreenOff
,D/PMS     (  905): acquireWL(41f6ba80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1195 10028 null
,D/PMS     (  905): acquireWL(441cbbc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1195 10028 null
,D/PMS     (  905): releaseWL(41f6ba80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1341): Connected
D/PMS     (  905): acquireWL(440084f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1341 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4223): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): releaseWL(437d14d8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/CheckinService( 1195): Preparing to send checkin request
,I/EventLogService( 1195): Accumulating logs since 1450200045594
,W/ContextImpl( 4223): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1341/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/PMS     (  905): releaseWL(440084f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(43fb0df0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1341 10028 null
,W/GAV2    ( 4223): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4223): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4223): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/GCM     ( 1341): Message class mpf
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1341/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1341/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/PMS     (  905): acquireWL(43f52bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,W/EventLogAggregator( 1195): Unknown tag: install_package_attempt
W/EventLogAggregator( 1195): Unknown tag: snet
,W/EventLogAggregator( 1195): Unknown tag: snet_gcore
D/PMS     (  905): releaseWL(43fb0df0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): releaseWL(43f52bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/GoogleHttpClient( 1195): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1195): Using GMS GoogleHttpClient
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1195/10028)
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1195/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4223/10151)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=0 [6][0][0]
V/WebViewChromiumFactoryProvider( 4223): Binding Chromium to main looper Looper (main, tid 1) {41a94168}
I/LibraryLoader( 4223): Expected native library version number "",actual native library version number ""
I/chromium( 4223): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4223): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(43f27950): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  905): acquireWL(43f16a18): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  905): releaseWL(43f27950): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 4223): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4223): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4223): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4223): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4223): Local Branch: 
I/Adreno-EGL( 4223): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4223): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4223):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4223): Starting up...
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4223/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4223/10151)
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
I/NotificationStore( 1341): System rebooted after Notification storage file was last written
I/NotificationStore( 1341): Deleting the file
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3628/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3628/10160)
,D/Process (  905): killProcessQuiet, pid=3760
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3760:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1739/10178)
,I/ActivityManager(  905): Recipient 3760
,D/AlertReceiver( 3793): beginStartingService
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(41ac6150): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3793 10013 null
,W/CheckinRequestBuilder( 1195): awaiting user notification for token
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/PMS     (  905): acquireWL(422a6910): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1195 10028 null
,I/RemoteViews( 1106): com.google.android.gms (false,0)
D/PMS     (  905): releaseWL(422a6910): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41af1598 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/AlertService( 3793): start to updateAlertNotification!
,I/RemoteViews.Performance( 1106): com.google.android.gms 3 10 4 12
,D/AlertService( 3793): No fired or scheduled alerts
,D/HtcAlertUtils( 3793): -- cancelReminderNotification --
,D/HtcAlertUtils( 3793): broadcastExistReminder!
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3793): stopSelfResult true
D/PMS     (  905): releaseWL(41ac6150): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4268 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/CalendarProvider2( 4152): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4152): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4280 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=3727
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3727:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3727
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherRequest( 1106): request cur loc, but there is no sys cur
,I/MultiDex( 4268): install
,I/MultiDex( 4268): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4268): loading existing secondary dex files
,I/MultiDex( 4268): load found 1 secondary dex files
,I/MultiDex( 4268): install done
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4295 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,I/ProviderInstaller( 4268): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,W/WeatherUtility( 4280): can't get weather sync account
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,W/WeatherRequest( 4280): request cur loc, but there is no sys cur
,W/Settings( 4280): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/PMS     (  905): acquireWL(42415b48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4295 10070 null
,D/PMS     (  905): acquireWL(422aa470): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4295 10070 null
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3995): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42415b48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 4295): update TASK shortcut>
I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4312 uid=10090 gids={50090, 3003, 5012, 1028}
,D/AppWidgetHostView( 1242): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1242): com.htc.widget.weatherclock (true,33751552)
,I/TodoTaskNotifyService( 4295): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/RemoteViews.Performance( 1242): com.htc.widget.weatherclock 2 9 17
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 4295): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4295): stopSelfResult true
,D/Process (  905): killProcessQuiet, pid=3777
,I/WorldClock.Global( 4312): isHtcDevice = true
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): releaseWL(422aa470): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Killing 3777:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3777
,I/WorldClock.Global( 4312): isHtcDevice = true
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.AlarmUtils( 4312): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4327 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 4312): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4312): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1106): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/Process (  905): killProcessQuiet, pid=3592
,D/TimeService( 4327): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450201676493
,I/ActivityManager(  905): Killing 3592:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3592
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4343 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=3889
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3889:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3889
,W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): acquireWL(43f5f5e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4343 1000 null
D/SmartSyncUtils( 4343): isEpsOn(), nState = 0
,D/PMS     (  905): releaseWL(43f5f5e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4343): getMobilePolicyEnabled, result = true
,D/AutoSetting( 4183): receiver - intent: android.intent.action.USER_PRESENT
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 4183): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3327): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3327): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3327): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3327): Cust_ConnectToPC   : spcsc>false
D/        ( 3327): Cust_ConnectToPC   : IPT>true
D/        ( 3327): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3327): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3327): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3327): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3327): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3327): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3327):  defaultType:0
,D/Process (  905): killProcessQuiet, pid=3996
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Killing 3996:com.htc.widget.process2/u0a48 (adj 15): empty #17
D/GCM     ( 1341): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3996
,W/ContextImpl( 4343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4343): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4343): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4343): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424da590
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  905): pid=905, uid=1000
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4365 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424da590, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424da590, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424da590
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424da988 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424da988 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/Adreno-EGL( 4268): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4268): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4268): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4268): Local Branch: 
I/Adreno-EGL( 4268): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4268): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4268):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4268): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4268): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4268): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4268): Local Branch: 
I/Adreno-EGL( 4268): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4268): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4268):                  aa63bbd948f41d15fc72f585e
I/Babel   ( 4365): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4365): MmsConfig.loadMmsSettings
,E/dalvikvm( 4365): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4365): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4365): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4365): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4365): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4390 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4365, uid=10111, userID:0
,W/Settings( 4365): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4365, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4365, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4365, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4365, uid=10111, userID:0
,D/MessageFrequencyProvider( 4390): onCreate
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4365, uid=10111, userID:0
,V/GetPrviateResource( 4390): GetPrviateResource
V/GetPrviateResource( 4390): GetPrviateResource
,D/MmsCustomizationProvider( 4390): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4390): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4365): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4365): MmsConfig.loadFromDatabase
E/Babel   ( 4365): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4365): MmsConfig.loadFromResources
,E/Babel   ( 4365): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4365): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,I/ProviderInstaller( 4365): Installed default security provider GmsCore_OpenSSL
,D/Process (  905): killProcessQuiet, pid=3930
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 3930:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3930
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4365/10111)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4268/10028)
W/Settings( 4268): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/MessageCustFlag( 4390): sense_version=6.0
,D/BTAccessoryUtil( 4390): createReceiver
,D/BTAccessoryUtil( 4390): registerReceiver return intent = null
D/MessageCustFlag( 4390): sku_id=99
,W/SystemReader( 4390): Cannot find message_ambs_application_id, use default value instead
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4365/10111)
,D/Messaging( 4390): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4390): networkCode: 
,D/MessageCustFlag( 4390): sku_id=99
D/MmsConfig( 4390): SIE smsPri: null
,D/MmsConfig( 4390): networkCode: 
,D/HtcTelephonyCapability( 4390): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4390): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4390): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4390): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  905): Resuming delayed broadcast
D/ProviderChangeReceiver( 3793): ---------------------------------------------------
D/ProviderChangeReceiver( 3793): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3793): start to updateAlertNotification!
,W/ContextImpl( 3809): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/AlertService( 3793): No fired or scheduled alerts
,D/HtcAlertUtils( 3793): -- cancelReminderNotification --
,D/HtcAlertUtils( 3793): broadcastExistReminder!
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,D/Process (  905): killProcessQuiet, pid=3948
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1341): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Killing 3948:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3948
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  905): Resuming delayed broadcast
,E/Babel   ( 4365): UserRecoverableAuthException.
,E/Babel   ( 4365): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4365): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4365): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4365): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4365): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4365): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4365): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4365): Error getting auth token
,E/Babel   ( 4365): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4365): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4365): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4365): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4365): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4365): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4415 uid=10038 gids={50038}
,E/Babel   ( 4365): Account registration failedRedacted-21
E/Babel   ( 4365): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4365): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4365): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4365): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4365): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4365): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4365): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4365): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4365/10111)
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4429 uid=10077 gids={50077}
,D/Process (  905): killProcessQuiet, pid=4084
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4084:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4131/10026)
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4131/10026)
,D/SMSBackup( 4429): Got a database change event
,D/Process (  905): killProcessQuiet, pid=4131
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4131:com.facebook.katana/u0a26 (adj 15): empty #17
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
D/PMS     (  905): acquireWL(43bafde8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4295 10070 null
D/PMS     (  905): acquireWL(43bad028): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4295 10070 null
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/TodoTaskNotifyService( 4295): java.lang.NullPointerException
W/System.err( 4295): java.lang.NullPointerException
W/System.err( 4295): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4295): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
,W/System.err( 4295): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4295): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4295): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  905): acquireWL(43b653e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4295 10070 null
I/ActivityManager(  905): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  905): releaseWL(43bafde8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): acquireWL(43bad028): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4295 10070 null
W/NotifyReceiver( 4295): stopSelfResult false
E/TodoTaskNotifyService( 4295): java.lang.NullPointerException
,W/System.err( 4295): java.lang.NullPointerException
W/System.err( 4295): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4295): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4295): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4295): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4295): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4295): mStartingService is null
,W/NotifyReceiver( 4295): stopSelfResult true
D/PMS     (  905): releaseWL(43b653e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): releaseWL(43bad028): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,E/Babel   ( 4365): Unexpected exception while authenticating.
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1106): com.google.android.gms (false,0)
,E/Babel   ( 4365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4365): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4365): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4365): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4365): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4365): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4365): 	at java.lang.Thread.run(Thread.java:864)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41c42470 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.google.android.gms 2 5 2 12
I/ActivityManager(  905): Recipient 4084
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 4084): Died!
,I/Adreno-EGL( 4268): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4268): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4268): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4268): Local Branch: 
I/Adreno-EGL( 4268): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4268): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4268):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  905): Recipient 4131
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(435b1050): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
,D/PMS     (  905): acquireWL(435ade28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
,D/PMS     (  905): releaseWL(435b1050): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(435ade28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/CheckinTask( 1195): Sending checkin request (9112 bytes)
,W/ActivityThread( 1195): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/libc    ( 1195): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1195): [NET] getaddrinfo-,err=8
D/libc    ( 1195): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1195): [NET] getaddrinfo-, 1
,D/libc    ( 1195): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =b1a3 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 150
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1195): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1195): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1195): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(4252cc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,D/PMS     (  905): releaseWL(4252cc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1195/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3995): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1195/10028)
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3995): nl80211: survey data missing!
E/wpa_supplicant( 3995): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3995): environment dirty rate=5 [18][1][0]
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1195): awaiting user notification for token
,I/RemoteViews( 1106): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41d72798 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.google.android.gms 1 8 3 12
,I/CheckinTask( 1195): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1195): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,D/GCM     ( 1341): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  905): releaseWL(441cbbc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1195): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c7b090 that was originally bound here
E/ActivityThread( 1195): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c7b090 that was originally bound here
E/ActivityThread( 1195): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1195): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1195): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1195): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1195): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1195): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1195): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1195): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1195): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1195): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1195): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1195): 	at bks.a(SourceFile:298)
E/ActivityThread( 1195): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1195): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1195): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1195): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1341): GCM config loaded
,D/PMS     (  905): releaseWL(43f16a18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/Messaging( 4390): mNeedToUpdateDate2 start
,D/MmsConfig( 4390): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4390): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4390): 
D/MmsAsyncWorkHandler( 4390): HM tk = 20001
,D/ReportIndicatorCache( 4390): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4390): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a9a780
,I/Messaging( 4390): mccmnc> 
,D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1210):  phoneType = -1
D/DraftCache( 4390): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4390): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1210): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4390): networkCode: 
,D/Messaging( 4390): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4390): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4390): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4390): createReceiver
,D/MessageCustFlag( 4390): sense_version=6.0
,D/Jerry   ( 4390): start to preload cursor >>>>>>>
D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1210):  phoneType = -1
,D/MmsSmsV2Provider( 1210): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1210): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
V/MmsProvider( 1210): Update uri=content://mms, match=0
,V/MmsProvider( 1210): selection=st=129 AND m_type!=134
,D/Messaging( 4390): mNeedToUpdateDate2: false
,D/Messaging( 4390): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4390): TransactionService is going to be woken up.
D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/MmsSmsV2Provider( 1210):  phoneType = -1
,V/TransactionService( 4390): 1-Creating TransactionService
,D/Messaging( 4390): ViewCache CreatePreload
,D/Messaging( 4390): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1210):  phoneType = -1
,D/MmsSmsV2Provider( 1210): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
V/TransactionService( 4390): onStartCommand: 1
,D/MmsSystemEventReceiver( 4390): unRegisterForConnectionStateChanges
V/TransactionService( 4390): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4390): Loading previous transactions.
,D/Cust_MMSMS( 4390): _has_set_default_values_2=true
,D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1210): sku_id=99
,D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1210): device_type: 1
,D/MsgPreferenceUtils( 4390): def_index: 0
,D/DraftCache( 4390): [DraftCache/451] rebuildCache
,D/MsgPreferenceUtils( 4390): globalIndex = 1
D/TransactionService( 4390): Force set service start id to 1
,V/TransactionService( 4390): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4390): unRegisterForConnectionStateChanges
D/MsgPreferenceUtils( 4390): phone state: true
D/MsgPreferenceUtils( 4390): sd state: false
,D/MsgPreferenceUtils( 4390): vIndex = 0
V/TransactionService( 4390): Destroying TransactionService
,D/TransactionService( 4390): stopSelfResult: true, mLastHandledServiceId: 1
,D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1210):  phoneType = -1
V/TransactionService( 4390): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MmsSmsV2Provider( 1210): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4390): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/Jerry   ( 1210): URI_DRAFT
,D/DraftCache( 4390): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4390): [DraftCache/451] rebuildCache time: 3
,D/MmsAsyncWorkHandler( 4390): 
D/MmsAsyncWorkHandler( 4390): HM tk = 20002
,D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1210): sku_id=99
,D/TelephUtils( 1210): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1210): sku_id=99
,D/PMS     (  905): acquireWL(423127e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=116686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(423127e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/GAV2    ( 4223): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=3415
,I/ActivityManager(  905): Killing 3415:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3415
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4365, uid=10111, userID:0
,D/Process (  905): killProcessQuiet, pid=4201
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4201:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4201
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4103
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4103:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4103
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4183): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4183): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4183): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{44008180 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1298): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1298): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
I/PackageManager(  905):   Scheme: "sms"
D/PackageBroadcastService( 1195): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1242): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/PeopleContactsSync( 1195): CP2 sync disabled
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,I/Launcher( 1242): Deferring update until onResume
,D/Launcher( 1242): waitUntilResume // bindAppsUpdated
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1195, uid=10028, userID:0
I/[PluginManager]RegisterService( 4183): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
I/[PluginManager]RegisterService( 4183): handle notify Blinkfeed plugin client changed
,D/AccTypeManager( 1298): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
D/PMS     (  905): acquireWL(425288e8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
I/ActivityManager(  905): Resuming delayed broadcast
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4480 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
D/PMS     (  905): releaseWL(425288e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
,E/ExternalAccountType( 1298): Unsupported attribute readOnly
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,D/PhoneApp( 1210): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4480, uid=10073, userID:0
,D/Finsky  ( 4480): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4480/10073)
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4480/10073)
,D/Finsky  ( 4480): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4480): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4480): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4480, uid=10073, userID:0
,D/Finsky  ( 4480): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4480): [1] 2.run: Finished loading 1 libraries.
,D/Process (  905): killProcessQuiet, pid=4223
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4223:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/IcingCorporaProvider( 2640): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,D/PMS     (  905): acquireWL(43b0bbb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3628 10160 null
,D/Finsky  ( 4480): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PMS     (  905): releaseWL(43b0bbb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4480): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm-heap( 3628): Grow heap (frag case) to 13.528MB for 1821008-byte allocation
I/ActivityManager(  905): Recipient 4223
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2640): UpdateCorporaTask done [took 208 ms] updated apps [took 208 ms] 
,W/PackageManager(  905): Unable to load service info ResolveInfo{425a90d8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1242): loadItems() com.htc.launcher.pageview.WidgetManager@41b24048 +
,I/Prism.WidgetManager( 1242): onLoadItems() +
,D/PMS     (  905): acquireWL(42a741d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
,V/AlarmManager(  905): sending alarm PendingIntent{42ff20a0: PendingIntentRecord{4259eea8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450201694149, Int=0
,D/PMS     (  905): releaseWL(42a741d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4480): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4480): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/asset   ( 1242): Copying FileAsset 0x64b071c8 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1242): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1242): onLoadItems() -
,I/Prism.ItemManager( 1242): loadItems() com.htc.launcher.pageview.WidgetManager@41b24048 -
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4480): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4480): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4480): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2),
,D/PhoneApp( 1210): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1210): -- N1 =0
,D/PhoneApp( 1210): -- N2 =0
,D/PhoneApp( 1210): -- N3 =0
,D/PMS     (  905): acquireWL(42ea3b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42ea3b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43692758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d0ef40: PendingIntentRecord{4241eff8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=139209, Int=0
,D/PMS     (  905): acquireWL(43373a48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(43692758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43fa8278): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43373a48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(43fa8278): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 4183): service - mHandler: update timezone
,D/AutoSetting( 4152): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4152): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4152): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4152): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4152): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4152): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4152): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4152): service - mHandler: update timezone
,D/AutoSetting( 4152): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4152): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4152): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4152): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1106): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41e54a20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.htc.htclocationservice 3 27 8 11
,D/AutoSetting( 4183): service - handleMessage() stop self
,D/AutoSetting( 4183): service - handleMessage() quit looper
,D/AutoSetting( 4183): service - onDestroy() END
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/PMS     (  905): acquireWL(43fd10d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{4245def8: PendingIntentRecord{4245de98 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141723, Int=0
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(4255b240): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
V/AlarmManager(  905): sending alarm PendingIntent{42174fb8: PendingIntentRecord{42384170 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142301, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{41ff26e0: PendingIntentRecord{4255b898 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450201709299, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/PMS     (  905): releaseWL(43fd10d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  905): acquireWL(43f4d520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =b34e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  905): releaseWL(43f4d520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ContactMessageStore( 1210): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1210): MSG_NOTIFY_CS_TO_SYNC <<
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Finsky  ( 4480): [1] 5.onFinished: Installation state replication succeeded.
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): releaseWL(4255b240): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43608a10 u0 com.htc.htclocationservice/.AutoSettingService}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42405e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42405e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 4152): service - handleMessage() stop self
,D/AutoSetting( 4152): service - onDestroy() END
,D/AutoSetting( 4152): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4280
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4280:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4280
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4401b3e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=176686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4401b3e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1210): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(4383e9f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4383e9f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4355e520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PMS     (  905): releaseWL(4355e520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(439a4cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dd2918: PendingIntentRecord{43e7b0d8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232155, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4533 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42439768: PendingIntentRecord{4247f770 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450201783826, Int=10800000
,D/PMS     (  905): releaseWL(439a4cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10047}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4533/10047)
,D/Process (  905): killProcessQuiet, pid=4312
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4312:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4312
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(43fc6330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=236686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43fc6330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43f9e258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43f9e258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43f9b578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=232159, Int=120000
,V/AlarmManager(  905): sending alarm PendingIntent{424fc930: PendingIntentRecord{423b7c60 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450201845640, Int=1800000
,D/PMS     (  905): acquireWL(43f83fe8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1195 10028 null
,D/PMS     (  905): releaseWL(43f9b578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  905): acquireWL(43f81570): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1195 10028 null
,D/PMS     (  905): releaseWL(43f83fe8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1195): Aggregate from 1450201675809 (log), 1450200045594 (data)
,D/PMS     (  905): releaseWL(43f81570): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  905): acquireWL(43f6f588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/BatteryService(  905): n_update end
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(43f6f588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e7ed60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=296687, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e7ed60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43bb0cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43bb0cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/Process (  905): killProcessQuiet, pid=4327
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4327:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4327
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(436cb110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=352159, Int=120000
,D/PMS     (  905): releaseWL(436cb110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(436661d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(436661d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(435a54a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=356686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(435a54a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(435a3fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435a3fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(430a6de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(430a6de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42d2f3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=416686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42d2f3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3844): Connected to the server!
I/jxcore-log( 3844): 
,I/chromium( 3844): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3844): --- start :testFindPeers.js---
I/jxcore-log( 3844): 
,I/jxcore-log( 3844): testFindPeers created [object Object]
I/jxcore-log( 3844): 
,I/jxcore-log( 3844): serverPort is 8876
I/jxcore-log( 3844): 
W/dalvikvm( 3844): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 3844): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 3844): threadid=1: thread exiting with uncaught exception (group=0x41661e30)
,E/AndroidRuntime( 3844): FATAL EXCEPTION: main
E/AndroidRuntime( 3844): Process: com.test.thalitest, PID: 3844
E/AndroidRuntime( 3844): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 3844): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 3844): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 3844): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 3844): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 3844): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 3844): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 3844): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 3844): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 3844): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 3844): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3844): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3844): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3844): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 3844): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3844): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3844): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 3844): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 3844): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  905): App crashed! Process: com.test.thalitest
W/ActivityManager(  905):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  905): killProcessQuiet, pid=4343
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  905): Killing 4343:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process ( 3844): killProcess, pid=3844
,D/Process ( 3844): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  905): Recipient 4343
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 3844 uid 10348
E/JavaBinder( 1181): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager(  905): Recipient 3844
,I/ActivityManager(  905): Process com.test.thalitest (pid 3844) has died.
,D/WifiService(  905): Client connection lost with reason: 4
,W/InputDispatcher(  905): channel '42523c40 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '42523c40 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '42523c40 com.test.thalitest.MainActivity (s)'
I/WindowState(  905): WIN DEATH: Window{42523c40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/WindowManager(  905): WINDOW DIED Window{42523c40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1341): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1341): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1341): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1341): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1341): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1106): com.google.android.gms (false,0)
,E/PlayEventLogger( 4480): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4480): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4480): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4480): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4480): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4480): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4480): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4480): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41e123d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.google.android.gms 1 11 3 12
,D/libc    ( 4480): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4480): [NET] getaddrinfo-,err=8
D/libc    ( 4480): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4480): [NET] getaddrinfo-, 1
,D/libc    ( 4480): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =bc6a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 256
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4480): [NET] getaddrinfo_proxy-, success
I/global  ( 4480): call createSocket() return a new socket.
D/libc    ( 4480): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4480): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4480): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4480): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(43550310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43550310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(425a3a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=472159, Int=120000
,D/PMS     (  905): releaseWL(425a3a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(4248a030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(4248a030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42d27ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=476686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42d27ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42451dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42451dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(423ab880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(423ab880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(422bbc10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=536687, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(422bbc10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(423db998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(423db998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43baf8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=592159, Int=120000
,D/PMS     (  905): releaseWL(43baf8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(42fd03b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42fd03b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42d36448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=596686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42d36448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(424891a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(424891a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1210): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1210): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1210): sku_id=99
,D/ContactMessageStore( 1210): start background delete task...
,D/ContactMessageStore( 1210): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1210): size: 0 , 0
,D/ContactMessageStore( 1210): Background delete complete,
,D/PMS     (  905): acquireWL(4200de98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4200de98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42e95470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=656686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e95470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42410c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42410c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42fc0150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=712159, Int=120000
,D/PMS     (  905): releaseWL(42fc0150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(41fade18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(41fade18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(41eda978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=716686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41eda978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(435a6ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/BatteryService(  905): n_update end
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(435a6ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(442a00d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(442a00d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1106): closing low battery warning: level=100
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42e49e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=776686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e49e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43ee97e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43ee97e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43ef5128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=832159, Int=120000
,D/PMS     (  905): releaseWL(43ef5128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(435a5cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=836686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(435a5cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41c03660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41c03660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42fc2170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42fc2170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43fdb7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=896687, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43fdb7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4252d0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
I/BatteryService(  905): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(4252d0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(424dc5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=956686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(424dc5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41b9a188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41b9a188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43f5c8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41d44b70: PendingIntentRecord{423ca7a0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783891, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=952159, Int=120000
,V/AlarmManager(  905): sending alarm PendingIntent{423aeb18: PendingIntentRecord{4239c0b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012488, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{422e63d8: PendingIntentRecord{42053c38 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450202504396, Int=900000
,D/PMS     (  905): acquireWL(43ba9910): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1341 10028 null
,V/AlarmManager(  905): sending alarm PendingIntent{42533928: PendingIntentRecord{43839d70 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450202576890, Int=0
,D/PMS     (  905): releaseWL(43ba9910): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): acquireWL(439c2f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,D/PMS     (  905): releaseWL(439c2f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4583 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  905): acquireWL(43fbe3d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1341 10028 null
,D/GCM     ( 1341): Message class mow
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1341/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/PMS     (  905): releaseWL(43fbe3d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  905): acquireWL(43f879f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,D/PMS     (  905): releaseWL(43f879f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4583): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4583): call getInstance()
,D/PMS     (  905): acquireWL(42fec0b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4583 1000 null
,D/SmartSyncUtils( 4583): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4583): MY_DEBUG = false
,D/PMS     (  905): releaseWL(43f5c8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): releaseWL(42fec0b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(43692488): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4583 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4583): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4583): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4583): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4583): SettingOnTime = 1450216800000, randomSettingOnTime = 1450216362000
D/SmartSyncScreenOnOffTimeReceiver( 4583): SettingOffTime = 1450206000000, randomSettingOffTime = 1450207250000
D/SmartSyncScreenOnOffTimeReceiver( 4583): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4583): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4583): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(43692488): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(4401f2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1016686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4401f2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44003be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(44003be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43f2cb88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1072159, Int=120000
,D/PMS     (  905): releaseWL(43f2cb88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(43f2ad58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43f2ad58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1106): closing low battery warning: level=100
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43bb2968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1076686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43bb2968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43bb2668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(43bb2668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(437db8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(437db8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  905): acquireWL(437db338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1136686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(437db338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43733ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(43733ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus,
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(435b22c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1192159, Int=120000
,D/PMS     (  905): releaseWL(435b22c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(435abbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1196686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(435abbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(435ab540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435ab540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(4344de68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4344de68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4341de78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1256687, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4341de78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43374170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(43374170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4271f828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1312159, Int=120000
,D/PMS     (  905): releaseWL(4271f828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(4255ed98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1316686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4255ed98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42473a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42473a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4240d8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(4240d8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(422c1890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000},
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1376686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(422c1890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(420f31f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/BatteryService(  905): n_update end
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(420f31f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(41ff2668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1432159, Int=120000
,D/PMS     (  905): releaseWL(41ff2668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(41dd27a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1436686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41dd27a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(420374a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(420374a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42fbed20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42fbed20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,D/PMS     (  905): acquireWL(42e61b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1496686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e61b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41d8e420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(41d8e420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(41aa16b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1552159, Int=120000
,D/PMS     (  905): releaseWL(41aa16b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(436bc300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436bc300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42920098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1556686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42920098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(423ba840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(423ba840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(424f5558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1616686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(424f5558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43adf720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43adf720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(424250e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1672159, Int=120000
,D/PMS     (  905): releaseWL(424250e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  905): acquireWL(41f6b4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(41f6b4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42fc8198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1676686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42fc8198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4238aa30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4238aa30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(424c0038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(424c0038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43ec4508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1736686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43ec4508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4203a338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4203a338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(428be230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(428be230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(436ae898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1796686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(436ae898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(4255b2e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41d44b70: PendingIntentRecord{423ca7a0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1733614, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1792159, Int=120000
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,V/AlarmManager(  905): sending alarm PendingIntent{42366518: PendingIntentRecord{4259eea8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450203366553, Int=0
,D/PMS     (  905): releaseWL(4255b2e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4480): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4480): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4480): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4480): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4480): [1] DailyHygiene.reschedule: Scheduling new run in 85 minutes (failures=3)
,D/PMS     (  905): acquireWL(42ea4680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42ea4680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  905): acquireWL(4244aec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
,V/AlarmManager(  905): sending alarm PendingIntent{4252bbf0: PendingIntentRecord{4255b898 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450203381703, Int=0
,D/PMS     (  905): releaseWL(4244aec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,I/ProcessStatsService(  905): Prepared write state in 43ms
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2015-12-15-05-01-22.bin
,D/Finsky  ( 4480): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  905): acquireWL(42498000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422df8d8: PendingIntentRecord{42335830 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1856686, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42498000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425d4a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425d4a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4629): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4629): ====startRecUseTime====
D/htc.customization.log.level( 4629):  is 
W/CustomizationLogLevel( 4629): Level value is invalid, use default level 2
D/PMS     (  905): acquireWL(426e6348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
V/AlarmManager(  905): sending alarm PendingIntent{41dfa970: PendingIntentRecord{43b53c78 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1912159, Int=120000
D/PMS     (  905): releaseWL(426e6348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
D/CustomizationManager( 4629):  Read ACC file spent 0.109 (s)
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4629): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4629): Parsing tag category name = system
I/CustomizationCIDLoader( 4629): Parsing tag category name = application
I/CustomizationCIDLoader( 4629): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4629): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4629): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4629): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4629): Parsing tag category name = Settings
D/CustomizationManager( 4629):  Read CID file spent 0.164 (s)
D/CustomizationManager( 4629):  All configurations done spent 0.164 (s)
W/HtcNativeFlag( 4629): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4629): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4629): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4629): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4629, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
W/asset   (  905): Copying FileAsset 0x63b0bda8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  905): Skipping PackageSetting{42203608 com.example.hello/10356} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/dalvikvm-heap( 3628): Grow heap (frag case) to 15.224MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
I/acms    ( 1758): Unregistering com.test.thalitest
D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/PMS     (  905): acquireWL(43702708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1422 10028 null
D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
E/acms    ( 1758): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1422): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1298): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1298): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(43702708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
D/VoicemailCleanupService( 1269): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1298): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
I/Launcher( 1242): Deferring update until onResume
D/Launcher( 1242): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
D/PackageBroadcastService( 1195): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4643 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1298): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
W/Parcel  ( 1225): Reading a NULL string not supported here.
I/MultiDex( 4643): install
I/ActivityManager(  905): Delaying start of: ServiceRecord{43f8bb60 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/MultiDex( 4643): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
I/MultiDex( 4643): loading existing secondary dex files
I/MultiDex( 4643): load found 1 secondary dex files
I/MultiDex( 4643): install done
I/PeopleContactsSync( 1195): CP2 sync disabled
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
D/PhoneApp( 1210): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/Icing   ( 1195): doRemovePackageData com.test.thalitest
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1195, uid=10028, userID:0
D/PMS     (  905): acquireWL(43a77180): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  905): releaseWL(43a77180): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4661 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4643): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4661): install
I/MultiDex( 4661): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4661): loading existing secondary dex files
I/MultiDex( 4661): load found 1 secondary dex files
I/MultiDex( 4661): install done
I/ActivityManager(  905): Resuming delayed broadcast
I/ProviderInstaller( 4661): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 4183): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 4183): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Resuming delayed broadcast
D/Process (  905): killProcessQuiet, pid=4365
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1242): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  905): Killing 4365:com.google.android.talk/u0a111 (adj 15): empty #17
I/IcingCorporaProvider( 2640): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4682 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4643): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4643): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4643): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4643): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4643): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4643): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4643): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4643): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4643): threadid=12: thread exiting with uncaught exception (group=0x41661e30)
E/AndroidRuntime( 4643): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4643): Process: com.google.android.gms.drive, PID: 4643
E/AndroidRuntime( 4643): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4643): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4643): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4643): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4643): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4643): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4643): 	at ctn.run(SourceFile:985)
I/ActivityManager(  905): Recipient 4365
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
D/Process ( 4643): killProcess, pid=4643
D/Process ( 4643): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  905): Can't write: system_app_crash
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
E/SQLiteLog( 2640): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2640): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x643363a8
W/dalvikvm( 2640): threadid=14: thread exiting with uncaught exception (group=0x41661e30)
E/AndroidRuntime( 2640): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2640): Process: com.google.android.googlequicksearchbox:search, PID: 2640
E/AndroidRuntime( 2640): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2640): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2640): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2640): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2640): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2640): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2640): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2640): 	at cid.d(PG:186)
E/AndroidRuntime( 2640): 	at clo.g(PG:594)
E/AndroidRuntime( 2640): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2640): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2640): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2640): 	at clr.tL(PG:827)
E/AndroidRuntime( 2640): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2640): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2640): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  905): Recipient 4643
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4643) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/Process ( 2640): killProcess, pid=2640
D/Process ( 2640): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
I/ActivityManager(  905): Recipient 2640
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2640): Died!
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2640) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/WifiService(  905): Client connection lost with reason: 4
E/SQLiteDatabase( 4682): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4682): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4682): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4682): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4682): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4682): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4682): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4682): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4682): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4682): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4682): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4682): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4682): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4682): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4682): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4682): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4682): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4682): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4682): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4682): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4682): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4682): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4682): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4682): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4682): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4682): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4682): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4682): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4682): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4682): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4682): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4682): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4682): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4682): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4682): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4682): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4682): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4682): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4682): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4682): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4682): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4682): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4682): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4682): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4682): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4682): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4682): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4682): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4682): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4682): threadid=11: thread exiting with uncaught exception (group=0x41661e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4682): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4682): Process: com.google.android.apps.docs, PID: 4682
E/AndroidRuntime( 4682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4682): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4682): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4682): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4682): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4682): 	at aho.run(AbstractDatabaseInstance.java:455)
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
D/Process ( 4682): killProcess, pid=4682
D/Process ( 4682): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4700 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/PackageManager(  905): Unable to load service info ResolveInfo{4254b0e0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  905): Recipient 4682
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4682) has died.
W/ContextImpl( 4700): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4700): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4700): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4700): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4700): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4700): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4700): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4700): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4700): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4700): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4700): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4700): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4700): threadid=10: thread exiting with uncaught exception (group=0x41661e30)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4713 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4700): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4700): Process: com.android.keychain, PID: 4700
E/AndroidRuntime( 4700): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4700): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4700): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4700): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4700): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4700): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4700): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4700): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4700): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4700): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4700): killProcess, pid=4700
D/Process ( 4700): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4713): getInstance(Context context)
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450203477378.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  905): Recipient 4700
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4700) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10338ms
D/Process (  905): killProcessQuiet, pid=3809
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.appDiedLocked:4131 
D/Process (  905): killProcessQuiet, pid=3793
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.appDiedLocked:4131 
I/ActivityManager(  905): Killing 3809:com.android.settings:remote/1000 (adj 15): empty for 1800s
I/ActivityManager(  905): Killing 3793:com.htc.calendar/u0a13 (adj 15): empty for 1800s
D/Process (  905): killProcessQuiet, pid=4415
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/AppTag  ( 4713): getInstance(Context context)
I/ActivityManager(  905): Killing 4415:com.htc.widget.hmsproc1/u0a38 (adj 15): empty for 1800s
D/AppTag  ( 4713): onCreate()
I/ActivityManager(  905): Recipient 3793
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1242): loadItems() com.htc.launcher.pageview.WidgetManager@41b24048 +
I/Prism.WidgetManager( 1242): onLoadItems() +
I/ActivityManager(  905): Recipient 3809
I/ActivityManager(  905): Recipient 4415
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
D/Process (  905): killProcessQuiet, pid=4429
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  905): Killing 4429:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1800s
D/PMS     (  905): acquireWL(43fd8c30): PARTIAL_WAKE_LOCK  AsyncService 0x1 3628 10160 null
I/ActivityManager(  905): Recipient 4429
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/dalvikvm-heap( 3628): Grow heap (frag case) to 16.963MB for 1821008-byte allocation
D/Process (  905): killProcessQuiet, pid=4295
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4731 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  905): Killing 4295:com.htc.task/u0a70 (adj 15): empty for 1800s
D/PMS     (  905): releaseWL(43fd8c30): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  905): Recipient 4295
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 4731): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4731 dbg=false s=true
I/DeviceManagement( 4731): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4731): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4731): WorkflowService: Starting workflow service
I/DeviceManagement( 4731): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41abfee8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4731): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4731): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4731): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4731): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4745 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4731): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4731): SessionStateController: Checking invariants...

```
