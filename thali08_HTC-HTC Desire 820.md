#### Test 506502784dae475_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  905): mEventCount = 1200
,E/cutils-trace( 3865): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3865): ====startRecUseTime====
D/htc.customization.log.level( 3865):  is 
W/CustomizationLogLevel( 3865): Level value is invalid, use default level 2
D/CustomizationManager( 3865):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3865): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3865): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3865): Parsing tag category name = system
I/CustomizationCIDLoader( 3865): Parsing tag category name = application
I/CustomizationCIDLoader( 3865): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3865): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3865): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3865): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3865): Parsing tag category name = Settings
D/CustomizationManager( 3865):  Read CID file spent 0.096 (s)
D/CustomizationManager( 3865):  All configurations done spent 0.096 (s)
W/HtcNativeFlag( 3865): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3865): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3865): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3865): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3865
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1135353216
D/PMS     (  905): acquireHCC(4347c800): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(43478e58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
D/PMS     (  905): acquireWL(4346d730): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b925b0
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3876 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1248): [trimMemory] 20
W/asset   ( 3876): Copying FileAsset 0x5c7b6428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3876): Binding Chromium to main looper Looper (main, tid 1) {41a713a0}
I/LibraryLoader( 3876): Expected native library version number "",actual native library version number ""
I/chromium( 3876): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3876): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(433d4570): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(433cfec0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440741d0:true
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3876): 1101557928: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  905): releaseWL(433d4570): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3876): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3876): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3876): Local Branch: 
I/Adreno-EGL( 3876): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3876): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3876):                  aa63bbd948f41d15fc72f585e
W/chromium( 3876): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3876): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3876): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3876): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3876): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3876): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3876): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3876): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3876): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3876): CordovaWebView is running on device made by: HTC
,W/AwContents( 3876): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1248
,W/ResourceType( 3876): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3876): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ab8630, mServedView=org.apache.cordova.engine.SystemWebView{41a7e3c0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +309ms
,W/AwContents( 3876): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Enable input method client, pid=3876
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  905): releaseWL(4346d730): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3876): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3876): JniHelper::setJavaVM(0x41544048), pthread_self() = 1663845608
,D/JX-Cordova( 3876): jxcore cordova android initializing
W/dalvikvm( 3876): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 11.509MB for 63974-byte allocation
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 11.562MB for 95956-byte allocation
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 11.642MB for 143930-byte allocation
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 11.759MB for 215890-byte allocation
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 11.934MB for 323830-byte allocation
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 12.596MB for 728606-byte allocation
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 13.193MB for 1092904-byte allocation
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 14.062MB for 1639352-byte allocation
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 15.436MB for 2459024-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(4347c800): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(43478e58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3876): Grow heap (frag case) to 17.399MB for 3688532-byte allocation
,W/jxcore-log( 3876): Initializing JXcore engine
,W/jxcore-log( 3876): JXcore engine is ready
,W/jxcore-log( 3876): Starting JXcore engine
,W/jxcore-log( 3876): Platform android
W/jxcore-log( 3876): 
,W/jxcore-log( 3876): Process ARCH arm
W/jxcore-log( 3876): 
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3920 uid=10077 gids={50077}
,D/PMS     (  905): acquireWL(43378988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
,V/AlarmManager(  905): sending alarm PendingIntent{41df0060: PendingIntentRecord{425fa578 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449751011535, Int=60000
,D/PMS     (  905): releaseWL(43378988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3920): SMSBackupAgentService started
,D/SMSBackup( 3920): Checking restore status
,D/SMSBackup( 3920): Restore complete
,D/SMSBackup( 3920): cancelCheckAlarm
,D/SMSBackup( 3920): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=3369
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3369:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/PMS     (  905): releaseWL(433cfec0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  905): Recipient 3369
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 3369): Died!
,I/jxcore-log( 3876): JXcore Cordova bridge is ready!
I/jxcore-log( 3876): 
,W/jxcore-log( 3876): JXcore engine is started
,I/chromium( 3876): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3876): Toggling radios to true
I/jxcore-log( 3876): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  905): checking for enable restriction...
D/BluetoothManagerService(  905): checkBTEasState, ret=true
,I/BluetoothManagerService(  905): isBluetoothRestricted(): false
,D/BluetoothManagerService(  905): enable(): region ID = 6
D/BluetoothManagerService(  905): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 1
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 915
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 3(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  905): MESSAGE_ENABLE: mBluetooth = null
D/WifiManager( 3876): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=3876, uid=10348
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 1427
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,I/ActivityManager(  905): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3935 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 9(ms)
D/WifiManager( 3876): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiManager( 3876): reconnect: Base Package Name=com.test.thalitest, uid=10348
D/PMS     (  905): acquireWL(432e43b0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
I/jxcore-log( 3876): Radios toggled
I/jxcore-log( 3876): 
,D/AdapterServiceConfig( 3935): Adding HeadsetService
D/AdapterServiceConfig( 3935): Adding A2dpService
D/AdapterServiceConfig( 3935): Adding HidService
D/AdapterServiceConfig( 3935): Adding HealthService
D/AdapterServiceConfig( 3935): Adding PanService
,D/AdapterServiceConfig( 3935): Adding GattService
,W/linker  ( 3935): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3935): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43676570:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3935): make
,I/BluetoothAdapterState( 3935): Entering OffState,
,I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3935): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  905): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapter( 1488): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41cefa08
,D/BluetoothAdapter( 1488): onBluetoothServiceUp done
,D/BluetoothAdapter( 1221): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41ae3f18
,D/BluetoothAdapter( 1221): onBluetoothServiceUp done
,D/BluetoothAdapter( 1110): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e8fa30
D/BluetoothAdapter( 1110): onBluetoothServiceUp done
D/BluetoothAdapter(  905): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4367a028
,D/BluetoothAdapter(  905): onBluetoothServiceUp done
D/BluetoothAdapter( 1232): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41ba8160
,D/BluetoothAdapter( 1232): onBluetoothServiceUp done
,D/BluetoothAdapter( 1755): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42085968
,D/BluetoothAdapter( 1755): onBluetoothServiceUp done
D/BluetoothAdapter( 3935): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41a8acf8
,D/BluetoothAdapter( 3935): onBluetoothServiceUp done
,D/BluetoothAdapter( 3876): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@425c59f8
,D/BluetoothAdapter( 3876): onBluetoothServiceUp done
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3935): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3935): Setting state to 11
I/BluetoothAdapterState( 3935): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3935): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3935): make
,I/IntentController( 1110): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3935): StableState(): Entering Off State
D/HeadsetService( 3935): Received start request. Starting profile...
D/HeadsetStateMachine( 3935): Version 1.6
,D/HeadsetStateMachine( 3935): make
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3961 uid=10037 gids={50037, 3002, 3001}
,I/HeadsetStateMachine( 3935): setCurrentDevice, the latest mCurrentDevice is:null
,I/BluetoothAdapterState( 3935): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/QuickSettingBluetooth( 1110): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpService( 3935): Received start request. Starting profile...
V/Avrcp   ( 3935): make
,D/Avrcp   ( 3935): fillIntentFilter()
,D/A2dpStateMachine( 3935): make
,D/A2dpStateMachine( 3935): Enter Disconnected: -2
,D/HidService( 3935): Received start request. Starting profile...
,D/HealthService( 3935): Received start request. Starting profile...
D/HtcBtWidget_BTWidgetProvider( 3961): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3961): updateWidget(context) for widget: 
,D/PanService( 3935): Received start request. Starting profile...
,D/BluetoothTethering(  905): supplyMessenger
D/BluetoothTethering(  905): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  905): got MESSAGE_CONNECT_PANSERVICE, call connect
D/Process (  905): killProcessQuiet, pid=3708
D/PanService( 3935): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  905): got CMD_CHANNEL_HALF_CONNECTED
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/BtGatt.DebugUtils( 3935): handleDebugAction() action=null
D/BtGatt.GattService( 3935): Received start request. Starting profile...
,D/BtGatt.GattService( 3935): start()
V/BluetoothPbapService( 3935): Pbap Service onCreate
,V/BluetoothPbapService( 3935): Starting PBAP service
,I/ActivityManager(  905): Killing 3708:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 11
,D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 11
,E/BluetoothMasService( 3935): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 3935): Add permission for SmsProvider.
,V/BluetoothMasService( 3935): Starting MAS instances
,D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 11
,I/MailMessageReceiver( 3935): reg:com.android.bluetooth.btservice.AdapterApp@41a7e260 with com.htc.util.mail.MailMessageReceiver@41abe5d0
I/ActivityManager(  905): Recipient 3708
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
I/MailManager( 3935): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41abe5d0
V/EmailUtils( 3935): Manager Instance is not NULL
,I/ActivityManager(  905): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3980 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  905): interfaceAdded wlan0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): wlan0 is not a tetherable iface, ignoring
,D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): interfaceAdded p2p0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): p2p0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/PMS     (  905): releaseWL(432e43b0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/EmailUtils( 3935): ============NULL aList========
V/EmailUtils( 3935): <-getEmailAccountIdList
,V/BluetoothMasService( 3935): onCreate: mIsEmailEnabled: true
,I/wpa_supplicant( 3996): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 3996): Add randomness: count=1 entropy=0
D/wpa_supplicant( 3996): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3996): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 3996): Get randomness: len=20 entropy=1
D/wpa_supplicant( 3996): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3996): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 3996): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 3996): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3996): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 3996): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3996): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3996): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3996): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3996): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3996): update_config=1
D/wpa_supplicant( 3996): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3996): device_name='Android_63cc'
D/wpa_supplicant( 3996): manufacturer='HTC'
D/wpa_supplicant( 3996): model_name='HTC_PHONE'
D/wpa_supplicant( 3996): model_number='1234'
D/wpa_supplicant( 3996): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3996): p2p_oper_reg_class=126
D/wpa_supplicant( 3996): p2p_oper_channel=36
D/wpa_supplicant( 3996): p2p_ssid_postfix='-Android_63cc'
,D/wpa_supplicant( 3996): persistent_reconnect=1
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 3996): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3996): nl80211: RFKILL status not available
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 95,
D/wpa_supplicant( 3996): nl80211: Using driver-based roaming
D/wpa_supplicant( 3996): nl80211: TDLS supported
D/wpa_supplicant( 3996): nl80211: TDLS external setup
D/wpa_supplicant( 3996): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3996): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3996): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3996): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3996): nl80211: Driver is new enough to support monitor-less mode,
D/wpa_supplicant( 3996): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 3996): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3996): nl80211: Subscribe to mgmt frames with non-AP handle 0xb88e7758
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758,
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88e7758
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 3996): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3996): htc_wext_command_init +
E/wpa_supplicant( 3996): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 3996): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3996): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 95
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3996): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3996): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3996): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3996): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3996): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5490-5710 @ 80 MHz,
D/wpa_supplicant( 3996): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 3996): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 11
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
V/BluetoothMasService( 3935): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3935): Manager Instance is not NULL
,D/EmailUtils( 3935): ============NULL aList========
,V/EmailUtils( 3935): <-getEmailAccountIdList
V/BluetoothSapService( 3935): Sap Service onCreate
,V/BluetoothSapService( 3935): initBinder
V/BluetoothSapService( 3935): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41ac39c0
,V/BluetoothSapReceiver( 3935): BluetoothSapReceiver init
,D/BluetoothSapService( 3935): setSapService()
V/BluetoothSapService( 3935): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3935): state: 12
,D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 11
D/BluetoothAdapterService( 3935): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3935): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3935): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3935): Profile still not running:com.android.bluetooth.pan.PanService
,D/HeadsetPhoneState( 3935): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/PanService( 3935): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothAdapterService( 3935): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3935): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  905): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  905): killProcessQuiet, pid=3352
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 3352:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/BluetoothMasReceiver( 3935): Bluetooth STATE CHANGED to 11
,I/qcom-bluetooth( 4001): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,D/WifiMonitor(  905): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager(  905): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4004 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/IntentController( 1110): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1110): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/qcom-bluetooth( 4015): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4022): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
I/ActivityManager(  905): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4017 uid=10048 gids={50048}
,I/qcom-bluetooth( 4034): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4035): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4036): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4037): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/ActivityManager(  905): Recipient 3352
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/QuickSettingWifi( 1110): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4004): Received state change = 11
,D/HtcWiFiWidget_WiFiWidgetProvider( 4017): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4017): updateWidget(context) for widget: 
,D/Process (  905): killProcessQuiet, pid=3731
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  905): Killing 3731:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3731
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): New client listening to asynchronous messages
I/wpa_supplicant( 3996): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 3996):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3996):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3996):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3996): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3996): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3996): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3996): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3996): nl80211: Flush PMKIDs
E/wpa_supplicant( 3996): send_and_recv error -22 - cmd 54
I/wpa_supplicant( 3996): State: DISCONNECTED -> INACTIVE
,D/Process (  905): killProcessQuiet, pid=3305
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3305:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3305
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 3996): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3996): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3996): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 3996): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
,D/wpa_supplicant( 3996): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3996): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3996): Using existing control interface directory.
D/wpa_supplicant( 3996): ctrl_iface bind(PF_UNIX) failed: Address already in use
,D/wpa_supplicant( 3996): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 3996): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0',
D/wpa_supplicant( 3996): P2P: Own listen channel: 1
D/wpa_supplicant( 3996): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 3996): P2P: Add operating class 81,
I/wpa_supplicant( 3996): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 3996): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3996): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3996): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3996): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3996): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3996): disable_scan_offload=1
D/wpa_supplicant( 3996): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 3996): update_config=1
D/wpa_supplicant( 3996): uuid=12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 3996): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3996): manufacturer='HTC'
D/wpa_supplicant( 3996): model_name='HTC Desire 820'
D/wpa_supplicant( 3996): model_number='HTC Desire 820'
D/wpa_supplicant( 3996): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 3996): persistent_reconnect=1
D/wpa_supplicant( 3996): p2p_disabled=1
D/wpa_supplicant( 3996): hs20=1
D/wpa_supplicant( 3996): interworking=1
D/wpa_supplicant( 3996): Line: 18 - start of a new network block
D/wpa_supplicant( 3996): key_mgmt: 0x2
D/wpa_supplicant( 3996): priority=1 (0x1)
,D/wpa_supplicant( 3996): signinfail=0 (0x0)
,I/qcom-bluetooth( 4041): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/qcom-bluetooth( 4042): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3935): btu_task pending for preload complete event
,D/wpa_supplicant( 3996): Priority group 1
D/wpa_supplicant( 3996):    id=0 ssid='NG700'
I/wpa_supplicant( 3996): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3996): nl80211: RFKILL status not available
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3996): nl80211: Using driver-based roaming
D/wpa_supplicant( 3996): nl80211: TDLS supported
D/wpa_supplicant( 3996): nl80211: TDLS external setup
D/wpa_supplicant( 3996): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3996): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3996): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3996): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3996): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3996): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 3996): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3996): nl80211: Subscribe to mgmt frames with non-AP handle 0xb88f7718
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3996): htc_wext_command_init +
I/wpa_supplicant( 3996): htc_wext_command_init -
I/wpa_supplicant( 3996): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 3996): Don't set 00 to countryID.conf
D/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 3996): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 3996): nl80211: Use separate P2P group interface
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3996): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3996): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3996): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3996): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3996): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3996): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 3996): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 3996):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3996):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 3996):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3996): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3996): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3996): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3996): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3996): nl80211: Flush PMKIDs
,E/wpa_supplicant( 3996): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 3996): TDLS: TDLS operation supported by driver
,D/wpa_supplicant( 3996): TDLS: Driver uses external link setup
D/wpa_supplicant( 3996): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 3996): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3996): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3996): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3996): Using existing control interface directory.,
,I/wpa_supplicant( 3996): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3996): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 3996): Auto country group 1: ch36
I/wpa_supplicant( 3996): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3996): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 3996): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3996): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3996): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 3996): Get randomness: len=20 entropy=0
D/wpa_supplicant( 3996): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,I/wpa_supplicant( 3996): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_905-2
D/wpa_supplicant( 3996): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 3996): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3996): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3996): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3996): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3996): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3996): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3996): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3996): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3996): nl80211: Event message available
D/wpa_supplicant( 3996): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 3996): nl80211: Regulatory domain change
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3996): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3996): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3996): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3996): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3996): P2P: Add operating class 81
D/wpa_supplicant( 3996): P2P: Add operating class 115
D/wpa_supplicant( 3996): P2P: Add operating class 116
D/wpa_supplicant( 3996): P2P: Add operating class 117
D/wpa_supplicant( 3996): P2P: Update channel list
D/wpa_supplicant( 3996): p2p0: Updating hw mode
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3996): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3996): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3996): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3996): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 3996): nl80211: Added 802.11b mode based on 802.11g information
D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): set wifi ON
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER MACADDR
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiConfigStore(  905): Loading config and enabling all networks
D/WifiNative-wlan0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): list_network_info: ret=0x1, pos=0xb88fa117 buf=0xb88fa0e8
I/wpa_supplicant( 3996): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3996): 0	NG700	any	
V/RegulatoryObserver(  905): uevent:
V/RegulatoryObserver(  905): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  905): Regulatory Country Code:DE
V/RegulatoryObserver(  905): Start wifi-crda service to run crda.
V/RegulatoryObserver(  905): Country Code is DE
V/RegulatoryObserver(  905): Send broadcast country code message.
I/RegulatoryObserver(  905): Broadcast intent for crda country code: DE
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiNative-wlan0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  905): 0	NG700	any	
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 bssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 priority
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wep_key0'
I/IntentController( 1110): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
,D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
,D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
,D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'user_cert_file'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wapi_psk'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 3996): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 proto
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  905): Failed to look-up a string: W
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 group
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='group'
,E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WIFI_ICON( 1110): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK key
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/HtcWiFiWidget_WiFiWidgetProvider( 4017): onWiFiStateChanged() for widget: 
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
,D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_as_cert
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 limited
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 signinfail
D/HtcWiFiWidget_WiFiWidgetProvider( 4017): updateWidget(context) for widget: 
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 eap
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='eap'
,D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 phase2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 password
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'engine_id'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 private_key
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 3996): CTRL_IFACE: Failed to get network variable 'private_key'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  905): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  905): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 3996): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3996): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET manufacturer HTC
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 3996): manufacturer='HTC',
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_name HTC Desire 820
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 3996): model_name='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'model_number'='HTC Desire 820'
,D/wpa_supplicant( 3996): model_number='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 3996): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET device_type 10-0050F204-5
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 3996): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET auto_interworking 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 3996): auto_interworking=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): wlan0: Setting scan interval: 15 sec
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): SET_SCREEN_ON:On
I/wpa_supplicant( 3996): htc_wext_set_keepalive +
I/wpa_supplicant( 3996): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3996): getPrivFuncNum +	
I/wpa_supplicant( 3996): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3996): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3996): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3996): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3996): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET ps 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 3996): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  905): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  905): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 3996): wpa_supplicant_scan enter
,I/wpa_supplicant( 3996): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3996): ap_scan=1 , scan_req =1
I/wpa_supplicant( 3996): wpa_supplicant_trigger_scan +
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 3996): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): SETBAND: 0
D/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 3996): P2P: Add operating class 81
D/wpa_supplicant( 3996): P2P: Add operating class 115
,D/wpa_supplicant( 3996): P2P: Add operating class 116
D/wpa_supplicant( 3996): P2P: Add operating class 117
D/wpa_supplicant( 3996): P2P: Update channel list
I/wpa_supplicant( 3996): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 3996): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3996): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 3996): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 3996): p2p_oper_reg_class=126
D/wpa_supplicant( 3996): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3996): P2P: New SSID postfix: -Android_63cc
,E/wpa_supplicant( 3996): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3996): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 3996): p2p_oper_channel=36
E/wpa_supplicant( 3996): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3996): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/wpa_supplicant( 3996): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 3996): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 3996): P2P_OP_CH: save_config, class=126, ch=36
D/wpa_supplicant( 3996): nl80211: Event message available
,D/wpa_supplicant( 3996): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: BSS_FLUSH 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 3996): wpa_supplicant_scan enter
D/WifiNative-wlan0(  905):    returned true
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiMonitor(  905): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  905): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 3996): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 3996): persistent_reconnect=1
I/wpa_supplicant( 3996): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_name Android_63cc
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_name Android_63cc"
,D/wpa_supplicant( 3996): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 3996): device_name='Android_63cc'
I/wpa_supplicant( 3996): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 3996): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 3996): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 3996): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 3996): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
,D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 3996): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 3996): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
,D/wpa_supplicant( 3996): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3996): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 3996): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 3996): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 3996): Single channel concurrency preference: sta
I/wpa_supplicant( 3996): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  905):    returned true
,D/WifiNative-p2p0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  905): doBoolean: P2P_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 3996): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 3996): P2P: Stopping find
D/wpa_supplicant( 3996): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 3996): P2P: State IDLE -> IDLE
I/wpa_supplicant( 3996): Recv Cmd 2: P2P_FLUSH
,D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 3996): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 3996): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: LIST_NETWORKS
D/WifiP2pService(  905): P2pEnablingState
D/WifiP2pService(  905): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2p socket connection successful
D/WifiP2pService(  905): P2pEnabledState
,D/WifiP2pService(  905): sending p2p connection changed broadcast
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  905): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  905): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiP2pService(  905): Send p2p flush in initializeP2pSettings
W/WifiHW  (  905): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 3996): list_network_info: ret=0x22, pos=0xb88fa10a buf=0xb88fa0e8
I/wpa_supplicant( 3996): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3996): Recv Cmd 2: LIST_NETWORKS
,D/WifiNative-p2p0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  905): doBoolean: AP_SCAN 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  905):    returned false
D/WifiNative-p2p0(  905): doBoolean: SET wifi_display 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 3996): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 3996): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 3996): WFD: Update WFD IE
I/wpa_supplicant( 3996): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3996): Recv Cmd 2: SET wifi_display
,D/WifiNative-p2p0(  905):    returned true
I/QuickSettingWifi( 1110): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  905): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  905): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 3996): WFD: Set subelement 0
D/wpa_supplicant( 3996): WFD: Update WFD IE
I/wpa_supplicant( 3996): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3996): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  905):    returned true
,V/AudioService(  905): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  905):     Client/Owner: Client
V/AudioService(  905):     GroupId: 
V/AudioService(  905):     Passphrase: 
V/AudioService(  905):     SessionId: 0
V/AudioService(  905):     IP Address: }
D/HtcEffectManagerBase(  905): onEventChanged id=5 status=false
,D/HtcEffectManager(  905): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
,D/HtcEffectManager(  905): convertEffect before=902
,D/HtcEffectManager(  905): convertEffect after=902
,D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
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
D/WifiP2pService(  905): InactiveState{ when=-10ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-10ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  905): Successfully set WFD info.
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  905):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  905):  primary type: 10-0050F204-5
D/WifiDisplayController(  905):  secondary type: null
D/WifiDisplayController(  905):  wps: 0
D/WifiDisplayController(  905):  grpcapab: 0,
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
,D/wpa_supplicant( 3996): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 3996): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 3996): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false,
,D/wpa_supplicant( 3996): nl80211: Event message available
D/wpa_supplicant( 3996): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 3996): Got an original EVENT_SCAN_RESULTS
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3996): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 3996): nl80211: Survey data missing
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3996): Sorted scan results
I/wpa_supplicant( 3996): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 3996): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 3996): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 3996): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
I/wpa_supplicant( 3996): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-83
D/wpa_supplicant( 3996): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 3996): Add randomness: count=2 entropy=0
D/wpa_supplicant( 3996): Add randomness: count=3 entropy=1
D/wpa_supplicant( 3996): Add randomness: count=4 entropy=2
D/wpa_supplicant( 3996): Add randomness: count=5 entropy=3
D/wpa_supplicant( 3996): Add randomness: count=6 entropy=4
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
,D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 3996): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3996): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3996): wpa_supplicant_pick_network+
I/wpa_supplicant( 3996): Selecting BSS from priority group 1
I/wpa_supplicant( 3996): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3996): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3996): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 3996): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 3996): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 3996):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 3996):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 3996): Start print parameters
I/wpa_supplicant( 3996): wpa_s->wpa_state is 3
I/wpa_supplicant( 3996): wpa_s->br_have_IP is 0
I/wpa_supplicant( 3996): isConcurrentMode() is 0
I/wpa_supplicant( 3996): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 3996): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 3996): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 3996): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 3996): wpa_s->reassociate is 0
I/wpa_supplicant( 3996): wpa_s->is_screen_on 1
,I/wpa_supplicant( 3996): wpa_s->ifname wlan0
I/wpa_supplicant( 3996): End print parameters
I/wpa_supplicant( 3996): selected network = 2
D/wpa_supplicant( 3996): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb88f84e8  current_ssid=0x0
D/wpa_supplicant( 3996): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3996): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 3996): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 3996): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 3996): check if in concurrent case
I/wpa_supplicant( 3996): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 3996): wpa_supplicant_associate, 1777
D/wpa_supplicant( 3996): wpa_supplicant_associate, 1780
D/wpa_supplicant( 3996): wpa_supplicant_associate, 1795
D/wpa_supplicant( 3996): RSN: PMKSA cache search - network_ctx=0xb88f84e8 try_opportunistic=0
D/wpa_supplicant( 3996): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3996): RSN: No PMKSA cache entry found
I/wpa_supplicant( 3996): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3996): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3996): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 3996): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3996): nl80211: Unsubscribe mgmt frames handle 0xb88f7718 (mode change)
D/wpa_supplicant( 3996): nl80211: Subscribe to mgmt frames with non-AP handle 0xb88f7718
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Register frame type=0xd0 nl_handle=0xb88f7718
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3996): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 3996):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3996):   * freq=2412
D/wpa_supplicant( 3996):   * Auth Type 0
D/wpa_supplicant( 3996):   * WPA Versions 0x2
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 3996): nl80211: Connect request send successfully
D/wpa_supplicant( 3996): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_su,pplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3996): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 3996): reply (632) for get BSS: id=0
I/wpa_supplicant( 3996): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3996): freq=5220
I/wpa_supplicant( 3996): level=-48
I/wpa_supplicant( 3996): tsf=0000000103841347
I/wpa_supplicant( 3996): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3996): ssid=NG7005g,
I/wpa_supplicant( 3996): ====
I/wpa_supplicant( 3996): id=1
I/wpa_supplicant( 3996): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 3996): freq=2412
I/wpa_supplicant( 3996): level=-47
I/wpa_supplicant( 3996): tsf=0000000103841359
I/wpa_supplicant( 3996): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 3996): ssid=01ABC
I/wpa_supplicant( 3996): ====
I/wpa_supplicant( 3996): id=2
I/wpa_supplicant( 3996): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3996): freq=2412
I/wpa_supplicant( 3996): level=-47
I/wpa_supplicant( 3996): tsf=0000000103841362
I/wpa_supplicant( 3996): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3996): ssid=NG700
I/wpa_supplicant( 3996): ====
I/wpa_supplicant( 3996): id=3
I/wpa_supplicant( 3996): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 3996): freq=2427
I/wpa_supplicant( 3996): level=-71
I/wpa_supplicant( 3996): tsf=0000000103841367
I/wpa_supplicant( 3996): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 3996): ssid=Gonzos
I/wpa_supplicant( 3996): ====
I/wpa_supplicant( 3996): id=4
I/wpa_supplicant( 3996): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 3996): freq=2462
I/wpa_supplicant( 3996): level=-83
I/wpa_supplicant( 3996): tsf=0000000103841371
I/wpa_supplicant( 3996): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 3996): ssid=UPC Wi-Free
I/wpa_supplicant( 3996): ####
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 103841347, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -47, frequency: 2412, timestamp: 103841359, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 103841362, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2427, timestamp: 103841367, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -83, frequency: 2462, timestamp: 103841371, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/wpa_supplicant( 3996): EAPOL: disable timer tick
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3996): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3996): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3996): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 3996): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 3996): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 3996): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3996): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3996): nl80211: Event message available
D/wpa_supplicant( 3996): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 3996): nl80211: Connect event
D/wpa_supplicant( 3996): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 3996): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3996): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 3996): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3996): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3996): Add randomness: count=7 entropy=5
I/wpa_supplicant( 3996): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 3996): TDLS: Remove peers on association
D/wpa_supplicant( 3996): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 3996): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 3996): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 3996): htc_wext_set_keepalive +
I/wpa_supplicant( 3996): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 3996): getPrivFuncNum +	
I/wpa_supplicant( 3996): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3996): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3996): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3996): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3996): Get randomness: len=32 entropy=6
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
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3,:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database,
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/bt-btu  ( 3935): btu_task received preload complete event
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
D/bt-btm  ( 3935): btm_acl_device_down
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/bt-btm  ( 3935): btm_acl_reset_paging
,D/bt-btm  ( 3935): btm_acl_set_discing
I/wpa_supplicant( 3996): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb88f79f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 3996):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 3996): EAPOL: External notification - portValid=1
I/wpa_supplicant( 3996): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f42b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 3996):    broadcast key
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 3996): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3996): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3996): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3996): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,I/wpa_supplicant( 3996): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3996): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 3996): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 3996): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 3996): set send_ind_to_ndc = 0
I/wpa_supplicant( 3996): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3996): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3996): EAPOL: External notification - portValid=1
D/wpa_supplicant( 3996): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 3996): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 3996): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 3996): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3996): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 3996): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 3996): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3996): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 3996): EAPOL authentication completed successfully
I/wpa_supplicant( 3996): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 3996): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3996): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3996): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,I/bt-btm  ( 3935): btm_reset_complete
I/bt-btm  ( 3935): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/bt-btm  ( 3935): Start reading local supported commands
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/bt-btm  ( 3935): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3935): BTM reads next extended features page (1)
,I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/bt-btm  ( 3935): BTM reads next extended features page (2)
D/bt-btm  ( 3935): BTM reached last extended features page (2)
D/bt-btm  ( 3935): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
D/bt-btm  ( 3935): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3935): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3935): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3935): btm_read_ble_wl_size 
D/bt-btm  ( 3935): btm_read_white_list_size_complete 
D/bt-btm  ( 3935): btm_get_ble_buffer_size 
,D/WISPrService( 3291): >>>>>WISPrService start isConnected = false<<<<<
D/bt-btm  ( 3935): btm_read_ble_buf_size_complete 
D/bt-btm  ( 3935): btm_read_ble_local_supported_features 
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/bt-btm  ( 3935): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3935): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3935): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3935): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3935): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3935): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3935): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3935):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3935): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3935): BTM_SetInquiryMode
I/bt-btm  ( 3935): BTM_SetPageScanType
I/bt-btm  ( 3935): BTM_SetInquiryScanType
D/bt-btm  ( 3935): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3935): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3935): BTM_BleLoadLocalKeys
D/bt-btm  ( 3935): BTM_BleLoadLocalKeys
I/bt-btm  ( 3935): BTM_Sec: application registered
E/bt-btm  ( 3935): BTM_SecRegister:p_cb_info->p_le_callback == 0x61f24941 
I/bt-btm  ( 3935): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3935): SMP_Register state=0
E/bt-btm  ( 3935): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61f24941 
I/bt-btm  ( 3935): BTM_Sec: application registered
D/bt-btm  ( 3935): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3935): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3935): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3935): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3935): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3935): BTM_RegBusyLevelNotif
I/bt-att  ( 3935): GATT_Register
D/bt-att  ( 3935): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3935): allocated gatt_if=3
I/bt-att  ( 3935): GATT_StartIf gatt_if=3
D/bt-att  ( 3935): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3935): gatt_find_the_connected_bda found=0 found_idx=7
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1755/10178)
,D/WifiService(  905): New client listening to asynchronous messages
D/WISPrService( 3291): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btm  ( 3935): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3935): BTM_AllocateSCN
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3935): BTM_AllocateSCN
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btm  ( 3935): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3935):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3935):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3935):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3935):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3935):                : sec: 0x2090, service name [] (up to 21 chars saved)
E/bt-btif ( 3935): BTM_SEC_REG[5]: id 3
I/bt-btm  ( 3935): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3935):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3935):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3935):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3935): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3935): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
D/bt-avp  ( 3935): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3935): btif_storage_get_adapter_property7
E/bt-btif ( 3935): AVRC_AddRecord uuid: 110e
I/bt-avp  ( 3935): AVRC_AddRecord uuid: 110e
I/bt-btif ( 3935): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btm  ( 3935): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935):, BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3935):                : sec: 0x80, service name [] (up to 21 chars saved)
I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:2 len:6
D/bt-btm  ( 3935): BTM_GetHCIConnHandle
I/bt-btm  ( 3935): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3935): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3935): BTM_GetHCIConnHandle
I/bt-btm  ( 3935): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3935): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3935): BTM_GetHCIConnHandle
I/bt-btm  ( 3935): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3935): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3935): BTM_GetHCIConnHandle
I/bt-btm  ( 3935): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3935): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3935): BTM_GetHCIConnHandle
I/bt-btm  ( 3935): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3935): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3935): GATT_Register
D/bt-att  ( 3935): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3935): allocated gatt_if=4
I/bt-att  ( 3935): GATT_StartIf gatt_if=4
D/bt-att  ( 3935): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3935): gatt_find_the_connected_bda found=0 found_idx=7
D/BluetoothAdapterProperties( 3935): Address is:80:01:84:8A:B3:68
I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:1 len:14
I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3935): Scan Mode:20
I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3935): Discoverable Timeout:120
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:8 len:30
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/BluetoothAdapter( 3935): getBluetoothService(): entry
D/BluetoothAdapter( 3935): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3935): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41ace878
D/BluetoothDevice( 3935): getService : Register callback
D/BluetoothAdapterProperties( 3935): Adding bonded device:B4:CE:F6:AB:A4:6A
D/BluetoothAdapterProperties( 3935): Adding bonded device:08:EC:A9:50:76:27
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/BluetoothAdapterProperties( 3935): Adding bonded device:34:FC:EF:9D:93:0B
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/BluetoothAdapterProperties( 3935): Adding bonded device:7C:F9:0E:34:8A:A0
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
D/BluetoothAdapterProperties( 3935): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:3 len:48
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/bt-btif ( 3935): HAL bt_hal_cbacks->remote_device_properties_cb
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
E/BluetoothRemoteDevices( 3935): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3935): Remote class is:5898764
D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  905): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): WiFioffload: update mobile network = Unknown
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
I/bt-btif ( 3935): HAL bt_hal_cbacks->remote_device_properties_cb
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): Power_Mode_Type mode = 1
I/wpa_supplicant( 3996): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/PMS     (  905): acquireWL(42414e48): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422c1a90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422c1a90 target=com.android.internal.util.StateMachine$SmHandler }
E/BluetoothRemoteDevices( 3935): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3935): Remote class is:5898764
I/bt-btif ( 3935): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3935): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
D/BluetoothRemoteDevices( 3935): Remote class is:5898764
I/bt-btif ( 3935): HAL bt_hal_cbacks->remote_device_properties_cb
I/QuickSettingWifi( 1110): receive.wifiConnect:false wifiAPname:null elapse:1
E/BluetoothRemoteDevices( 3935): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BluetoothRemoteDevices( 3935): Remote class is:5898764
I/bt-btif ( 3935): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3935): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
D/BluetoothRemoteDevices( 3935): Remote class is:5898764
I/bt-btif ( 3935): BTA_JvEnable
I/bt-btm  ( 3935): BTM_ReadConnectability
I/bt-btm  ( 3935): BTM_ReadDiscoverability
I/bt-btm  ( 3935): BTM_SetDiscoverability
I/bt-btm  ( 3935): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
E/bt_mct  ( 3935): hci lib postload completed
D/bt-btm  ( 3935): br_edr_supported=0x2
I/bt-btm  ( 3935): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3935): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3935): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3935): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3935): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3935): BTM_SetConnectability
I/bt-btm  ( 3935): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3935): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3935): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3935): BTM_SetDiscoverability
I/bt-btm  ( 3935): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3935): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3935): br_edr_supported=0x0
I/bt-btm  ( 3935): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3935): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3935): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3935): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3935): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3935): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3935): BTM_SetConnectability
I/bt-btm  ( 3935): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3935): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3935): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3935): bta_pan_co_init
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3935): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3935):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3935):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3935): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3935):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3935): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3935):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btif ( 3935): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3935): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3935): ScanMode =  20
D/BluetoothAdapterProperties( 3935): State =  11
D/BluetoothAdapterProperties( 3935): Setting state to 12
I/BluetoothAdapterState( 3935): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3935): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=11 new=12
I/bt-btm  ( 3935): BTM_SetDiscoverability
I/bt-btif ( 3935): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 3935): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan(  905): onBluetoothStateChange(on) call bindService
D/bt-btm  ( 3935): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3935): br_edr_supported=0x0
I/bt-btm  ( 3935): mode == BTM_BLE_NON_DISCOVERABLE 
I/BluetoothAdapterState( 3935): Entering On State
I/bt-btm  ( 3935): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3935): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3935): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3935): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3935): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3935): BTM_SetConnectability
I/bt-btm  ( 3935): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/BluetoothHeadset( 1110): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3935): Scan Mode:21
I/bt-btm  ( 3935): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3935): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3935): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3935): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btif ( 3935): BTM_SetConnectability: mode 1 [NonConn-0
I/bt-btm  ( 3935): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/BluetoothAdapterProperties( 3935): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3935): Discoverable Timeout:120
D/BluetoothPan(  905): BluetoothPAN Proxy object connected
D/BluetoothAdapterService(1101562248)( 3935): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3935): getBondedDevices: length=5
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothA2dp(  905): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1110): Proxy object connected
I/QuickSettingMiniLite( 1110): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41d85620
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1221): Proxy object connected
D/BluetoothPhoneService( 1221): BluetoothHeadset onServiceConnected
W/BluetoothHeadset( 1221): Proxy not attached to service
D/BluetoothA2dp(  905): Proxy object connected
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=true
D/BluetoothAdapter(  905): 1111027240: getState(). Returning 12
D/BluetoothAdapterService(1101562248)( 3935): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3935): getBondedDevices: length=5
D/BluetoothHeadset( 1221): Proxy object connected
D/BluetoothHeadset(  905): onBluetoothStateChange: up=true
D/BluetoothHeadset(  905): Proxy object connected
D/BluetoothAdapter(  905): 1111027240: getState(). Returning 12
D/BluetoothManagerService(  905): Bluetooth State Change Intent: 11 -> 12
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/IntentController( 1110): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 3935): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3935): ***********state = 12
D/BluetoothMasReceiver( 3935): Bluetooth STATE CHANGED to 12
V/BluetoothSapReceiver( 3935): SapReceiver onReceive 
V/BluetoothSapReceiver( 3935): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3935):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3935): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 12
D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 12
V/BluetoothMasService( 3935): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3935): Manager Instance is not NULL
D/PMS     (  905): acquireWL(439c69d0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3291 1000 null
,D/HtcBtWidget_BTWidgetProvider( 3961): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3961): updateWidget(context) for widget: 
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424d00d0:true
D/EmailUtils( 3935): ============NULL aList========
,V/EmailUtils( 3935): <-getEmailAccountIdList
W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  905): releaseWL(439c69d0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  905): acquireWL(428bbcd0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3291 1000 null
V/BluetoothPbapService( 3935): Handler(): got msg=1
V/BluetoothPbapService( 3935): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3935): Pbap Service initSocket
V/BluetoothMasService( 3935): handleMessage: mIsEmailEnabledtrue
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtMns   ( 3935): BluetoothMns: isEmailEnabled: true
I/LocationAgent( 3291): new LocationAgent instance!!
D/BluetoothAdapter( 3935): getBluetoothService(): entry
W/BluetoothAdapter( 3935): getBluetoothService() called with no BluetoothManagerCallback
D/HtcTagManager( 3291): HtcTagManager construction complete
E/BluetoothServiceJni( 3935): SOCK FLAG = 1 ***********************
I/bt-btif ( 3935): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btif ( 3935): BTA_JvRfcommStartServer
I/bt-btm  ( 3935): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3935):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3935): Succeed to create listening socket 
V/BluetoothPbapService( 3935): Accepting socket connection...
D/BluetoothMasService( 3935): Map_prev 1
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3935): getBluetoothService(): entry
W/BluetoothAdapter( 3935): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
E/BluetoothServiceJni( 3935): SOCK FLAG = 3 ***********************
I/bt-btif ( 3935): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btif ( 3935): BTA_JvRfcommStartServer
I/bt-btm  ( 3935): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3935):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothInputDevice( 3291): BluetoothInputDevice()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 7
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
D/BluetoothInputDevice( 3291): BluetoothInputDevice(): Binding service...
D/BluetoothAdapter( 3935): getBluetoothService(): entry
W/BluetoothAdapter( 3935): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3935): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3935): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btif ( 3935): BTA_JvRfcommStartServer
,I/bt-btm  ( 3935): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3935):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3935): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3935): state: 12
,D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 12
D/BluetoothPan( 3291): BluetoothPan()
W/ContextImpl( 3935): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 8
V/BluetoothSapService( 3935): Starting SAP server process
,W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
,D/BluetoothPan( 3291): BluetoothPan(): Binding service...
,D/BluetoothMap( 3291): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): registerStateChangeCallback+
E/BluetoothMap( 3291): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 9
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothSap( 3291): BluetoothSap() call bindService
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 10
W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothAdapter( 1110): 1104262352: getState(). Returning 12
D/BluetoothAdapter( 1110): 1104262352: getState(). Returning 12
D/BluetoothPbap( 3291): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
I/QuickSettingBluetooth( 1110): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/BluetoothManagerService(  905): Registered receivers: 11
D/PhoneStatusBar( 1110): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
D/BluetoothPbap( 3291): BluetoothPbap(): Binding service...
D/BluetoothSapService( 3935): Sap_prev 1
,V/BluetoothSapService( 3935): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 3935): Sap Service initRfcommSocket
D/BluetoothA2dp( 3291): BluetoothA2dp()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 12
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
,D/BluetoothA2dp( 3291): BluetoothA2dp(): Binding service...
D/BluetoothAdapter( 3935): getBluetoothService(): entry
,W/BluetoothAdapter( 3935): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3935): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3935): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btif ( 3935): BTA_JvRfcommStartServer
I/bt-btm  ( 3935): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3935):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3935): Succeed to create listening socket 
,V/BluetoothSapService( 3935): Accepting socket connection...
,D/BluetoothHeadset( 3291): BluetoothHeadset()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
D/BluetoothHeadset( 3291): BluetoothHeadset(): Binding service...
,D/BluetoothManagerService(  905): Registered receivers: 13
,D/HtcTagManager( 3291): startProxy
,W/ContextImpl( 3291): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3291): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/DockEventReceiver( 3291): finishStartingService: stopping service
V/TAG     ( 3935): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3935): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41ac5100
D/BluetoothPan( 3291): BluetoothPAN Proxy object connected
D/PanProfile( 3291): Bluetooth service connected
D/BluetoothInputDevice( 3291): Proxy object connected
D/HidProfile( 3291): Bluetooth service connected
D/BluetoothAdapter( 1110): 1104262352: getState(). Returning 12
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4004): onCreate: going to find gatt base service first.
V/BluetoothPbapService( 3935): Pbap Service onBind
I/QuickSettingMiniLite( 1110): updateLiteState:no connect device!
D/BluetoothA2dp( 3291): Proxy object connected
D/A2dpProfile( 3291): Bluetooth service connected
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
D/BluetoothHeadset( 3291): Proxy object connected
D/HeadsetProfile( 3291): Bluetooth service connected
D/BluetoothAdapter( 3291): 1103142168: getState(). Returning 12
I/BluetoothFtpService( 3935): Ftp Service onCreate
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 12
D/SapServerProfile( 3291): Bluetooth service connected
D/BluetoothPbap( 3291): Proxy object connected
,D/PbapServerProfile( 3291): Bluetooth service connected
W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4231f620:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothAdapter( 3935): getBluetoothService(): entry
,W/BluetoothAdapter( 3935): getBluetoothService() called with no BluetoothManagerCallback
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothServiceJni( 3935): SOCK FLAG = 0 ***********************
I/bt-btif ( 3935): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btif ( 3935): BTA_JvRfcommStartServer
I/bt-btm  ( 3935): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 3935):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,I/BtOppRfcommListener( 3935): Accept thread started.
D/BluetoothMasReceiver( 3935): Bluetooth STATE CHANGED to 12
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  905): releaseWL(428bbcd0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothFtpService( 3935): Ftp_prev 1
D/[HTC_BLE][Constants]( 4004):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4004):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 4004):  + discoverServicesOnBonded = false
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3935): getBluetoothService(): entry
W/BluetoothAdapter( 3935): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3935): SOCK FLAG = 1 ***********************
I/bt-btif ( 3935): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3935): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3935): Write Extended Inquiry Response to controller
I/bt-btif ( 3935): BTA_JvRfcommStartServer
I/bt-btm  ( 3935): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3935):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3935): Run Accept thread
D/BluetoothAdapter( 3935): 1101580424: getState(). Returning 12
V/BluetoothMasService( 3935): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3935): Manager Instance is not NULL
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4004):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4004): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41a83228
D/[HTC_BLE][Constants]( 4004): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4004): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4004): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4004): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4004): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
D/[HTC_BLE][Constants]( 4004): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
D/EmailUtils( 3935): ============NULL aList========
V/EmailUtils( 3935): <-getEmailAccountIdList
D/BluetoothMasService( 3935): Map_prev 1
I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4004): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
D/HtcTagManager( 3291): onServiceConnected
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4004): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4004): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4004): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41a83228
D/HtcTagProfile( 3291): setup proxy
D/HtcPxpProfile( 3291): setup proxy
D/HtcFmpProfile( 3291): setup proxy
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4004): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41a83228
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4004): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41a83228, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41a8e210
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4004): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41a83228
,W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ee26c8:true
,I/LocationAgent( 3746): new LocationAgent instance!!
,D/HtcTagManager( 3746): HtcTagManager construction complete,
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/BluetoothInputDevice( 3746): BluetoothInputDevice()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 14
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/BluetoothInputDevice( 3746): BluetoothInputDevice(): Binding service...
,D/RingtoneManager( 4004): getExternalStorageState=mounted
,D/BluetoothPan( 3746): BluetoothPan()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  905): Registered receivers: 15
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/BluetoothPan( 3746): BluetoothPan(): Binding service...
D/wpa_supplicant( 3996): EAPOL: startWhen --> 0
,D/wpa_supplicant( 3996): EAPOL: disable timer tick
D/BluetoothMap( 3746): Create BluetoothMap proxy object
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[1]: Daisy
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[2]: Feverfew
E/BluetoothMap( 3746): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[3]: Foxglove,
D/BluetoothManagerService(  905): Registered receivers: 16
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[5]: Hangouts Message
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 17
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[6]: Lavender
D/BluetoothSap( 3746): BluetoothSap() call bindService
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[8]: Olive,
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[13]: Wintergreen
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + Available RingingTone[14]: Wisteria
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4004):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothPbap( 3746): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 18
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
D/BluetoothPbap( 3746): BluetoothPbap(): Binding service...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4004): BleProfilesStateMachine is initialized...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4004): Enter IdleState
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4004): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4004): initScanModeInterface: true
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4315db68:true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4004): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4004):  + mTag.getPrimaryDeviceList() = []
,D/BluetoothA2dp( 3746): BluetoothA2dp()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/[HTC_BLE][Constants]( 4004):  + defaultServices = 0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE][Constants]( 4004):  + enableOnBonded = false
D/BluetoothManagerService(  905): Registered receivers: 19
D/[HTC_BLE][Constants]( 4004):  + discoverServicesOnBonded = false
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/BluetoothA2dp( 3746): BluetoothA2dp(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4004): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41a8e210
,D/BluetoothHeadset( 3746): BluetoothHeadset()
,W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 20
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/BluetoothHeadset( 3746): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3746): startProxy
,W/ContextImpl( 3746): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3746): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
D/LocalBluetoothProfileManager( 3746): setBluetoothStateOn
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
D/HtcTagManager( 3746): startProxy
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
D/BluetoothAdapterService(1101562248)( 3935): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3935): getBondedDevices: length=5
D/BluetoothAdapter( 3746): getBluetoothService(): entry
D/BluetoothAdapter( 3746): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3746): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41ac39b8
D/BluetoothDevice( 3746): getService : Register callback
E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,D/BluetoothInputDevice( 3746): Proxy object connected
D/HidProfile( 3746): Bluetooth service connected
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/BluetoothPan( 3746): BluetoothPAN Proxy object connected
,D/PanProfile( 3746): Bluetooth service connected
D/SapServerProfile( 3746): Bluetooth service connected
D/BluetoothPbap( 3746): Proxy object connected
D/PbapServerProfile( 3746): Bluetooth service connected
,D/BluetoothA2dp( 3746): Proxy object connected
D/A2dpProfile( 3746): Bluetooth service connected
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/BluetoothHeadset( 3746): Proxy object connected
,D/HeadsetProfile( 3746): Bluetooth service connected
,D/BluetoothAdapter( 3746): 1101570752: getState(). Returning 12
,D/HtcTagManager( 3746): onServiceConnected
D/HtcTagProfile( 3746): setup proxy
D/HtcPxpProfile( 3746): setup proxy
,D/HtcFmpProfile( 3746): setup proxy
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/SensorManager(  905): mEventCount = 1350
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): Power_Mode_Type mode = 0
,I/wpa_supplicant( 3996): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  905): releaseWL(42414e48): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 3996): WiFi gateway: 0x101a8c0
D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -47, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19125 delay=15s
,D/WifiWatchdogStateMachine(  905): WAN detection
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1755/10178)
,D/WISPrService( 3291): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
,D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@42394a48
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
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
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,I/QuickSettingWifi( 1110): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(42f0d7c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42f0d7c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4203ce98
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4203ce98, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4219f4b8
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42054e30
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4117 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/CaptivePortalTracker(  905): NoActiveNetworkState
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/ConnectivityHelper( 1248): [onReceive] WIFI(1): CONNECTED
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =477e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1248/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1755/10178)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1488/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1773/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3795/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3404/10051)
D/PMS     (  905): acquireWL(4357d770): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3795/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43f3b410): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(437c9df8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4134 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  905): acquireWL(42bf41d0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 905 1000 WorkSource{10160}
,D/PMS     (  905): releaseWL(437c9df8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 128
D/libc    (  364): [NET]res_nsend:resplen=104
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  905): acquireWL(4360c588): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
D/PMS     (  905): releaseWL(43f3b410): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,I/IntentController( 1110): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1524): [EventService] EVENT_RESET_THEME_TIMESTAMP
,I/FeedActionBar( 1248): updateLastUpdatedTime(in String) LAST UPDATED 13:35
,D/DotMatrix( 1524): [EventService] isTheSameDay:false,timestamp is early than today:true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42480648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42480648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43eee3a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [1][0][0]
,D/GpsLocationProvider(  905): NTP server returned: 1449751016336 (Thu Dec 10 13:36:56 CET 2015) reference: 106426 certainty: 12 system time offset: -28
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME_FINISHED
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43eee3a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(4357d770): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(434ee6e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42bf41d0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  905): releaseWL(434ee6e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 372ms
D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
D/NfcService( 1232): applyRouting -2
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4342a188)
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=3876
D/PMS     (  905): acquireWL(433e1ab0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/PMS     (  905): releaseWL(433e1ab0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  905): wakingUp
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1110): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
D/PMS     (  905): acquireWL(435eb0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(435eb0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2529): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1232): applyRouting - 0
D/MtpService( 2529): [MTP][onReceive]-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/NfcService( 1232): applyRouting -2
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): acquireWL(430485c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): releaseWL(430485c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
,D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19126 delay=15s
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): SET_SCREEN_ON:On
I/wpa_supplicant( 3996): htc_wext_set_keepalive +
I/wpa_supplicant( 3996): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3996): getPrivFuncNum +	
I/wpa_supplicant( 3996): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3996): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3996): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3996): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3996): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/ClockThread( 1110): stop update clock
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-47 , oldRssi= -200
,I/MusicStore( 4117): Database version: 95
,V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1110): WifiActivity: 3
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3996): WiFioffload: SignalStrength: =97
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiNative-wlan0(  905):    returned true
W/ContextImpl( 4117): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED 3 -> 3
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/NetworkPolicy(  905): updateScreenOn: false
W/ContextImpl( 4117): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4117): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/DelayedSyncController( 4134): Delaying sync.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43690078): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43690078): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43af4b78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4360c588): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43602970): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1488 10028 null
D/PMS     (  905): releaseWL(43602970): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4004): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4004): onScreenOn: 1449751016730
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4004): onScreenOn: 1449751016730
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4219f4b8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4219f4b8, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42054e30
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  905): acquireWL(43875140): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
D/PMN     (  905): goingToSleep
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4117): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4117): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/PMS     (  905): releaseWL(43af4b78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): acquireWL(433ae468): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4117, uid=10154, userID:0
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19126 mDataStallAlarmIntent=PendingIntent{43f64e60: PendingIntentRecord{433f5690 android broadcastIntent}}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43669550): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43669550): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/DelayedSyncController( 4134): Delaying sync.
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3996): SET_SCREEN_ON:Off
I/wpa_supplicant( 3996): htc_wext_set_keepalive +
I/wpa_supplicant( 3996): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3996): getPrivFuncNum +	
I/wpa_supplicant( 3996): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3996): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3996): get_ip_address source addr = c0a80176
I/wpa_supplicant( 3996): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 3996): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  905):    returned true
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  905): acquireWL(43a925a8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4250df60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43875140): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  905): releaseWL(4250df60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ContactMessageStore( 1221): start background delete task...
D/ContactMessageStore( 1221): size: 0 , 0
,D/ContactMessageStore( 1221): Background delete complete
D/NetworkPolicy(  905): updateScreenOn: false
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,I/MediaRouter( 4117): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/MediaRouterService(  905): Client com.google.android.music (pid 4117): Registered
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/wpa_supplicant( 3996): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43a925a8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/NetworkMonitor( 4117): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4117/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2529/10021)
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4172 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] getTotalRam: 1873 Mb
,D/MediaRouter( 4117): getSelectedRoute
D/PMS     (  905): acquireWL(4335e2d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1488 10028 null
,D/PMS     (  905): releaseWL(4335e2d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4004): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4004): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4004): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4004): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4004): onScreenOff
,I/NetworkMonitor( 4117): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4117/10154)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4117, uid=10154, userID:0
,D/Process (  905): killProcessQuiet, pid=3609
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
,I/ActivityManager(  905): Killing 3609:com.google.android.gm/u0a107 (adj 15): empty #17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 4172): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4172): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4172): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/ActivityManager(  905): Recipient 3609
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4172): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4172): Preparing secondary program dexes.
,V/DexLibLoader( 4172): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4172): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4172): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4172): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4172): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4172): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4172): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4172): Dex already copied
D/OdexVerifier( 4172): Odex verification is skipped.
,V/DexLibLoader( 4172): Creating class loader
,V/DexLibLoader( 4172): Finished creating class loader
V/DexLibLoader( 4172): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4172): Dex already copied
D/OdexVerifier( 4172): Odex verification is skipped.
,V/DexLibLoader( 4172): Creating class loader
,V/DexLibLoader( 4172): Finished creating class loader
V/DexLibLoader( 4172): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4172): Dex already copied
D/OdexVerifier( 4172): Odex verification is skipped.
,V/DexLibLoader( 4172): Creating class loader
,V/DexLibLoader( 4172): Finished creating class loader
V/DexLibLoader( 4172): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4172): Dex already copied
D/OdexVerifier( 4172): Odex verification is skipped.
,V/DexLibLoader( 4172): Creating class loader
,V/DexLibLoader( 4172): Finished creating class loader
,V/DexLibLoader( 4172): Verifying classes from secondary dexes.
,D/DexLibLoader( 4172): DexLibLoader.ensureDexLoaded took 105 ms
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{4414f778 u0 com.test.thalitest/.MainActivity t2}
,W/dalvikvm( 4172): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4172): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4172): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4172): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4172): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4172): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4172): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/BTIF_CORE( 3935): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3935): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3935): Wake lock released
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fba4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,W/dalvikvm( 4172): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.59.123.86
,W/dalvikvm( 4172): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4172): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4172): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4172/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4172): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4172): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  905): Disable JIT of com.htc.bgp
,I/ActivityManager(  905): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4194 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  905): killProcessQuiet, pid=3761
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3761:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3761
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 4194): Created com.android.providers.calendar.CalendarAlarmManager@41aa9a18(com.android.providers.calendar.HtcCalendarProvider@41a91da0)
,D/CalendarProvider2( 4194): wait start:true
,W/fb4a(:<default>):UserScope( 4172): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/CalendarProvider2( 4194): wait end:false
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4172): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/PMS     (  905): acquireWL(43f51178): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1200 10028 null
,D/PMS     (  905): acquireWL(43f4f0d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1200 10028 null
,W/fb4a(:<default>):UserScope( 4172): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  905): releaseWL(43f51178): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/GCM     ( 1396): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
,D/PMS     (  905): releaseWL(43f4f0d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
,D/libc    ( 1396): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1396): [NET] getaddrinfo-,err=8
D/libc    ( 1396): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1396): [NET] getaddrinfo-, 1
,D/libc    ( 1396): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f170 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  905): acquireWL(43f065c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1396 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/AutoSetting( 1370): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4219 uid=10078 gids={50078, 3003, 5012}
,E/dalvikvm( 4172): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4172): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1370/10053)
E/dalvikvm( 4172): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4172): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4172): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4172): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4172): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4172): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4172): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4172): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4172): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
D/AutoSetting( 1370): service - onCreate()
W/dalvikvm( 4172): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4172): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4172): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4172): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4172): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4172): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4172): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/AutoSetting( 1370): service - AddressCache: using context: com.htc.Weather
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 181
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1396): [NET] getaddrinfo_proxy-, success
D/AutoSetting( 1370): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1370): service - onStartCommand() screen is off, don't request location
D/LocationManagerService(  905): request 42442500 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1370): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1370): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1370/10053)
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 9.914MB for 39954-byte allocation
,D/MobileConnectivityChangeReceiver( 4219): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4219): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4219): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4219): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 9.985MB for 79892-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4219/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4219/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4219/10078)
D/libc    ( 1396): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1396): [NET] getaddrinfo-,err=8
W/ActivityThread( 1396): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/PMS     (  905): acquireWL(43ebe7c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1200 10028 null
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4234 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
,D/PMS     (  905): acquireWL(43ea64c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 10.025MB for 84664-byte allocation
D/ContactMessageStore( 1221): notify MmsSms
D/AccFlag ( 1221): sense_version=6.0
,D/AccFlag ( 1221): sku_id=99
D/PMS     (  905): releaseWL(43ea64c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  905): acquireWL(43e9d8a8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1200 10028 null
D/PMS     (  905): releaseWL(43ebe7c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 1200): Preparing to send checkin request
,I/EventLogService( 1200): Accumulating logs since 1449749546258
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,W/GAV2    ( 4234): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4234): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4234): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4234): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4234): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/GCM     ( 1396): Connected
D/PMS     (  905): acquireWL(42541f90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1396 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
,D/PMS     (  905): releaseWL(43f065c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1396/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
W/EventLogAggregator( 1200): Unknown tag: install_package_attempt
W/EventLogAggregator( 1200): Unknown tag: snet
,W/EventLogAggregator( 1200): Unknown tag: snet_gcore
D/PMS     (  905): releaseWL(42541f90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(42084a18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1396 10028 null
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,D/GCM     ( 1396): Message class mpf
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1396/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1396/10028)
I/GoogleHttpClient( 1200): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1200): Using GMS GoogleHttpClient
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4172/10026)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42104090 u0 ReceiverList{422459b0 4172 com.facebook.katana/10026/u0 remote:422d5b48}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e8f058 u0 ReceiverList{43e8f738 4172 com.facebook.katana/10026/u0 remote:42307f80}}
D/PMS     (  905): acquireWL(43e692d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10028 null
D/PMS     (  905): releaseWL(42084a18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): releaseWL(43e692d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4172/10026)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4172/10026)
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [14][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4172/10026)
D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4234/10151)
,V/WebViewChromiumFactoryProvider( 4234): Binding Chromium to main looper Looper (main, tid 1) {41a720a8}
,I/LibraryLoader( 4234): Expected native library version number "",actual native library version number ""
,D/PMS     (  905): acquireWL(42384770): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1488 10028 null
I/chromium( 4234): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4234): Initializing chromium process, renderers=0
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1200/10028)
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1200/10028)
,D/PMS     (  905): releaseWL(42384770): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(42386818): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4234): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(420d5af0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(42386818): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4234): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4234): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4234): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4234): Local Branch: 
I/Adreno-EGL( 4234): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4234): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4234):                  aa63bbd948f41d15fc72f585e
,D/GCoreFlp( 1488): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(42f31e88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1488 10028 null
D/PMS     (  905): releaseWL(42f31e88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NSApplication( 4234): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4234/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4234/10151)
,W/GLSUser ( 1396): GoogleAccountDataService.getToken()
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1396): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3562/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3562/10160)
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Process (  905): killProcessQuiet, pid=3795
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3795:com.google.android.apps.docs/u0a100 (adj 15): empty #17
I/NotificationStore( 1396): System rebooted after Notification storage file was last written
,I/NotificationStore( 1396): Deleting the file
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1755/10178)
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=4282 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4172): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4172): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/CheckinRequestBuilder( 1200): awaiting user notification for token
D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/ContextImpl( 4172): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/DotMatrix( 1524): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/RemoteViews( 1110): com.google.android.gms (false,0)
,D/CalendarApplication( 4282): onCreate
,D/AlertReceiver( 4282): beginStartingService
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41d2d988 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/Process (  905): killProcessQuiet, pid=3817
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3817:com.htc.backup/1000 (adj 15): empty #17
,D/PMS     (  905): acquireWL(42bbda08): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4282 10013 null
,I/RemoteViews.Performance( 1110): com.google.android.gms 1 9 3 12
D/PMS     (  905): acquireWL(423b0598): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1200 10028 null
,I/ActivityManager(  905): Recipient 3817
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): releaseWL(423b0598): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4297 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 4282): start to updateAlertNotification!
I/ActivityManager(  905): Recipient 3795
,I/MultiDex( 4297): install
,I/MultiDex( 4297): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4297): loading existing secondary dex files
,I/MultiDex( 4297): load found 1 secondary dex files
,I/MultiDex( 4297): install done
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4313 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,D/AlertService( 4282): No fired or scheduled alerts
,I/ProviderInstaller( 4297): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/HtcAlertUtils( 4282): -- cancelReminderNotification --
,D/HtcAlertUtils( 4282): broadcastExistReminder!
,W/WeatherRequest( 1110): request cur loc, but there is no sys cur
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 4282): stopSelfResult true
D/PMS     (  905): releaseWL(42bbda08): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4328 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4313): can't get weather sync account
,W/WeatherRequest( 4313): request cur loc, but there is no sys cur
,W/Settings( 4313): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  905): acquireWL(42c6e410): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4328 10070 null
D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/PMS     (  905): acquireWL(42551ef0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4328 10070 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/TodoTaskshortcut( 4328): update TASK shortcut>
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42c6e410): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3996): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4343 uid=10090 gids={50090, 3003, 5012, 1028}
D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1248): com.htc.widget.weatherclock (true,33751552)
,I/TodoTaskNotifyService( 4328): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/RemoteViews.Performance( 1248): com.htc.widget.weatherclock 1 8 17
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 4328): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): releaseWL(42551ef0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/CalendarProvider2( 4194): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4194): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/NotifyReceiver( 4328): stopSelfResult true
,I/WorldClock.Global( 4343): isHtcDevice = true
,D/Process (  905): killProcessQuiet, pid=3782
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3782:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=3834
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3834:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3834
,W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.Global( 4343): isHtcDevice = true
I/ActivityManager(  905): Recipient 3782
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WorldClock.AlarmUtils( 4343): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 4343): Cancel any alarm from alarm manager
I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4357 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 4343): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1110): receive(android.intent.action.ALARM_CHANGED,1,false)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4297/10028)
,D/PMS     (  905): acquireWL(43f67620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422bc2b0: PendingIntentRecord{41c9b8b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=110091, Int=0
I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/TimeService( 4357): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751020026
D/PMS     (  905): releaseWL(43f67620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  905): killProcessQuiet, pid=3529
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3529:com.android.vending/u0a73 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=3920
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AutoSetting( 1370): receiver - intent: android.intent.action.USER_PRESENT
I/ActivityManager(  905): Killing 3920:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/AutoSetting( 1370): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3291): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3291): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3291): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3291): Cust_ConnectToPC   : spcsc>false
D/        ( 3291): Cust_ConnectToPC   : IPT>true
D/        ( 3291): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3291): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3291): hasRemovableStorageSlot: true
I/ActivityManager(  905): Recipient 3920
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SmartNS_Utility( 3291): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3291): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3291): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3291): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3291): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3291):  defaultType:0
W/ContextImpl( 3291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4375 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  905): Recipient 3529
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4375): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4375): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(43e958e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4375 1000 null
,D/SmartSyncUtils( 4375): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=4017
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): releaseWL(43e958e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  905): Killing 4017:com.htc.widget.process2/u0a48 (adj 15): empty #17
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Recipient 4017
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4375): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4375): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4375): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4375): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42054e30
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,D/GCM     ( 1396): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4297): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42054e30, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42054e30, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42054e30
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422a1b70 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422a1b70 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4395 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4395): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4395): MmsConfig.loadMmsSettings
E/dalvikvm( 4395): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4395): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4395): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4395): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4395): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4418 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4395, uid=10111, userID:0
,W/Settings( 4395): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4395, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4395, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4395, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4395, uid=10111, userID:0
,D/MessageFrequencyProvider( 4418): onCreate
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4395, uid=10111, userID:0
,D/MmsCustomizationProvider( 4418): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4418): GetPrviateResource
,V/GetPrviateResource( 4418): GetPrviateResource
,I/ProviderInstaller( 4395): Installed default security provider GmsCore_OpenSSL
,D/MmsCustomizationProvider( 4418): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
I/Babel   ( 4395): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4395): MmsConfig.loadFromDatabase
,E/Babel   ( 4395): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4395): MmsConfig.loadFromResources
,E/Babel   ( 4395): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4395): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4395/10111)
,D/Process (  905): killProcessQuiet, pid=3961
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 3961:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4395/10111)
,D/MessageCustFlag( 4418): sense_version=6.0
,D/BTAccessoryUtil( 4418): createReceiver
,D/BTAccessoryUtil( 4418): registerReceiver return intent = null
D/MessageCustFlag( 4418): sku_id=99
,W/SystemReader( 4418): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4418): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4418): networkCode: 
,D/MessageCustFlag( 4418): sku_id=99
D/MmsConfig( 4418): SIE smsPri: null
,D/MmsConfig( 4418): networkCode: 
D/HtcTelephonyCapability( 4418): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4418): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4418): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4418): Cannot find qct_8960_interface, use default value instead
,W/GLSUser ( 1396): GoogleAccountDataService.getToken()
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1396): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4395): UserRecoverableAuthException.
,E/Babel   ( 4395): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4395): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4395): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4395): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4395): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4395): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4395): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4395): Error getting auth token
,E/Babel   ( 4395): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4395): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4395): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4395): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4395): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4395): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4395): Account registration failedRedacted-21
E/Babel   ( 4395): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4395): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4395): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4395): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4395): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4395): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4395): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4395): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4395/10111)
,I/ActivityManager(  905): Recipient 3961
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3980
,I/ActivityManager(  905): Killing 3980:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1396): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/GLSUser ( 1396): GoogleAccountDataService.getToken()
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4297): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4297): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4297):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Recipient 3980
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Resuming delayed broadcast
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1396): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
D/PMS     (  905): acquireWL(424c7c48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4328 10070 null
,D/PMS     (  905): acquireWL(4235a0b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4328 10070 null
W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  905): acquireWL(42214890): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4328 10070 null
,D/PMS     (  905): releaseWL(424c7c48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.notification.NotifyReceiver
,E/TodoTaskNotifyService( 4328): java.lang.NullPointerException
W/System.err( 4328): java.lang.NullPointerException
W/System.err( 4328): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4328): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4328): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 4328): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4328): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4328): stopSelfResult false
E/TodoTaskNotifyService( 4328): java.lang.NullPointerException
W/System.err( 4328): java.lang.NullPointerException
W/System.err( 4328): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4328): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4328): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4328): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4328): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4328): mStartingService is null
D/PMS     (  905): acquireWL(4235a0b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4328 10070 null
D/PMS     (  905): releaseWL(42214890): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): releaseWL(4235a0b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
W/NotifyReceiver( 4328): stopSelfResult true
D/ProviderChangeReceiver( 4282): ---------------------------------------------------
D/ProviderChangeReceiver( 4282): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 4282): start to updateAlertNotification!
,E/Babel   ( 4395): Unexpected exception while authenticating.
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,E/Babel   ( 4395): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4395): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4395): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4395): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4395): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4395): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4395): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4395): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4395): 	at java.lang.Thread.run(Thread.java:864)
D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1524): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/AlertService( 4282): No fired or scheduled alerts
,D/HtcAlertUtils( 4282): -- cancelReminderNotification --
D/HtcAlertUtils( 4282): broadcastExistReminder!
,I/RemoteViews( 1110): com.google.android.gms (false,0)
,I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41d91150 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.google.android.gms 2 11 4 12
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4449 uid=10038 gids={50038}
,D/Process (  905): killProcessQuiet, pid=3404
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/CheckinTask( 1200): Sending checkin request (8963 bytes)
I/ActivityManager(  905): Killing 3404:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3404
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityThread( 1200): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4462 uid=10077 gids={50077}
,D/Process (  905): killProcessQuiet, pid=4117
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4117:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/libc    ( 1200): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1200): [NET] getaddrinfo-,err=8
D/libc    ( 1200): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1200): [NET] getaddrinfo-, 1
,D/libc    ( 1200): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e030 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
I/ActivityManager(  905): Recipient 4117
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 4117): Died!
,D/SMSBackup( 4462): Got a database change event
,D/Process (  905): killProcessQuiet, pid=4172
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  905): Killing 4172:com.facebook.katana/u0a26 (adj 15): empty #17
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 20
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1200): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1200): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1200): [NET] getaddrinfo-,err=8
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4172
,D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(4210a7a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1488 10028 null
,D/PMS     (  905): acquireWL(41c91af8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1488 10028 null
,D/PMS     (  905): releaseWL(4210a7a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(41c91af8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/jxcore-log( 3876): Test app app.js loaded
I/jxcore-log( 3876): 
,I/Choreographer( 3876): Skipped 543 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 3876): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3876): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a7e3c0 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 3876): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  905): releaseWL(433ae468): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  905): acquireWL(42c06df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10028 null
,D/PMS     (  905): releaseWL(42c06df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1200/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3996): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1200/10028)
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3996): nl80211: survey data missing!
E/wpa_supplicant( 3996): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3996): environment dirty rate=11 [18][2][0]
,W/GLSUser ( 1396): GoogleAccountDataService.getToken()
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1396): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1524): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1110): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1200): awaiting user notification for token
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41e42e88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.google.android.gms 2 8 3 12
,I/CheckinTask( 1200): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1200): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/GCM     ( 1396): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  905): releaseWL(43e9d8a8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1200): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c00368 that was originally bound here
E/ActivityThread( 1200): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c00368 that was originally bound here
E/ActivityThread( 1200): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1200): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1200): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1200): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1200): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1200): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1200): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1200): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1200): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1200): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1200): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1200): 	at bks.a(SourceFile:298)
E/ActivityThread( 1200): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1200): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1200): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1396): GCM config loaded
,D/PMS     (  905): releaseWL(420d5af0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/Messaging( 4418): mNeedToUpdateDate2 start
,D/MmsConfig( 4418): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4418): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4418): 
D/MmsAsyncWorkHandler( 4418): HM tk = 20001
,D/ReportIndicatorCache( 4418): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4418): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a798c8
,I/Messaging( 4418): mccmnc> 
D/DraftCache( 4418): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4418): [DraftCache/1] refresh
,D/MmsConfig( 4418): networkCode: 
D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/MmsSmsV2Provider( 1221):  phoneType = -1
D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4418): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1221):  phoneType = -1
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4418): sense_version=6.0
,D/Jerry   ( 4418): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4418): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4418): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4418): createReceiver
D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1221):  phoneType = -1
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 4418): mNeedToUpdateDate2: false
D/TelephUtils( 1221): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
V/MmsProvider( 1221): Update uri=content://mms, match=0
,V/MmsProvider( 1221): selection=st=129 AND m_type!=134
,D/Messaging( 4418): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4418): TransactionService is going to be woken up.
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1221): sku_id=99
,V/TransactionService( 4418): 1-Creating TransactionService
,D/DraftCache( 4418): [DraftCache/463] rebuildCache
D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/MmsSmsV2Provider( 1221):  phoneType = -1
,V/TransactionService( 4418): onStartCommand: 1
,D/MmsSystemEventReceiver( 4418): unRegisterForConnectionStateChanges
V/TransactionService( 4418): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4418): Loading previous transactions.
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1221):  phoneType = -1
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/Messaging( 4418): ViewCache CreatePreload
,D/Messaging( 4418): ViewCache CreatePreloadOnlyMultipleOpsList
,D/AccFlag ( 1221): device_type: 1
,D/TransactionService( 4418): Force set service start id to 1
,D/Cust_MMSMS( 4418): _has_set_default_values_2=true
V/TransactionService( 4418): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/Messaging( 4418): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MmsSystemEventReceiver( 4418): unRegisterForConnectionStateChanges
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/Jerry   ( 1221): URI_DRAFT
,D/TransactionService( 4418): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4418): Destroying TransactionService
,V/TransactionService( 4418): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/DraftCache( 4418): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4418): [DraftCache/463] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4418): 
D/MmsAsyncWorkHandler( 4418): HM tk = 20002
D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1221): sku_id=99
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,D/AccFlag ( 1221): sku_id=99
,D/MsgPreferenceUtils( 4418): def_index: 0
,D/MsgPreferenceUtils( 4418): globalIndex = 1
D/MsgPreferenceUtils( 4418): phone state: true
D/MsgPreferenceUtils( 4418): sd state: false
,D/MsgPreferenceUtils( 4418): vIndex = 0
,I/GAV2    ( 4234): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4395, uid=10111, userID:0
,D/Process (  905): killProcessQuiet, pid=4219
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4219:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4219
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4134
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4134:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4134
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/AutoSetting( 1370): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1370): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1370): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43f63040 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1248): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,D/PackageBroadcastService( 1200): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/Launcher( 1248): Deferring update until onResume
,D/Launcher( 1248): waitUntilResume // bindAppsUpdated
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PeopleContactsSync( 1200): CP2 sync disabled
I/[PluginManager]RegisterService( 1370): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 1370): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1200, uid=10028, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4508 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/PMS     (  905): acquireWL(434b82f8): PARTIAL_WAKE_LOCK  Icing 0x1 1200 10028 null
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,D/PMS     (  905): releaseWL(434b82f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4508, uid=10073, userID:0
,D/Finsky  ( 4508): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4508/10073)
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4508/10073)
,D/Finsky  ( 4508): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4508): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4508): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4508, uid=10073, userID:0
,W/PackageManager(  905): Unable to load service info ResolveInfo{438887c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/Finsky  ( 4508): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4508): [1] 2.run: Finished loading 1 libraries.
,D/Process (  905): killProcessQuiet, pid=4234
,I/ActivityManager(  905): Killing 4234:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/IcingCorporaProvider( 2661): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,D/Finsky  ( 4508): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PMS     (  905): acquireWL(43f496f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3562 10160 null
D/PMS     (  905): releaseWL(43f496f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4508): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm-heap( 3562): Grow heap (frag case) to 13.528MB for 1821008-byte allocation
,I/IcingCorporaProvider( 2661): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 
,I/ActivityManager(  905): Recipient 4234
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41afeed0 +
,I/Prism.WidgetManager( 1248): onLoadItems() +
,D/PMS     (  905): acquireWL(428d8c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
,V/AlarmManager(  905): sending alarm PendingIntent{4350c618: PendingIntentRecord{425ec260 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449751037360, Int=0
,D/PMS     (  905): releaseWL(428d8c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1396): GoogleAccountDataService.getToken()
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1396): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1396): GoogleAccountDataService.getToken()
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1396): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4508): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4508): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/asset   ( 1248): Copying FileAsset 0x66913988 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1248): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1248): onLoadItems() -
,I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41afeed0 -
,W/GLSUser ( 1396): GoogleAccountDataService.getToken()
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1396): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1396): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4508): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4508): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4508): [1] DailyHygiene.reschedule: Scheduling new run in 93 minutes (failures=3)
,D/PhoneApp( 1221): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1221): -- N1 =0
,D/PhoneApp( 1221): -- N2 =0
,D/PhoneApp( 1221): -- N3 =0
,D/PMS     (  905): acquireWL(420613b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(420613b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(424fd858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5eee0: PendingIntentRecord{423f3c90 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=136403, Int=0
,D/PMS     (  905): acquireWL(42349ec8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(424fd858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(421b4a88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42349ec8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(421b4a88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1370): service - mHandler: update timezone
,D/AutoSetting( 4194): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4194): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4194): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4194): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4194): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4194): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4194): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4194): service - mHandler: update timezone
,D/AutoSetting( 4194): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4194): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4194): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4194): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1524): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1110): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41e5b978 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.htclocationservice 3 10 3 11
,D/AutoSetting( 1370): service - handleMessage() stop self
,D/AutoSetting( 1370): service - handleMessage() quit looper
,D/AutoSetting( 1370): service - onDestroy() END
,D/PMS     (  905): acquireWL(4208e1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{42095c08: PendingIntentRecord{4234e038 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136968, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1396/10028)
,V/AlarmManager(  905): sending alarm PendingIntent{4209ac68: PendingIntentRecord{42433500 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140534, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{422e0cd0: PendingIntentRecord{422e1310 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449751052522, Int=0
,D/PMS     (  905): acquireWL(43fb3d18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10028 null
,D/PMS     (  905): releaseWL(43fb3d18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC <<
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(43166930): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(4208e1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8d23 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/Finsky  ( 4508): [1] 5.onFinished: Installation state replication succeeded.
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): releaseWL(43166930): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{41ea4f00 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(43f237c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PMS     (  905): releaseWL(43f237c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4194): service - handleMessage() stop self
,D/AutoSetting( 4194): service - onDestroy() END
,D/AutoSetting( 4194): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4313
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4313:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4313
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(434cd8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422bc2b0: PendingIntentRecord{41c9b8b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=170091, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(434cd8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1221): switchBindHtcMsgCursor: null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1200/10028)
,D/Process (  905): killProcessQuiet, pid=4343
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4343:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4343
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4391e068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4391e068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42609688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42609688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(434e95f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422bc2b0: PendingIntentRecord{41c9b8b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=230091, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(434e95f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43515708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43515708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43f56338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5eee0: PendingIntentRecord{423f3c90 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=254093, Int=0
,D/PMS     (  905): acquireWL(4249bd00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(43f56338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42ebf5c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4249bd00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(42ebf5c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43f68d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43f68d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43eca0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422bc2b0: PendingIntentRecord{41c9b8b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=290090, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43eca0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4369a0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4369a0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true

```
