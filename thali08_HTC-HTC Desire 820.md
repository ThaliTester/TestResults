#### Test 50650278b28a87a_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  909): mEventCount = 1200
,E/cutils-trace( 3861): Error opening trace file: No such file or directory (2)
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
D/CustomizationManager( 3861):  Read CID file spent 0.088 (s)
D/CustomizationManager( 3861):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 3861): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3861): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3861): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3861): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3861
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1126175696
D/PMS     (  909): acquireHCC(436a59c8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(4369e798): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bf0130
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
D/PMS     (  909): acquireWL(43686770): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3872 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1250): [trimMemory] 20
W/asset   ( 3872): Copying FileAsset 0x5c7bf688 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3872): Binding Chromium to main looper Looper (main, tid 1) {41b39200}
I/LibraryLoader( 3872): Expected native library version number "",actual native library version number ""
I/chromium( 3872): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3872): Initializing chromium process, renderers=0
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@435ebc88:true
D/BluetoothAdapter( 3872): 1102375992: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  909): acquireWL(435e0ca8): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  909): acquireWL(435caf20): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  909): releaseWL(435caf20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3872): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3872): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3872): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3872): Local Branch: 
I/Adreno-EGL( 3872): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3872): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3872):                  aa63bbd948f41d15fc72f585e
W/chromium( 3872): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3872): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3872): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3872): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3872): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3872): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3872): CordovaWebView is running on device made by: HTC
,W/AwContents( 3872): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Disable input method client, pid=1250
,W/ResourceType( 3872): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3872): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b801c0, mServedView=org.apache.cordova.engine.SystemWebView{41b45f50 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1184): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1184): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  909): Enable input method client, pid=3872
,W/AwContents( 3872): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +424ms
,D/PMS     (  909): releaseWL(43686770): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3872): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3872): JniHelper::setJavaVM(0x4160e048), pthread_self() = 1663235416
,D/JX-Cordova( 3872): jxcore cordova android initializing
,W/dalvikvm( 3872): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 11.511MB for 64402-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 11.631MB for 144892-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 11.747MB for 217334-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 11.922MB for 325996-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 12.197MB for 488990-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 12.603MB for 733480-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 14.050MB for 1650320-byte allocation
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 15.462MB for 2475476-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(436a59c8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(4369e798): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 17.477MB for 3713210-byte allocation
,W/jxcore-log( 3872): Initializing JXcore engine
,W/jxcore-log( 3872): JXcore engine is ready
,W/jxcore-log( 3872): Starting JXcore engine
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3916 uid=10077 gids={50077}
D/PMS     (  909): acquireWL(43647730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10077}
V/AlarmManager(  909): sending alarm PendingIntent{4237d340: PendingIntentRecord{42332768 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449671227473, Int=60000
,D/PMS     (  909): releaseWL(43647730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3916): SMSBackupAgentService started
,D/SMSBackup( 3916): Checking restore status
,D/SMSBackup( 3916): Restore complete
,D/SMSBackup( 3916): cancelCheckAlarm
,D/SMSBackup( 3916): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  909): killProcessQuiet, pid=1476
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 1476:com.htc.bgp/u0a14 (adj 15): empty #17
,W/jxcore-log( 3872): Platform android
W/jxcore-log( 3872): 
,W/jxcore-log( 3872): Process ARCH arm
W/jxcore-log( 3872): 
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 1476
,I/jxcore-log( 3872): JXcore Cordova bridge is ready!
I/jxcore-log( 3872): 
,W/jxcore-log( 3872): JXcore engine is started
,I/chromium( 3872): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  909): releaseWL(435e0ca8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3872): Toggling radios to true
I/jxcore-log( 3872): 
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  909): checking for enable restriction...
,D/BluetoothManagerService(  909): checkBTEasState, ret=true
,I/BluetoothManagerService(  909): isBluetoothRestricted(): false
D/BluetoothManagerService(  909): enable(): region ID = 6
D/BluetoothManagerService(  909): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  909): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 1
,W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1448
,W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
,W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  909): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
,W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
,W/Settings:Agent(  909): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  909): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  909): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3872): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1246
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
,W/Settings:Agent(  909): << traceCallingStack(): 1(ms)
D/WifiService(  909): New client listening to asynchronous messages
D/WifiService(  909): setWifiEnabled: true pid=3872, uid=10348
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiManager( 3872): disconnect: Base Package Name=com.test.thalitest, uid=10348
I/ActivityManager(  909): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3931 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/PMS     (  909): acquireWL(42dc9f58): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiManager( 3872): reconnect: Base Package Name=com.test.thalitest, uid=10348
I/jxcore-log( 3872): Radios toggled
I/jxcore-log( 3872): 
D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3872): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 3872): 
I/jxcore-log( 3872): Perf Test app loaded loaded
I/jxcore-log( 3872): 
I/jxcore-log( 3872): check test folder
I/jxcore-log( 3872): 
I/jxcore-log( 3872): found test : ./testFindPeers.js
I/jxcore-log( 3872): 
,I/jxcore-log( 3872): found test : ./testSendData.js
I/jxcore-log( 3872): 
,D/AdapterServiceConfig( 3931): Adding HeadsetService
D/AdapterServiceConfig( 3931): Adding A2dpService
D/AdapterServiceConfig( 3931): Adding HidService
D/AdapterServiceConfig( 3931): Adding HealthService
D/AdapterServiceConfig( 3931): Adding PanService
,D/AdapterServiceConfig( 3931): Adding GattService
,W/linker  ( 3931): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3931): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  909): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42459e70:true
,W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3931): make
,I/BluetoothAdapterState( 3931): Entering OffState
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3931): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  909): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  909): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  909): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  909): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  909): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapter( 1220): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bfc110
,D/BluetoothAdapter( 1220): onBluetoothServiceUp done
D/BluetoothAdapter( 3931): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b52a18
D/BluetoothAdapter( 3931): onBluetoothServiceUp done
D/BluetoothAdapter(  909): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42453c88
,D/BluetoothAdapter(  909): onBluetoothServiceUp done
D/BluetoothAdapter( 1109): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f92fa0
,D/BluetoothAdapter( 1109): onBluetoothServiceUp done
,D/BluetoothAdapter( 1231): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c724a0
,D/BluetoothAdapter( 1231): onBluetoothServiceUp done
,D/BluetoothAdapter( 1390): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41db4938
,D/BluetoothAdapter( 1390): onBluetoothServiceUp done
D/BluetoothAdapter( 1755): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@421534d0
,D/BluetoothAdapter( 1755): onBluetoothServiceUp done
,D/BluetoothAdapter( 3872): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42695ff8
D/BluetoothAdapter( 3872): onBluetoothServiceUp done
,D/BluetoothManagerService(  909): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3931): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3931): Setting state to 11
I/BluetoothAdapterState( 3931): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3931): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  909): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  909): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothBondStateMachine( 3931): make
D/BluetoothManagerService(  909): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  909): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3931): StableState(): Entering Off State
,I/IntentController( 1109): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/HeadsetService( 3931): Received start request. Starting profile...
D/HeadsetStateMachine( 3931): Version 1.6
,D/HeadsetStateMachine( 3931): make
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3957 uid=10037 gids={50037, 3002, 3001}
,I/BluetoothAdapterState( 3931): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 3931): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3931): Received start request. Starting profile...
V/Avrcp   ( 3931): make
,D/Avrcp   ( 3931): fillIntentFilter()
D/A2dpStateMachine( 3931): make
,I/Choreographer( 3872): Skipped 92 frames!  The application may be doing too much work on its main thread.
,D/A2dpStateMachine( 3931): Enter Disconnected: -2
,D/HtcBtWidget_BTWidgetProvider( 3957): onBTStateChanged() for widget: 
,D/HidService( 3931): Received start request. Starting profile...
,D/HtcBtWidget_BTWidgetProvider( 3957): updateWidget(context) for widget: 
,I/QuickSettingBluetooth( 1109): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/Process (  909): killProcessQuiet, pid=3174
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  909): Killing 3174:com.android.defcontainer/u0a19 (adj 15): empty #17
D/HealthService( 3931): Received start request. Starting profile...
I/chromium( 3872): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PanService( 3931): Received start request. Starting profile...
D/BluetoothTethering(  909): supplyMessenger
D/BluetoothTethering(  909): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  909): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  909): got CMD_CHANNEL_HALF_CONNECTED
D/PanService( 3931): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BtGatt.DebugUtils( 3931): handleDebugAction() action=null
D/BtGatt.GattService( 3931): Received start request. Starting profile...
D/BtGatt.GattService( 3931): start()
V/BluetoothPbapService( 3931): Pbap Service onCreate
V/BluetoothPbapService( 3931): Starting PBAP service
D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 11
D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 11
E/BluetoothMasService( 3931): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3931): Add permission for SmsProvider.
V/BluetoothMasService( 3931): Starting MAS instances
D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 11
I/MailMessageReceiver( 3931): reg:com.android.bluetooth.btservice.AdapterApp@41b45f80 with com.htc.util.mail.MailMessageReceiver@41b85dc0
I/MailManager( 3931): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b85dc0
V/EmailUtils( 3931): Manager Instance is not NULL
,I/ActivityManager(  909): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3975 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
D/Tethering(  909): interfaceAdded wlan0
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/Tethering(  909): wlan0 is not a tetherable iface, ignoring
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/Tethering(  909): interfaceAdded p2p0
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/Tethering(  909): p2p0 is not a tetherable iface, ignoring
D/Tethering(  909): interfaceLinkStateChanged p2p0, false
,D/Tethering(  909): interfaceStatusChanged p2p0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/PMS     (  909): releaseWL(42dc9f58): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  909): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3174
,D/EmailUtils( 3931): ============NULL aList========
,V/EmailUtils( 3931): <-getEmailAccountIdList
,V/BluetoothMasService( 3931): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 11
V/BluetoothMasService( 3931): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3931): Manager Instance is not NULL
D/EmailUtils( 3931): ============NULL aList========
,V/EmailUtils( 3931): <-getEmailAccountIdList
V/BluetoothSapService( 3931): Sap Service onCreate
,V/BluetoothSapService( 3931): initBinder
V/BluetoothSapService( 3931): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b8b5f0
,V/BluetoothSapReceiver( 3931): BluetoothSapReceiver init
,D/BluetoothSapService( 3931): setSapService()
V/BluetoothSapService( 3931): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3931): state: 12
,D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 11
D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3931): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 3931): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3931): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  909): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  909): killProcessQuiet, pid=3711
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  909): Killing 3711:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/BluetoothMasReceiver( 3931): Bluetooth STATE CHANGED to 11
,I/ActivityManager(  909): Recipient 3711
D/WifiService(  909): Client connection lost with reason: 4
,I/qcom-bluetooth( 3993): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3994 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiMonitor(  909): startMonitoring(wlan0) with mConnected = false
,I/IntentController( 1109): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  909): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1109): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/qcom-bluetooth( 4013): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4014): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/wpa_supplicant( 4012): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4012): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4012): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4012): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4012): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4012): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4012): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4012): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4012): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4012): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4012): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4012): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4012): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4012): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4012): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4012): update_config=1
D/wpa_supplicant( 4012): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4012): device_name='Android_63cc'
D/wpa_supplicant( 4012): manufacturer='HTC'
D/wpa_supplicant( 4012): model_name='HTC_PHONE'
D/wpa_supplicant( 4012): model_number='1234'
D/wpa_supplicant( 4012): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4012): p2p_oper_reg_class=126
D/wpa_supplicant( 4012): p2p_oper_channel=36
D/wpa_supplicant( 4012): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4012): persistent_reconnect=1
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4012): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4012): nl80211: RFKILL status not available
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4012): nl80211: Using driver-based roaming
D/wpa_supplicant( 4012): nl80211: TDLS supported
D/wpa_supplicant( 4012): nl80211: TDLS external setup
D/wpa_supplicant( 4012): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4012): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4012): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4012): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4012): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4012): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4012): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4012): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7bd7758
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Re,gister frame type=0xd0 nl_handle=0xb7bd7758
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4012): htc_wext_command_init +
E/wpa_supplicant( 4012): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4012): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4012): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 95
D/Tethering(  909): interfaceLinkStateChanged p2p0, false
D/Tethering(  909): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4012): nl80211: Regulatory information - country=00
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 4012): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4012): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4012): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4012): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 5735-5835 @ 80 MHz
,D/wpa_supplicant( 4012): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4012): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  909): interfaceLinkStateChanged p2p0, false
D/Tethering(  909): interfaceStatusChanged p2p0, false
,I/qcom-bluetooth( 4016): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3994): Received state change = 11,
,I/qcom-bluetooth( 4017): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 4018): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4019): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/QuickSettingWifi( 1109): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,I/ActivityManager(  909): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4022 uid=10048 gids={50048}
,D/WifiService(  909): New client listening to asynchronous messages,
,D/Process (  909): killProcessQuiet, pid=3365
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3365:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/HtcWiFiWidget_WiFiWidgetProvider( 4022): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4022): updateWidget(context) for widget: 
,D/Process (  909): killProcessQuiet, pid=3736
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  909): Killing 3736:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3736
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 4012): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4012):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4012):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4012):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4012): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4012): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4012): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4012): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4012): nl80211: Flush PMKIDs
E/wpa_supplicant( 4012): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4012): State: DISCONNECTED -> INACTIVE
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3365
,D/wpa_supplicant( 4012): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4012): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4012): WPS: Set UUID for interface p2p0
,I/qcom-bluetooth( 4035): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
D/wpa_supplicant( 4012): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4012): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4012): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): Using existing control interface directory.
D/wpa_supplicant( 4012): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4012): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4012): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4012): P2P: Own listen channel: 11
D/wpa_supplicant( 4012): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4012): P2P: Add operating class 81
,I/qcom-bluetooth( 4036): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
I/wpa_supplicant( 4012): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4012): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4012): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4012): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4012): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4012): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4012): disable_scan_offload=1
D/wpa_supplicant( 4012): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4012): update_config=1
D/wpa_supplicant( 4012): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4012): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4012): manufacturer='HTC'
D/wpa_supplicant( 4012): model_name='HTC Desire 820'
D/wpa_supplicant( 4012): model_number='HTC Desire 820'
D/wpa_supplicant( 4012): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4012): persistent_reconnect=1
D/wpa_supplicant( 4012): p2p_disabled=1
D/wpa_supplicant( 4012): hs20=1
D/wpa_supplicant( 4012): interworking=1
D/wpa_supplicant( 4012): Line: 18 - start of a new network block
D/wpa_supplicant( 4012): key_mgmt: 0x2
D/wpa_supplicant( 4012): priority=1 (0x1)
,D/wpa_supplicant( 4012): signinfail=0 (0x0)
,I/bt-btu  ( 3931): btu_task pending for preload complete event
,D/wpa_supplicant( 4012): Priority group 1
D/wpa_supplicant( 4012):    id=0 ssid='NG700'
I/wpa_supplicant( 4012): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4012): nl80211: RFKILL status not available
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4012): nl80211: Using driver-based roaming
D/wpa_supplicant( 4012): nl80211: TDLS supported
D/wpa_supplicant( 4012): nl80211: TDLS external setup
D/wpa_supplicant( 4012): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4012): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4012): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4012): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4012): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4012): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4012): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4012): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7be7718
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4012): htc_wext_command_init +
I/wpa_supplicant( 4012): htc_wext_command_init -
I/wpa_supplicant( 4012): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4012): Don't set 00 to countryID.conf
D/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4012): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4012): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4012): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4012): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4012): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4012): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4012): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4012): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false,
,I/wpa_supplicant( 4012): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4012):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4012):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4012):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4012): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4012): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4012): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4012): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4012): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4012): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4012): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4012): TDLS: Driver uses external link setup
D/wpa_supplicant( 4012): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4012): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4012): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4012): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4012): Using existing control interface directory.
,I/wpa_supplicant( 4012): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4012): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4012): Auto country group 1: ch36
I/wpa_supplicant( 4012): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4012): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4012): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4012): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4012): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4012): Get randomness: len=20 entropy=0
V/RegulatoryObserver(  909): uevent:
V/RegulatoryObserver(  909): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4421, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  909): Regulatory Country Code:DE
V/RegulatoryObserver(  909): Start wifi-crda service to run crda.
V/RegulatoryObserver(  909): Country Code is DE
V/RegulatoryObserver(  909): Send broadcast country code message.
,I/RegulatoryObserver(  909): Broadcast intent for crda country code: DE
,D/wpa_supplicant( 4012): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4012): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_909-2
D/wpa_supplicant( 4012): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4012): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4012): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4012): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4012): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4012): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4012): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4012): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4012): nl80211: Event message available
D/wpa_supplicant( 4012): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4012): nl80211: Regulatory domain change
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 95
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4012): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4012): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4012): nl80211: 5150-5250 @ 80 MHz,
D/wpa_supplicant( 4012): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4012): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4012): P2P: Add operating class 81
,D/wpa_supplicant( 4012): P2P: Add operating class 115
D/wpa_supplicant( 4012): P2P: Add operating class 116
D/wpa_supplicant( 4012): P2P: Add operating class 117,
D/wpa_supplicant( 4012): P2P: Update channel list
D/wpa_supplicant( 4012): p2p0: Updating hw mode
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4012): nl80211: Regulatory information - country=DE
,D/wpa_supplicant( 4012): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4012): nl80211: 5150-5250 @ 80 MHz,
D/wpa_supplicant( 4012): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4012): nl80211: 5470-5725 @ 80 MHz,
D/wpa_supplicant( 4012): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4012): nl80211: Added 802.11b mode based on 802.11g information,
D/WifiNative-wlan0(  909): doBoolean: SET_WIFI_ON 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
,I/wpa_supplicant( 4012): set wifi ON
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doString: DRIVER MACADDR
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  909): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1109): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  909): Loading config and enabling all networks
D/WifiNative-wlan0(  909): doString: LIST_NETWORKS
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/WIFI_ICON( 1109): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): list_network_info: ret=0x1, pos=0xb7bea117 buf=0xb7bea0e8
I/wpa_supplicant( 4012): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4012): 0	NG700	any	
D/WifiNative-wlan0(  909):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  909): 0	NG700	any	
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 ssid
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 bssid
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
,D/HtcWiFiWidget_WiFiWidgetProvider( 4022): onWiFiStateChanged() for widget: 
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 priority
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/HtcWiFiWidget_WiFiWidgetProvider( 4022): updateWidget(context) for widget: 
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
,D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
,D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wep_key3'
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
,D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 psk
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4012): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 proto
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  909): Failed to look-up a string: W
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 pairwise
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  909): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 group
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  909): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  909): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  909): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wapi_cert
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  909): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
,D/WifiConfigStore(  909): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  909): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 limited
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 eap
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 phase2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
,D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 identity
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 password
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 engine
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 key_id
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'key_id'
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  909): doString: GET_NETWORK 0 private_key
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4012): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  909): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  909): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4012): device_name='a51ul_htc_europe'
,D/wpa_supplicant( 4012): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SET manufacturer HTC
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4012): manufacturer='HTC'
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4012): model_name='HTC Desire 820'
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4012): model_number='HTC Desire 820'
D/WifiNative-wlan0(  909):    returned true
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4012): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): WiFioffload: update mobile network = UNINITIALIZED
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SET auto_interworking 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4012): auto_interworking=0
I/wpa_supplicant( 4012): wpa_supplicant_scan enter
I/wpa_supplicant( 4012): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4012): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4012): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  909):    returned true
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 4012): Scan req (ret=0) - timeout 10 secs
D/wpa_supplicant( 4012): nl80211: Event message available
D/wpa_supplicant( 4012): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  909): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: RECONNECT
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: STATUS
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): SET_SCREEN_ON:On
I/wpa_supplicant( 4012): htc_wext_set_keepalive +
I/wpa_supplicant( 4012): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4012): getPrivFuncNum +	
,I/wpa_supplicant( 4012): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4012): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4012): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4012): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4012): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SET ps 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4012): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
W/Settings(  909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  909): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE: field=AIR_MODE id=0
D/libc    (  909): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETBAND 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): SETBAND: 0
D/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4012): P2P: Add operating class 81
D/wpa_supplicant( 4012): P2P: Add operating class 115
D/wpa_supplicant( 4012): P2P: Add operating class 116
D/wpa_supplicant( 4012): P2P: Add operating class 117
D/wpa_supplicant( 4012): P2P: Update channel list
I/wpa_supplicant( 4012): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
,I/wpa_supplicant( 4012): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4012): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4012): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4012): p2p_oper_reg_class=126
D/wpa_supplicant( 4012): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4012): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 4012): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4012): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4012): p2p_oper_channel=36
E/wpa_supplicant( 4012): P2P: Own oper channel update failed: -1
,D/wpa_supplicant( 4012): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4012): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4012): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4012): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: BSS_FLUSH 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  909): startMonitoring(p2p0) with mConnected = true
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  909):    returned false
D/WifiP2pService(  909): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnablingState
D/WifiP2pService(  909): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  909): doBoolean: SET pno 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4012): wpa_supplicant_scan enter
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-p2p0(  909): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4012): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4012): persistent_reconnect=1
I/wpa_supplicant( 4012): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doBoolean: SET device_name Android_63cc
W/WifiHW  (  909): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 4012): CTRL_IFACE SET 'device_name'='Android_63cc'
,D/wpa_supplicant( 4012): device_name='Android_63cc'
I/wpa_supplicant( 4012): Recv Cmd 2: SET device_name=Android_63cc
I/QuickSettingWifi( 1109): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  909): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 4012): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 4012): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4012): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 4012): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  909): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
,D/wpa_supplicant( 4012): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4012): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  909): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/WifiStateMachine(  909): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  909): P2p socket connection successful
D/WifiP2pService(  909): P2pEnabledState
D/WifiP2pService(  909): sending p2p connection changed broadcast
D/WifiDisplayController(  909): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  909): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
,D/WifiDisplayController(  909): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  909): mWfdEnabled :false, networkInfo.isConnected() :false
D/wpa_supplicant( 4012): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4012): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4012): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  909): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4012): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4012): Single channel concurrency preference: sta
,I/wpa_supplicant( 4012): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doString: STATUS
W/WifiHW  (  909): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  909): doBoolean: P2P_FLUSH
W/WifiHW  (  909): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4012): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4012): P2P: Stopping find
D/wpa_supplicant( 4012): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4012): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4012): Recv Cmd 2: P2P_FLUSH
,D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  909): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4012): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4012): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doString: LIST_NETWORKS
W/WifiHW  (  909): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4012): list_network_info: ret=0x22, pos=0xb7bea10a buf=0xb7bea0e8
I/wpa_supplicant( 4012): list_network_info: buf=network id / ssid / bssid / flags
,I/wpa_supplicant( 4012): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  909):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  909): doBoolean: AP_SCAN 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  909):    returned false
D/WifiNative-p2p0(  909): doBoolean: SET wifi_display 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4012): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4012): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4012): WFD: Update WFD IE
I/wpa_supplicant( 4012): WFD: Update WFD IE - DONE
,I/wpa_supplicant( 4012): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  909):    returned true
D/WifiNative-p2p0(  909): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  909): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4012): WFD: Set subelement 0
D/wpa_supplicant( 4012): WFD: Update WFD IE
I/wpa_supplicant( 4012): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4012): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  909):    returned true
,D/WifiP2pService(  909): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  909): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  909):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  909):  primary type: 10-0050F204-5
D/WifiDisplayController(  909):  secondary type: null
D/WifiDisplayController(  909):  wps: 0
D/WifiDisplayController(  909):  grpcapab: 0
D/WifiDisplayController(  909):  devcapab: 0
D/WifiDisplayController(  909):  status: 3
D/WifiDisplayController(  909):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  909):  WFD CtrlPort: 0
D/WifiDisplayController(  909):  WFD MaxThroughput: 0
,D/WifiP2pService(  909): sending p2p persistent groups changed broadcast
D/WifiP2pService(  909): InactiveState
D/WifiP2pService(  909): InactiveState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  909):  WFD CtrlPort: 7236
D/WifiP2pService(  909):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  909):  WFD CtrlPort: 7236
D/WifiP2pService(  909):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  909): Successfully set WFD info.
I/WifiDisplayController(  909): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  909): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  909):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  909):  primary type: 10-0050F204-5
D/WifiDisplayController(  909):  secondary type: null
D/WifiDisplayController(  909):  wps: 0
D/WifiDisplayController(  909):  grpcapab: 0
D/WifiDisplayController(  909):  devcapab: 0
D/WifiDisplayController(  909):  status: 3
D/WifiDisplayController(  909):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  909):  WFD CtrlPort: 7236
D/WifiDisplayController(  909):  WFD MaxThroughput: 50
,V/AudioService(  909): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  909):     Client/Owner: Client
V/AudioService(  909):     GroupId: 
V/AudioService(  909):     Passphrase: 
V/AudioService(  909):     SessionId: 0
V/AudioService(  909):     IP Address: }
D/HtcEffectManagerBase(  909): onEventChanged id=5 status=false
D/HtcEffectManager(  909): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  909): convertEffect before=902
,D/HtcEffectManager(  909): convertEffect after=902
,D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,D/wpa_supplicant( 4012): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4012): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4012): nl80211: if_removed already cleared - ignore event
D/Tethering(  909): interfaceLinkStateChanged p2p0, false
,D/Tethering(  909): interfaceStatusChanged p2p0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4012): nl80211: Event message available
D/wpa_supplicant( 4012): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 4012): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4012): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 4012): nl80211: Survey data missing
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4012): Sorted scan results
I/wpa_supplicant( 4012): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 4012): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-43
I/wpa_supplicant( 4012): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-44
I/wpa_supplicant( 4012): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 4012): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-85
I/wpa_supplicant( 4012): [NULL] fe:94:e3:11:35:3c freq=2412 level=-89
I/wpa_supplicant( 4012): [NULL] fc:94:e3:11:35:3a freq=2412 level=-89
D/wpa_supplicant( 4012): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 4012): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4012): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4012): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4012): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4012): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4012): Add randomness: count=7 entropy=5
D/wpa_supplicant( 4012): Add randomness: count=8 entropy=6
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4012): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 4012): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4012): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4012): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4012): wpa_supplicant_pick_network+
I/wpa_supplicant( 4012): Selecting BSS from priority group 1
I/wpa_supplicant( 4012): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4012): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4012): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4012): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4012):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4012):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-43
I/wpa_supplicant( 4012): Start print parameters
I/wpa_supplicant( 4012): wpa_s->wpa_state is 3,
,I/wpa_supplicant( 4012): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4012): isConcurrentMode() is 0,
I/wpa_supplicant( 4012): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 4012): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4012): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4012): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 4012): wpa_s->reassociate is 0
I/wpa_supplicant( 4012): wpa_s->is_screen_on 1
I/wpa_supplicant( 4012): wpa_s->ifname wlan0
I/wpa_supplicant( 4012): End print parameters
I/wpa_supplicant( 4012): selected network = 1
D/wpa_supplicant( 4012): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7be84e8  current_ssid=0x0
,D/wpa_supplicant( 4012): wlan0: Request association with c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 4012): supplicant attached completed, trigger assoc.
,D/wpa_supplicant( 4012): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4012): TDLS: TDLS is allowed in the target BSS
,I/wpa_supplicant( 4012): check if in concurrent case
I/wpa_supplicant( 4012): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 4012): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4012): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4012): wpa_supplicant_associate, 1795,
D/wpa_supplicant( 4012): RSN: PMKSA cache search - network_ctx=0xb7be84e8 try_opportunistic=0
,D/wpa_supplicant( 4012): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4012): RSN: No PMKSA cache entry found
,I/wpa_supplicant( 4012): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4012): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 4012): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 4012): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 6
,D/wpa_supplicant( 4012): nl80211: Unsubscribe mgmt frames handle 0xb7be7718 (mode change)
D/wpa_supplicant( 4012): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7be7718
,D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718,
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718,
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Register frame type=0xd0 nl_handle=0xb7be7718
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4012): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4012):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4012):   * freq=2412
D/wpa_supplicant( 4012):   * Auth Type 0
D/wpa_supplicant( 4012):   * WPA Versions 0x2
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4012): nl80211: Connect request send successfully,
,D/wpa_supplicant( 4012): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4012): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987,
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4012): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4012): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 4012): reply (897) for get BSS: id=0
I/wpa_supplicant( 4012): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4012): freq=5220
I/wpa_supplicant( 4012): level=-50
I/wpa_supplicant( 4012): tsf=0000000106952345
I/wpa_supplicant( 4012): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4012): ssid=NG7005g
I/wpa_supplicant( 4012): ====
I/wpa_supplicant( 4012): id=1,
I/wpa_supplicant( 4012): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4012): freq=2412
I/wpa_supplicant( 4012): level=-43
I/wpa_supplicant( 4012): tsf=0000000106952334
I/wpa_supplicant( 4012): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4012): ssid=NG700
I/wpa_supplicant( 4012): ====
I/wpa_supplicant( 4012): id=2
I/wpa_supplicant( 4012): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 4012): freq=2412
I/wpa_supplicant( 4012): level=-44
I/wpa_supplicant( 4012): tsf=0000000106952314
I/wpa_supplicant( 4012): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4012): ssid=01ABC
I/wpa_supplicant( 4012): ====
I/wpa_supplicant( 4012): id=3
I/wpa_supplicant( 4012): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4012): freq=2427
I/wpa_supplicant( 4012): level=-80
,I/wpa_supplicant( 4012): tsf=0000000106952358
I/wpa_supplicant( 4012): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4012): ssid=Gonzos
I/wpa_supplicant( 4012): ====
I/wpa_supplicant( 4012): id=4
I/wpa_supplicant( 4012): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 4012): freq=2437
I/wpa_supplicant( 4012): level=-85
I/wpa_supplicant( 4012): tsf=0000000106952367
I/wpa_supplicant( 4012): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
,I/wpa_supplicant( 4012): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 4012): ====
I/wpa_supplicant( 4012): id=5
I/wpa_supplicant( 4012): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 4012): freq=2412
I/wpa_supplicant( 4012): level=-89
I/wpa_supplicant( 4012): tsf=0000000106952377
I/wpa_supplicant( 4012): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 4012): ssid=UPC Wi-Free
I/wpa_supplicant( 4012): ====
I/wpa_supplicant( 4012): id=6
I/wpa_supplicant( 4012): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 4012): freq=2412
,I/wpa_supplicant( 4012): level=-89
I/wpa_supplicant( 4012): tsf=0000000106952387
I/wpa_supplicant( 4012): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4012): ssid=UPC0039325
I/wpa_supplicant( 4012): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/wpa_supplicant( 4012): EAPOL: disable timer tick
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 106952345, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -43, frequency: 2412, timestamp: 106952334, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -44, frequency: 2412, timestamp: 106952314, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 106952358, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -85, frequency: 2437, timestamp: 106952367, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2412, timestamp: 106952377, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (7) end of scan result ==
D/WifiStateMachine(  909): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2412, timestamp: 106952387, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 7 to mScanResults
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/bt-btu  ( 3931): btu_task received preload complete event
,D/bt-btm  ( 3931): btm_acl_device_down
D/bt-btm  ( 3931): btm_acl_reset_paging
,D/bt-btm  ( 3931): btm_acl_set_discing
,I/bt-btm  ( 3931): btm_reset_complete
,I/bt-btm  ( 3931): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3931): Start reading local supported commands
,D/bt-btm  ( 3931): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3931): BTM reads next extended features page (1)
,D/bt-btm  ( 3931): BTM reads next extended features page (2)
,D/bt-btm  ( 3931): BTM reached last extended features page (2)
,D/bt-btm  ( 3931): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3931): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3931): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,D/bt-btm  ( 3931): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3931): btm_read_ble_wl_size 
,D/bt-btm  ( 3931): btm_read_white_list_size_complete 
,D/bt-btm  ( 3931): btm_get_ble_buffer_size 
D/bt-btm  ( 3931): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3931): btm_read_ble_local_supported_features 
D/bt-btm  ( 3931): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3931): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3931): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3931): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3931): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3931): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3931): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3931): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3931): BTM_SetInquiryMode
I/bt-btm  ( 3931): BTM_SetPageScanType
I/bt-btm  ( 3931): BTM_SetInquiryScanType
D/bt-btm  ( 3931): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3931): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3931): BTM_BleLoadLocalKeys
D/bt-btm  ( 3931): BTM_BleLoadLocalKeys
I/bt-btm  ( 3931): BTM_Sec: application registered
E/bt-btm  ( 3931): BTM_SecRegister:p_cb_info->p_le_callback == 0x61ff3941 
I/bt-btm  ( 3931): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3931): SMP_Register state=0
E/bt-btm  ( 3931): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61ff3941 
I/bt-btm  ( 3931): BTM_Sec: application registered
D/bt-btm  ( 3931): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3931): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3931): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3931): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3931): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3931): BTM_RegBusyLevelNotif
I/bt-att  ( 3931): GATT_Register
D/bt-att  ( 3931): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3931): allocated gatt_if=3
I/bt-att  ( 3931): GATT_StartIf gatt_if=3
D/bt-att  ( 3931): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3931): gatt_find_the_connected_bda found=0 found_idx=7
,E/bt-btif ( 3931): Calling BTA_HhEnable
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
E/bt-btif ( 3931): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3931): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:2 len:6
I/bt-btm  ( 3931): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/BluetoothAdapterProperties( 3931): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:1 len:14
,D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:3
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:7 len:4
,D/bt-btm  ( 3931): BTM_AllocateSCN
D/BluetoothAdapterProperties( 3931): Scan Mode:20
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3931): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:8 len:30
,I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:4
,D/bt-btm  ( 3931): BTM_AllocateSCN
D/BluetoothAdapter( 3931): getBluetoothService(): entry
D/BluetoothAdapter( 3931): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3931): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b964a8
D/BluetoothDevice( 3931): getService : Register callback
,I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/BluetoothAdapterProperties( 3931): Adding bonded device:B4:CE:F6:AB:A4:6A
,I/bt-btm  ( 3931): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
,D/BluetoothAdapterProperties( 3931): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 3931): Adding bonded device:34:FC:EF:9D:93:0B
I/bt-btm  ( 3931):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3931):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3931):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3931):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3931): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3931): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/bt-avp  ( 3931): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3931): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
D/BluetoothAdapterProperties( 3931): Adding bonded device:7C:F9:0E:34:8A:A0
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 3931): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3931): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 393,1): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3931): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 3931): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3931): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 3931): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3931): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 3931): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3931): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3931): GATT_Register
D/bt-att  ( 3931): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3931): allocated gatt_if=4
I/bt-att  ( 3931): GATT_StartIf gatt_if=4
D/bt-att  ( 3931): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3931): gatt_find_the_connected_bda found=0 found_idx=7
D/BluetoothAdapterProperties( 3931): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3931): Remote class is:5898764
I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3931): Remote class is:5898764
I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
D/BluetoothRemoteDevices( 3931): Remote class is:5898764
D/wpa_supplicant( 4012): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4012): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4012): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4012): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4012): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4012): nl80211: Event message available
D/wpa_supplicant( 4012): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4012): nl80211: Connect event
D/wpa_supplicant( 4012): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4012): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4012): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4012): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4012): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4012): Add randomness: count=9 entropy=7
I/wpa_supplicant( 4012): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4012): TDLS: Remove peers on association
D/wpa_supplicant( 4012): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4012): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4012): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4012): htc_wext_set_keepalive +
I/wpa_supplicant( 4012): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4012): getPrivFuncNum +	
I/wpa_supplicant( 4012): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4012): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4012): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4012): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4012): Get randomness: len=32 entropy=8
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Associated
I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/BluetoothRemoteDevices( 3931): Remote class is:5898764
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
I/wpa_supplicant( 4012): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7be79f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4012):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4012): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4012): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f4eb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4012):    broadcast key
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4012): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4012): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4012): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4012): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4012): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4012): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4012): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4012): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4012): set send_ind_to_ndc = 0
I/wpa_supplicant( 4012): htc_wext_set_TX_TRACKING (1)+
D/WifiApDatabaseHandler(  909): updateConnectedAP...
I/wpa_supplicant( 4012): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4012): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4012): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4012): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4012): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4012): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4012): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4012): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4012): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4012): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4012): EAPOL authentication completed successfully
I/wpa_supplicant( 4012): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4012): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4012): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
D/BluetoothRemoteDevices( 3931): Remote class is:5898764
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,I/bt-btif ( 3931): BTA_JvEnable
I/bt-btm  ( 3931): BTM_ReadConnectability
I/bt-btm  ( 3931): BTM_ReadDiscoverability
I/bt-btm  ( 3931): BTM_SetDiscoverability
I/bt-btm  ( 3931): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3931): br_edr_supported=0x2
I/bt-btm  ( 3931): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3931): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3931): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3931): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3931): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3931): BTM_SetConnectability
I/bt-btm  ( 3931): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3931): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3931): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3931): BTM_SetDiscoverability
I/bt-btm  ( 3931): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3931): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3931): br_edr_supported=0x0
I/bt-btm  ( 3931): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3931): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3931): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3931): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3931): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3931): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3931): BTM_SetConnectability
I/bt-btm  ( 3931): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3931): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3931): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3931): bta_pan_co_init
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3931): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3931):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3931):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3931): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3931):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3931):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
E/bt_mct  ( 3931): hci lib postload completed
I/bt-btif ( 3931): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3931): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3931): ScanMode =  20
D/BluetoothAdapterProperties( 3931): State =  11
I/bt-btm  ( 3931): BTM_SetDiscoverability
I/bt-btm  ( 3931): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3931): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3931): br_edr_supported=0x0
I/bt-btm  ( 3931): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3931): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3931): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3931): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3931): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3931): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3931): BTM_SetConnectability
I/bt-btm  ( 3931): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3931): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3931): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3931): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3931): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3931): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3931): Setting state to 12
I/BluetoothAdapterState( 3931): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3931): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  909): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  909): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  909): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  909): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 3931): Entering On State
I/bt-btif ( 3931): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothHeadset( 1220): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1102380712)( 3931): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3931): Scan Mode:21
I/bt-btif ( 3931): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3931): Discoverable Timeout:120
D/BluetoothAdapterProperties( 3931): getBondedDevices: length=5
D/BluetoothHeadset( 1220): Proxy object connected
D/BluetoothA2dp(  909): onBluetoothStateChange: up=true
D/BluetoothHeadset(  909): onBluetoothStateChange: up=true
D/BluetoothA2dp(  909): Proxy object connected
D/BluetoothHeadset( 1220): onBluetoothStateChange: up=true
D/BluetoothAdapter(  909): 1111805128: getState(). Returning 12
D/BluetoothHeadset( 1109): onBluetoothStateChange: up=true
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/BluetoothHeadset( 1220): Proxy object connected
D/BluetoothPhoneService( 1220): BluetoothHeadset onServiceConnected
D/BluetoothAdapterService(1102380712)( 3931): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3931): getBondedDevices: length=5
D/BluetoothHeadset( 1109): Proxy object connected
D/BluetoothPan(  909): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset(  909): Proxy object connected
I/QuickSettingMiniLite( 1109): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e4e888
D/BluetoothManagerService(  909): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapter(  909): 1111805128: getState(). Returning 12
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothP,an$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothAdapter( 1220): 1103716176: getState(). Returning 12
I/IntentController( 1109): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothPan(  909): BluetoothPAN Proxy object connected
D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  909): acquireWL(4232f958): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3316 1000 null
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1109): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
,D/BluetoothManagerService(  909): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
V/BluetoothPbapReceiver( 3931): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3931): ***********state = 12
D/BluetoothManagerService(  909): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  909): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1109): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  909): releaseWL(4232f958): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/HtcBtWidget_BTWidgetProvider( 3957): onBTStateChanged() for widget: 
D/BluetoothMasReceiver( 3931): Bluetooth STATE CHANGED to 12
,D/HtcBtWidget_BTWidgetProvider( 3957): updateWidget(context) for widget: 
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,V/BluetoothSapReceiver( 3931): SapReceiver onReceive 
,V/BluetoothSapReceiver( 3931): action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424662a8:true
V/BluetoothSapReceiver( 3931):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 3931): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  909): acquireWL(432cff40): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3316 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1755/10178)
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 12
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 12
V/BluetoothMasService( 3931): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3931): Manager Instance is not NULL
I/LocationAgent( 3316): new LocationAgent instance!!
D/HtcTagManager( 3316): HtcTagManager construction complete
D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
D/EmailUtils( 3931): ============NULL aList========
V/EmailUtils( 3931): <-getEmailAccountIdList
D/BluetoothInputDevice( 3316): BluetoothInputDevice()
D/DhcpStateMachine(  909): [StoppedState] Start DHCP
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
D/BluetoothInputDevice( 3316): BluetoothInputDevice(): Binding service...
,D/BluetoothManagerService(  909): Registered receivers: 7
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/BluetoothPan( 3316): BluetoothPan()
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 8
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
,D/BluetoothPan( 3316): BluetoothPan(): Binding service...
,D/WifiStateMachine(  909): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  909): doBoolean: MOBILE_TYPE Unknown
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  909):    returned true
V/BluetoothSapService( 3931): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3931): state: 12
,D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 12
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
,W/ContextImpl( 3931): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): Power_Mode_Type mode = 1
I/wpa_supplicant( 4012): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
V/BluetoothSapService( 3931): Starting SAP server process
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/BluetoothMap( 3316): Create BluetoothMap proxy object
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/BluetoothManagerService(  909): registerStateChangeCallback+
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 9
D/WifiNative-wlan0(  909):    returned null
E/BluetoothMap( 3316): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(4261b558): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
,D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/BluetoothPbapService( 3931): Handler(): got msg=1
D/BluetoothManagerService(  909): registerStateChangeCallback+
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 10
D/WifiNative-wlan0(  909):    returned null
D/BluetoothSap( 3316): BluetoothSap() call bindService
,V/BluetoothPbapService( 3931): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3931): Pbap Service initSocket
,V/BluetoothMasService( 3931): handleMessage: mIsEmailEnabledtrue
,V/BtMns   ( 3931): BluetoothMns: isEmailEnabled: true
,D/BluetoothPbap( 3316): BluetoothPbap()
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42590350 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42590350 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothMasService( 3931): Map_prev 1
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 11
D/BluetoothAdapter( 3931): getBluetoothService(): entry
W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
D/BluetoothPbap( 3316): BluetoothPbap(): Binding service...
E/BluetoothServiceJni( 3931): SOCK FLAG = 1 ***********************
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3931):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3931): Succeed to create listening socket 
V/BluetoothPbapService( 3931): Accepting socket connection...
D/BluetoothAdapter( 3931): getBluetoothService(): entry
,W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3931): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/BluetoothA2dp( 3316): BluetoothA2dp()
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3931):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  909): registerStateChangeCallback+
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 12
D/BluetoothAdapter( 1109): 1105084880: getState(). Returning 12
D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
,D/BluetoothA2dp( 3316): BluetoothA2dp(): Binding service...
D/BluetoothAdapter( 3931): getBluetoothService(): entry
,W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothAdapter( 1109): 1105084880: getState(). Returning 12
E/BluetoothServiceJni( 3931): SOCK FLAG = 3 ***********************
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3931):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
I/QuickSettingBluetooth( 1109): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
I/QuickSettingWifi( 1109): receive.wifiConnect:false wifiAPname:null elapse:1
,D/PhoneStatusBar( 1109): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothHeadset( 3316): BluetoothHeadset()
,D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 13
D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
,D/BluetoothHeadset( 3316): BluetoothHeadset(): Binding service...
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/HtcTagManager( 3316): startProxy
,W/ContextImpl( 3316): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/BluetoothAdapter( 1109): 1105084880: getState(). Returning 12
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3316): LocalBluetoothProfileManager construction complete
I/QuickSettingMiniLite( 1109): updateLiteState:no connect device!
,D/BluetoothSapService( 3931): Sap_prev 1
,V/BluetoothSapService( 3931): SAP Service startRfcommListenerThread
V/TAG     ( 3931): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3931): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b8cd30
,D/DockEventReceiver( 3316): finishStartingService: stopping service
,V/BluetoothPbapService( 3931): Pbap Service onBind
,V/BluetoothSapService( 3931): Sap Service initRfcommSocket
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3931): getBluetoothService(): entry
,W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3994): onCreate: going to find gatt base service first.
E/BluetoothServiceJni( 3931): SOCK FLAG = 3 ***********************
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3931):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothSapService( 3931): Succeed to create listening socket 
,V/BluetoothSapService( 3931): Accepting socket connection...
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3931): getBluetoothService(): entry
,W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3931): SOCK FLAG = 0 ***********************
I/BluetoothFtpService( 3931): Ftp Service onCreate
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 3931):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 12
,I/BtOppRfcommListener( 3931): Accept thread started.
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothMasReceiver( 3931): Bluetooth STATE CHANGED to 12
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothPan( 3316): BluetoothPAN Proxy object connected
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/PanProfile( 3316): Bluetooth service connected
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e3d228:true
D/BluetoothA2dp( 3316): Proxy object connected
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
,D/A2dpProfile( 3316): Bluetooth service connected
,D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
,D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
,D/[HTC_BLE][Constants]( 3994):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3994):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 3994):  + discoverServicesOnBonded = false
,D/BluetoothFtpService( 3931): Ftp_prev 1
D/BluetoothHeadset( 3316): Proxy object connected
,D/HeadsetProfile( 3316): Bluetooth service connected
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -43, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiService(  909): New client listening to asynchronous messages
D/BluetoothAdapter( 3931): getBluetoothService(): entry
W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothInputDevice( 3316): Proxy object connected
D/HidProfile( 3316): Bluetooth service connected
D/BluetoothAdapter( 3316): 1103954544: getState(). Returning 12
E/BluetoothServiceJni( 3931): SOCK FLAG = 1 ***********************
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3931):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3931): Run Accept thread
D/BluetoothAdapter( 3931): 1102398888: getState(). Returning 12
V/BluetoothMasService( 3931): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3931): Manager Instance is not NULL
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3994):  + Google LE service found. Using BaseLeProfilesGoogle.
D/SapServerProfile( 3316): Bluetooth service connected
D/BluetoothPbap( 3316): Proxy object connected
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3994): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b55df8
D/PbapServerProfile( 3316): Bluetooth service connected
D/[HTC_BLE][Constants]( 3994): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3994): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3994): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3994): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3994): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 3994): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3994): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
D/PMS     (  909): releaseWL(432cff40): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/HtcTagManager( 3316): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3994): Received state change = 12
D/HtcTagProfile( 3316): setup proxy
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3994): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
D/HtcPxpProfile( 3316): setup proxy
D/HtcFmpProfile( 3316): setup proxy
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3994): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b55df8
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3994): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b55df8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3994): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b55df8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b60de0
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3994): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b55df8
D/EmailUtils( 3931): ============NULL aList========
V/EmailUtils( 3931): <-getEmailAccountIdList
,D/BluetoothMasService( 3931): Map_prev 1
,W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e4e860:true
,W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3750): new LocationAgent instance!!
,D/HtcTagManager( 3750): HtcTagManager construction complete
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/RingtoneManager( 3994): getExternalStorageState=mounted
D/BluetoothInputDevice( 3750): BluetoothInputDevice()
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 14
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/BluetoothInputDevice( 3750): BluetoothInputDevice(): Binding service...
,D/BluetoothPan( 3750): BluetoothPan()
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 15
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/BluetoothPan( 3750): BluetoothPan(): Binding service...
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[-1]: Crocus
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[1]: Daisy
D/BluetoothMap( 3750): Create BluetoothMap proxy object
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[5]: Hangouts Message
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[8]: Olive
D/wpa_supplicant( 4012): EAPOL: startWhen --> 0
D/wpa_supplicant( 4012): EAPOL: disable timer tick
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3994):  + mAlertUri: content://settings/system/alarm_alert
E/BluetoothMap( 3750): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothSap( 3750): BluetoothSap() call bindService
D/BluetoothManagerService(  909): Registered receivers: 16
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 17
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3994): BleProfilesStateMachine is initialized...
,D/BluetoothPbap( 3750): BluetoothPbap()
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3994): Enter IdleState
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 18
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3994): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3994): initScanModeInterface: true
,W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
D/BluetoothPbap( 3750): BluetoothPbap(): Binding service...
,W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3994): loadDeviceConfiguration() init =true
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3994):  + mTag.getPrimaryDeviceList() = []
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@433f2dc8:true
D/[HTC_BLE][Constants]( 3994):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3994):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3994):  + discoverServicesOnBonded = false
D/BluetoothA2dp( 3750): BluetoothA2dp()
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
D/BluetoothA2dp( 3750): BluetoothA2dp(): Binding service...
,D/BluetoothManagerService(  909): Registered receivers: 19
,D/BluetoothHeadset( 3750): BluetoothHeadset()
D/BluetoothManagerService(  909): registerStateChangeCallback+
,D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 20
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/BluetoothHeadset( 3750): BluetoothHeadset(): Binding service...
,W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3994): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b60de0
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/HtcTagManager( 3750): startProxy
,W/ContextImpl( 3750): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3750): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
D/LocalBluetoothProfileManager( 3750): setBluetoothStateOn
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
D/HtcTagManager( 3750): startProxy
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
D/BluetoothAdapterService(1102380712)( 3931): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3931): getBondedDevices: length=5
D/BluetoothAdapter( 3750): getBluetoothService(): entry
D/BluetoothAdapter( 3750): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3750): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b96450
D/BluetoothDevice( 3750): getService : Register callback
E/BluetoothDevice( 3750): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
D/HtcTagManager( 3750): addHtcTagProfiles
,E/BluetoothDevice( 3750): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/HtcTagManager( 3750): addHtcTagProfiles
,E/BluetoothDevice( 3750): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/HtcTagManager( 3750): addHtcTagProfiles
,E/BluetoothDevice( 3750): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/HtcTagManager( 3750): addHtcTagProfiles
,E/BluetoothDevice( 3750): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/HtcTagManager( 3750): addHtcTagProfiles
,D/BluetoothInputDevice( 3750): Proxy object connected
,D/HidProfile( 3750): Bluetooth service connected
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/BluetoothPan( 3750): BluetoothPAN Proxy object connected
D/PanProfile( 3750): Bluetooth service connected,
D/SapServerProfile( 3750): Bluetooth service connected
D/BluetoothPbap( 3750): Proxy object connected
D/PbapServerProfile( 3750): Bluetooth service connected
D/BluetoothA2dp( 3750): Proxy object connected
,D/A2dpProfile( 3750): Bluetooth service connected
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/BluetoothHeadset( 3750): Proxy object connected
,D/HeadsetProfile( 3750): Bluetooth service connected
,D/BluetoothAdapter( 3750): 1102433624: getState(). Returning 12
,D/HtcTagManager( 3750): onServiceConnected
D/HtcTagProfile( 3750): setup proxy
D/HtcPxpProfile( 3750): setup proxy
,D/HtcFmpProfile( 3750): setup proxy
,I/SensorManager(  909): mEventCount = 1350
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4,
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42180508
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  909): pid=909, uid=1000
,W/SensorService(  909): Active sensors: size = 2
,W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
I/PMS     (  909): Going to sleep due to screen timeout...
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42180508, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423ab6e8
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@41b6bdf0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  909): mWirelessDisplayManager is null
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4012): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  909): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  909): releaseWL(4261b558): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -42 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4012): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): gateway: /192.168.1.1
,D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -42, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19124 delay=15s
,I/IntentController( 1109): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1109): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WifiWatchdogStateMachine(  909): WAN detection
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1,
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
,D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1755/10178)
D/WISPrService( 3316): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  909): default: setTeardownRequested(true)
,D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    (  357): *************************
D/libc    (  357): *** DNS CACHE FLUSHED ***
D/libc    (  357): *************************
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@424528c8
,D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    (  357): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/QuickSettingWifi( 1109): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  909): acquireWL(4220cbb0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [1][0][0]
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,I//system/bin/ip(  357): RTNETLINK answers: No such file or directory
,I/logwrapper(  357): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  357): RTNETLINK answers: No such process
,I/logwrapper(  357): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(4220cbb0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 373ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/NfcService( 1231): ScreenObserver: OFF
,D/NfcService( 1231): applyRouting - 0
,D/NfcService( 1231): applyRouting -2
D/PMS     (  909): OOBE c monitor 11
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=3872
D/PMS     (  909): acquireWL(423aece8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
W/ResourceType( 3872): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3872): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b45f50 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42d3bb40)
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/PMS     (  909): releaseWL(423aece8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  909): wakingUp
I/WindowManager(  909): No lock screen! windowToken=null
,I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  909): acquireWL(42429808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMN     (  909): onScreenOn
D/PMS     (  909): releaseWL(42429808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=99
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 2212): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1231): applyRouting - 0
D/MtpService( 2212): [MTP][onReceive]-
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1231): applyRouting -2
,D/AutoSetting( 1375): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  909): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  909): acquireWL(42b74960): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
D/PMS     (  909): releaseWL(42b74960): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1375): service - onCreate()
D/TetherSettings( 3316): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3316): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3316): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3316): Cust_ConnectToPC   : spcsc>false
D/        ( 3316): Cust_ConnectToPC   : IPT>true
D/        ( 3316): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/AutoSetting( 1375): service - AddressCache: using context: com.htc.Weather
E/SmartNS_Utility( 3316): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3316): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3316): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19125 delay=15s
I/PSReceiver( 3316): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1375): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
V/NotificationService(  909): batLight: plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c80000
D/qdlights(  909): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/LocationManagerService(  909): request 42592b80 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
I/ClockThread( 1109): stop update clock
I/SmartNS_PSService( 3316): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3316):  defaultType:0
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): SET_SCREEN_ON:On
I/wpa_supplicant( 4012): htc_wext_set_keepalive +
I/wpa_supplicant( 4012): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4012): getPrivFuncNum +	
I/wpa_supplicant( 4012): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4012): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4012): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4012): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4012): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  909):    returned true
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/BatteryController( 1109): status:2 level:99 unsupport:false plugged:true
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  909): BroadcastRSSIForIMS, newrssi =-43 , oldRssi= -200
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4012): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1109): WifiActivity: 3
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ActivityManager(  909): Disable JIT of com.htc.bgp
,I/ActivityManager(  909): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4121 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
V/NotificationService(  909): batLight: plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c80000
D/qdlights(  909): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED 3 -> 3
,V/SRS_Proc(  364): ParamSet string: screen_state=on
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/NetworkPolicy(  909): updateScreenOn: false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3994): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3994): onScreenOn: 1449671233677
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3994): onScreenOn: 1449671233677
D/PMS     (  909): acquireWL(43f34f00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1390 10028 null
,D/PMS     (  909): releaseWL(43f34f00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423ab6e8
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423ab6e8, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@41b6bdf0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(42deba78): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42deba78): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,I/CalendarProvider2( 4121): Created com.android.providers.calendar.CalendarAlarmManager@41b6eb00(com.android.providers.calendar.HtcCalendarProvider@41b56e88)
,I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19125 mDataStallAlarmIntent=PendingIntent{4244bc68: PendingIntentRecord{4209a020 android broadcastIntent}}
,D/CalendarProvider2( 4121): wait start:true
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4012): SET_SCREEN_ON:Off
I/wpa_supplicant( 4012): htc_wext_set_keepalive +
I/wpa_supplicant( 4012): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4012): getPrivFuncNum +	
I/wpa_supplicant( 4012): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4012): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4012): get_ip_address source addr = c0a80176
I/wpa_supplicant( 4012): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4012): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  909):    returned true
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(43bc57b8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
,V/SRS_Proc(  364): ParamSet string: screen_state=off
,D/NetworkPolicy(  909): updateScreenOn: false
D/ContactMessageStore( 1220): start background delete task...
D/ContactMessageStore( 1220): size: 0 , 0
D/ContactMessageStore( 1220): Background delete complete
,D/CalendarProvider2( 4121): wait end:false
,D/wpa_supplicant( 4012): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43bc57b8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4140 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1554): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  909): acquireWL(42bb2820): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1390 10028 null
,D/PMS     (  909): releaseWL(42bb2820): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3994): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3994): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3994): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3994): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3994): onScreenOff
,D/AutoSetting( 1375): service - mHandler: cancel location update
,D/AutoSetting( 1375): service -           changes count: 0
W/ContextImpl( 4140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): acquireWL(4365d6f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4140 1000 null
D/SmartSyncUtils( 4140): isEpsOn(), nState = 0
,D/PMS     (  909): releaseWL(4365d6f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4140): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4140): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4140): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4140): isEpsOn(), nState = 0,
W/ContextImpl( 4140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b6bdf0
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b6bdf0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
,W/SensorService(  909): Active sensors: size = 0
,D/WifiService(  909): New client listening to asynchronous messages
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b6bdf0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b6bdf0
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4201cf60 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4201cf60 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  909): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4161 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/PMS     (  909): acquireWL(434247f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/ConnectivityHelper( 1250): [onReceive] WIFI(1): CONNECTED
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1250/10075)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1774/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3418/10051)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (3798/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1755/10178)
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1390/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (3798/10100)
D/libc    (  357): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =8310 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43421e10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): acquireWL(425760b0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 909 1000 WorkSource{10096}
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  909): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4179 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  909): releaseWL(425760b0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/MusicStore( 4161): Database version: 95
,W/ContextImpl( 4161): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  909): acquireWL(436fe460): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 909 1000 WorkSource{10096}
,D/GpsLocationProvider(  909): [handleMessage] INJECT_NTP_TIME
,D/PMS     (  909): releaseWL(43421e10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =82e8 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42e55738): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(42e55738): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/ContextImpl( 4161): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4161): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 149
D/libc    (  357): [NET]res_nsend:resplen=104
,D/libc    (  357): [NET]res_queryN: exit 3, ancount=4
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42599a20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/DelayedSyncController( 4179): Delaying sync.
D/PMS     (  909): releaseWL(42599a20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/GpsLocationProvider(  909): NTP server returned: 1449671245186 (Wed Dec 09 15:27:25 CET 2015) reference: 110159 certainty: 17 system time offset: 10675
,W/ContextImpl( 4161): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(433ca908): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4161): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [1][0][0]
D/PMS     (  909): releaseWL(436fe460): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(43f628f8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 909 1000 WorkSource{10096}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4161, uid=10154, userID:0
,D/GpsLocationProvider(  909): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  909): releaseWL(433ca908): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(434247f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/DelayedSyncController( 4179): Delaying sync.
D/PMS     (  909): acquireWL(4364bc30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(4364bc30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43894fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/libc    (  357): [NET]res_nsend:resplen=104
D/libc    (  357): [NET]res_queryN: exit 3, ancount=4
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo_proxy-, success
D/PMS     (  909): releaseWL(43f628f8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  909): releaseWL(43894fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,D/MediaRouterService(  909): Client com.google.android.music (pid 4161): Registered
,D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,I/MediaRouter( 4161): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/IntentController( 1109): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1554): [EventService] EVENT_RESET_THEME_TIMESTAMP
,I/FeedActionBar( 1250): updateLastUpdatedTime(in String) LAST UPDATED 15:25
,D/DotMatrix( 1554): [EventService] isTheSameDay:false,timestamp is early than today:true
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.music (4161/10154)
,I/NetworkMonitor( 4161): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2212/10021)
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4207 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4161): getSelectedRoute
,I/jxcore-log( 3872): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3872): 
,I/NetworkMonitor( 4161): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4161/10154)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
,D/Process (  909): killProcessQuiet, pid=3766
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4161, uid=10154, userID:0
I/ActivityManager(  909): Killing 3766:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3766
,I/CalendarProvider2( 4121): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4121): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  909): killProcessQuiet, pid=3798
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3798:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/ACRA    ( 4207): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4207): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4207): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4207): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4207): Preparing secondary program dexes.
I/ActivityManager(  909): Recipient 3798
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/DexLibLoader( 4207): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4207): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4207): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4207): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4207): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4207): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4207): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4207): Dex already copied
D/OdexVerifier( 4207): Odex verification is skipped.
,V/DexLibLoader( 4207): Creating class loader
,V/DexLibLoader( 4207): Finished creating class loader
V/DexLibLoader( 4207): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4207): Dex already copied
D/OdexVerifier( 4207): Odex verification is skipped.
,V/DexLibLoader( 4207): Creating class loader
,V/DexLibLoader( 4207): Finished creating class loader
V/DexLibLoader( 4207): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4207): Dex already copied
D/OdexVerifier( 4207): Odex verification is skipped.
,V/DexLibLoader( 4207): Creating class loader
,V/DexLibLoader( 4207): Finished creating class loader
V/DexLibLoader( 4207): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4207): Dex already copied
D/OdexVerifier( 4207): Odex verification is skipped.
,V/DexLibLoader( 4207): Creating class loader
,V/DexLibLoader( 4207): Finished creating class loader
,V/DexLibLoader( 4207): Verifying classes from secondary dexes.
,D/DexLibLoader( 4207): DexLibLoader.ensureDexLoaded took 146 ms
,E/BTIF_CORE( 3931): NETI system_power_manager_wake : 259 param 0,
I/bt-btif ( 3931): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3931): Wake lock released
,W/dalvikvm( 4207): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4207): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4207): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4207): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4207): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4207): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4207): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4207): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4207): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =8442 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,E/FbInjectorInitializer( 4207): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  357): [NET]res_nsend:resplen=172
D/libc    (  357): [NET]res_queryN: exit 3, ancount=4
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/23.59.123.86
,W/fb4a(:<default>):StaticBindingVerifier( 4207): Verify
,D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4207): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4207): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  909): killProcessQuiet, pid=3816
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3816:com.htc.backup/1000 (adj 15): empty #17
D/PMS     (  909): acquireWL(425ecf88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
I/ActivityManager(  909): Recipient 3816
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42d3af18): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
,D/PMS     (  909): releaseWL(425ecf88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/GCM     ( 1338): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
D/PMS     (  909): releaseWL(42d3af18): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
,D/libc    ( 1338): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1338): [NET] getaddrinfo-,err=8
D/libc    ( 1338): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1338): [NET] getaddrinfo-, 1
,D/libc    ( 1338): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =33d9 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
D/PMS     (  909): acquireWL(425fc618): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1338 10028 null
,D/AutoSetting( 1375): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4235 uid=10078 gids={50078, 3003, 5012}
,W/fb4a(:<default>):UserScope( 4207): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4207): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutoSetting( 1375): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1375/10053)
,D/AutoSetting( 1375): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1375): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1375): service - onStartCommand() check timezone in 30000
D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 259
D/libc    (  357): [NET]res_nsend:resplen=79
,D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1338): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1375/10053)
,W/fb4a(:<default>):UserScope( 4207): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4235): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4235): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4235): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4235): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4235/10078)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4235/10078)
,D/PMS     (  909): acquireWL(43082028): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,I/DeviceManagement( 3784): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4235/10078)
,D/libc    ( 1338): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,W/ActivityThread( 1338): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/libc    ( 1338): [NET] getaddrinfo-,err=8
,I/DeviceManagement( 3784): WorkflowService: Starting workflow service
,I/DeviceManagement( 3784): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41d0a4e8] args=[Bundle[mParcelledData.dataSize=804]]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [8][0][0]
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 9.954MB for 84664-byte allocation
I/DeviceManagement( 3784): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 3784): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
,I/DeviceManagement( 3784): NetworkChangeWorkflow: ==================================================
I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4250 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
I/DeviceManagement( 3784): SessionStateController: Checking invariants...
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 9.968MB for 28144-byte allocation
,I/DeviceManagement( 3784): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 3784): Perf: *** Cache update - start...
,I/DeviceManagement( 3784): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 3784): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3784): Perf: *** Enabled app cache update - complete: 1 ms
I/DeviceManagement( 3784): Perf: *** Config cache update - start...
I/DeviceManagement( 3784): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 3784): ConfigCacheController: *** Updating stale config cache entries...
E/dalvikvm( 4207): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4207): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4207): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4207): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4207): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4207): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4207): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4207): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4207): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4207): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4207): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4207): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4207): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4207): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4207): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4207): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4207): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4207): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4250): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 3784): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
,W/dalvikvm( 3784): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 3784): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4250): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4250): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4250): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 10.039MB for 39954-byte allocation
,W/ContextImpl( 4250): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/System.err( 3784): Starting the internal HTTP client
,I/DeviceManagement( 3784): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEwLTE0VDEwOjI4OjM4LjU4Mlo
,D/PMS     (  909): acquireWL(43275a80): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
,D/PMS     (  909): acquireWL(443794c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  909): acquireWL(43fa7bd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1338 10028 null
,D/GCM     ( 1338): Connected
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 10.115MB for 79892-byte allocation
D/PMS     (  909): releaseWL(43082028): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
D/PMS     (  909): releaseWL(443794c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  909): releaseWL(425fc618): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1338/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
I/CheckinService( 1198): Preparing to send checkin request
,I/EventLogService( 1198): Accumulating logs since 1449669603479
D/PMS     (  909): releaseWL(43fa7bd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  909): acquireWL(43f306e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1338 10028 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1338/10028)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1338): Message class mpf
,I/DeviceManagement( 3784): DeviceClientResource: Active network...
I/DeviceManagement( 3784):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098),
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [2][0][0]
D/BuildInfo( 3784): Created new instance: com.htc.cs.lib.hms.BuildInfo@41e29ee8
,I/DeviceManagement( 3784): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1338/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
W/EventLogAggregator( 1198): Unknown tag: install_package_attempt
W/EventLogAggregator( 1198): Unknown tag: snet
,W/EventLogAggregator( 1198): Unknown tag: snet_gcore
D/PMS     (  909): releaseWL(43f306e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  909): acquireWL(43f06ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  909): releaseWL(43f06ff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/libc    ( 3784): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3784): [NET] getaddrinfo-, 1
D/libc    ( 3784): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  357): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3784): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4250/10151)
,V/WebViewChromiumFactoryProvider( 4250): Binding Chromium to main looper Looper (main, tid 1) {41b3b388}
,I/LibraryLoader( 4250): Expected native library version number "",actual native library version number ""
I/chromium( 4250): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4250): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4250): BLUETOOTH permission is missing!
D/PMS     (  909): acquireWL(43eb3440): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  909): acquireWL(43eabeb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  909): releaseWL(43eb3440): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4250): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4250): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4250): Local Branch: 
I/Adreno-EGL( 4250): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4250): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4250):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,I/GoogleHttpClient( 1198): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1198): Using GMS GoogleHttpClient
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/libc    ( 3784): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3784): [NET] getaddrinfo-,err=8
D/libc    ( 3784): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3784): [NET] getaddrinfo-, 1
D/libc    ( 3784): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =88ca +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42dd0920 u0 ReceiverList{42dd0e78 4207 com.facebook.katana/10026/u0 remote:41d3c4e0}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42dcc3a8 u0 ReceiverList{42dcc900 4207 com.facebook.katana/10026/u0 remote:41c9a2e0}}
D/WifiService(  909): New client listening to asynchronous messages
,I/NSApplication( 4250): Starting up...
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4250/10151)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4250/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=100 [1][1][0]
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (1198/10028)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (1198/10028)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(42dda420): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1390 10028 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (3657/10160)
D/PMS     (  909): releaseWL(42dda420): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (3657/10160)
,D/Process (  909): killProcessQuiet, pid=3835
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3835:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1755/10178)
,I/ActivityManager(  909): Recipient 3835
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(4305f990): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1390 10028 null
,D/GCoreFlp( 1390): Unknown pending intent to remove.
D/PMS     (  909): releaseWL(4305f990): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=4301 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  357): [NET]res_nsend:resplen=204
D/libc    (  357): [NET]res_queryN: exit 3, ancount=4
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3784): [NET] getaddrinfo_proxy-, success
,D/CalendarApplication( 4301): onCreate
,D/AlertReceiver( 4301): beginStartingService
D/PMS     (  909): acquireWL(4264feb8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4301 10013 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4207): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/PMS     (  909): acquireWL(425bbc08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  909): releaseWL(425bbc08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4207): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/GLSUser ( 1338): GoogleAccountDataService.getToken()
D/AlertService( 4301): start to updateAlertNotification!
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4207): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/AlertService( 4301): No fired or scheduled alerts
,D/HtcAlertUtils( 4301): -- cancelReminderNotification --
,D/HtcAlertUtils( 4301): broadcastExistReminder!
W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 4301): stopSelfResult true
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Process (  909): killProcessQuiet, pid=3533
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  909): releaseWL(4264feb8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  909): Killing 3533:com.google.android.gm/u0a107 (adj 15): empty #17
D/ContactMessageStore( 1220): notify MmsSms
D/AccFlag ( 1220): sense_version=6.0
D/AccFlag ( 1220): sku_id=99
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4317 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,W/WeatherRequest( 1109): request cur loc, but there is no sys cur
,W/CheckinRequestBuilder( 1198): awaiting user notification for token
,I/RemoteViews( 1109): com.google.android.gms (false,0)
D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b5c5f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
I/RemoteViews.Performance( 1109): com.google.android.gms 2 8 2 12
,I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4330 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4317): can't get weather sync account
,W/WeatherRequest( 4317): request cur loc, but there is no sys cur
,W/Settings( 4317): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  909): Recipient 3533
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4344 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
D/PMS     (  909): acquireWL(43051630): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4330 10070 null
,D/PMS     (  909): acquireWL(4347b988): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4330 10070 null
,D/AppWidgetHostView( 1250): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1250): com.htc.widget.weatherclock (true,33751552)
D/PMS     (  909): releaseWL(43051630): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/RemoteViews.Performance( 1250): com.htc.widget.weatherclock 2 8 17
,I/MultiDex( 4344): install
,I/ActivityManager(  909): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4359 uid=10090 gids={50090, 3003, 5012, 1028}
I/MultiDex( 4344): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/TodoTaskshortcut( 4330): update TASK shortcut>
I/TodoTaskNotifyService( 4330): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
I/MultiDex( 4344): loading existing secondary dex files
I/MultiDex( 4344): load found 1 secondary dex files
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/MultiDex( 4344): install done
,I/TodoTaskNotifyService( 4330): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/ProviderInstaller( 4344): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,W/NotifyReceiver( 4330): stopSelfResult true
,D/Process (  909): killProcessQuiet, pid=3619
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  909): releaseWL(4347b988): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  909): Killing 3619:com.android.vending/u0a73 (adj 15): empty #17
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,I/WorldClock.Global( 4359): isHtcDevice = true
,I/ActivityManager(  909): Recipient 3619
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=44 [9][4][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
,I/WorldClock.Global( 4359): isHtcDevice = true
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4359): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  909): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4378 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 4359): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4359): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1109): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/GoogleHttpClient( 4344): Falling back to old SSLCertificateSocketFactory
,I/DeviceManagement( 3784): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3784): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3784): DeviceClientResourceController: handleDirectives: []
,W/dalvikvm( 3784): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 3784): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 3784): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3784): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3784): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 3784): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3784): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3784): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3784): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3784): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 3784): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3784): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
,W/dalvikvm( 3784): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;,
E/dalvikvm( 3784): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 3784): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3784): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 3784): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 3784): isCompatible false
,I/System.out( 3784): createObjectMapper
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
,I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
,I/System.out( 3784): isCompatible false
,D/Process (  909): killProcessQuiet, pid=3916
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3916:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/TimeService( 4378): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449671248417
I/ActivityManager(  909): Recipient 3916
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ProviderChangeReceiver( 4301): ---------------------------------------------------
,D/ProviderChangeReceiver( 4301): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4301): start to updateAlertNotification!
,D/Process (  909): killProcessQuiet, pid=4022
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/AlertService( 4301): No fired or scheduled alerts
,D/HtcAlertUtils( 4301): -- cancelReminderNotification --
I/ActivityManager(  909): Delay finish: com.htc.calendar/.ProviderChangeReceiver
,I/ActivityManager(  909): Killing 4022:com.htc.widget.process2/u0a48 (adj 15): empty #17
,D/HtcAlertUtils( 4301): broadcastExistReminder!
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  909): Recipient 4022
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3784): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 3784): DeviceClientResource: Active network...
I/DeviceManagement( 3784):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
D/libc    ( 4344): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4344): [NET] getaddrinfo-,err=8
D/libc    ( 4344): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4344): [NET] getaddrinfo-, 1
D/libc    ( 4344): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =4813 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  357): [NET] NOT IN CACHE
D/libc    ( 3784): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3784): [NET] getaddrinfo-, 1
D/libc    ( 3784): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  357): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3784): [NET] getaddrinfo_proxy-, success
D/libc    ( 3784): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3784): [NET] getaddrinfo-,err=8
D/libc    ( 3784): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3784): [NET] getaddrinfo-, 1
D/libc    ( 3784): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =431f +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  357): [NET]res_queryN: exit 3, ancount=4
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3784): [NET] getaddrinfo_proxy-, success
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 244
D/libc    (  357): [NET]res_nsend:resplen=86
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4344): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4344): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4344): [NET] getaddrinfo-,err=8
,D/PMS     (  909): acquireWL(425a8ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  909): releaseWL(425a8ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/DeviceManagement( 3784): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3784): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3784): DeviceClientResourceController: handleDirectives: []
I/System.out( 3784): isCompatible false
,I/System.out( 3784): createObjectMapper
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
,I/System.out( 3784): isCompatible false
,I/DeviceManagement( 3784): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,I/DeviceManagement( 3784): DeviceClientResource: Active network...
I/DeviceManagement( 3784):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=15 [38][6][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (3784/10098)
,D/libc    ( 3784): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3784): [NET] getaddrinfo-, 1
,D/libc    ( 3784): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  357): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3784): [NET] getaddrinfo_proxy-, success
D/libc    ( 3784): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3784): [NET] getaddrinfo-,err=8
D/libc    ( 3784): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3784): [NET] getaddrinfo-, 1
D/libc    ( 3784): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
,D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =e216 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  357): [NET]res_queryN: exit 3, ancount=4
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3784): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  909): Resuming delayed broadcast
,W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  909): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 3957:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=3957
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  909): Recipient 3957
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4403 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  909): killProcessQuiet, pid=3418
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3418:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3418
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Adreno-EGL( 4344): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4344): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4344): Build Date: 08/28/14 Thu
,I/Adreno-EGL( 4344): Local Branch: 
I/Adreno-EGL( 4344): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4344): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4344):                  aa63bbd948f41d15fc72f585e
,I/Babel   ( 4403): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4403): MmsConfig.loadMmsSettings
,E/dalvikvm( 4403): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4403): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4403): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4403): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4403): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  909): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4429 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4403, uid=10111, userID:0
,W/Settings( 4403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4403, uid=10111, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4403, uid=10111, userID:0
,D/MessageFrequencyProvider( 4429): onCreate
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4403, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4403, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4403, uid=10111, userID:0
,V/GetPrviateResource( 4429): GetPrviateResource
D/MmsCustomizationProvider( 4429): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4429): GetPrviateResource
,D/MmsCustomizationProvider( 4429): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4403): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4403): MmsConfig.loadFromDatabase
,I/ProviderInstaller( 4403): Installed default security provider GmsCore_OpenSSL
E/Babel   ( 4403): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4403): MmsConfig.loadFromResources
,I/ActivityManager(  909): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
E/Babel   ( 4403): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4403): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Process (  909): killProcessQuiet, pid=3975
,I/ActivityManager(  909): Killing 3975:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  909): Recipient 3975
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.talk (4403/10111)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.talk (4403/10111)
,I/DeviceManagement( 3784): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3784): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3784): DeviceClientResourceController: handleDirectives: []
I/System.out( 3784): isCompatible false
I/System.out( 3784): createObjectMapper
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
I/System.out( 3784): isCompatible false
,I/System.out( 3784): isCompatible false
,D/MessageCustFlag( 4429): sense_version=6.0
,D/BTAccessoryUtil( 4429): createReceiver
,D/BTAccessoryUtil( 4429): registerReceiver return intent = null
D/MessageCustFlag( 4429): sku_id=99
,W/SystemReader( 4429): Cannot find message_ambs_application_id, use default value instead
D/Messaging( 4429): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4429): networkCode: 
,D/MessageCustFlag( 4429): sku_id=99
D/MmsConfig( 4429): SIE smsPri: null
,D/MmsConfig( 4429): networkCode: 
D/HtcTelephonyCapability( 4429): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4429): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4429): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4429): Cannot find qct_8960_interface, use default value instead
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,I/DeviceManagement( 3784): ConfigCacheController: *** Update config cache: updating 3 entries...
,I/DeviceManagement( 3784): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4403): UserRecoverableAuthException.
,E/Babel   ( 4403): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4403): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4403): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4403): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4403): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4403): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4403): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
E/Babel   ( 4403): Error getting auth token
,E/Babel   ( 4403): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4403): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4403): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4403): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4403): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4403): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4403): Account registration failedRedacted-21
E/Babel   ( 4403): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4403): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4403): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4403): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4403): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4403): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4403): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4403): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.talk (4403/10111)
,I/DeviceManagement( 3784): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 3784): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 3784): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 3784): AlarmController: Scheduling TTL alarm for: 2015.12.10 at 14:59:55.983 CET (due to: com.htc.reportagent)
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3784, uid=10098, userID:0
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,I/DeviceManagement( 3784): Perf: *** Config cache update - complete: 2159 ms
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/DeviceManagement( 3784): Perf: *** Cache update - complete: 2162 ms
,I/DeviceManagement( 3784): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41d0a4e8]
,I/DeviceManagement( 3784): WorkflowService: Stopping workflow service
I/ActivityManager(  909): Resuming delayed broadcast
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
D/PMS     (  909): acquireWL(43f305f8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4330 10070 null
D/PMS     (  909): acquireWL(43f23190): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4330 10070 null
,I/ActivityManager(  909): Delay finish: com.htc.task/.notification.NotifyReceiver
,E/TodoTaskNotifyService( 4330): java.lang.NullPointerException
,W/System.err( 4330): java.lang.NullPointerException
W/System.err( 4330): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4330): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4330): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4330): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4330): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  909): releaseWL(43f305f8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  909): releaseWL(43f23190): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4330): stopSelfResult true
W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,D/Process (  909): killProcessQuiet, pid=3316
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(43eb3440): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4330 10070 null
D/PMS     (  909): acquireWL(43d7c408): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4330 10070 null
,I/ActivityManager(  909): Killing 3316:com.android.settings/1000 (adj 15): empty #17
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/TodoTaskNotifyService( 4330): java.lang.NullPointerException
,W/System.err( 4330): java.lang.NullPointerException
D/PMS     (  909): releaseWL(43eb3440): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.gcm.ServiceAutoStarter
W/System.err( 4330): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4330): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4330): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4330): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4330): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/NotifyReceiver( 4330): stopSelfResult true
D/PMS     (  909): releaseWL(43d7c408): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  909): Recipient 3316
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/Adreno-EGL( 4344): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4344): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4344): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4344): Local Branch: 
I/Adreno-EGL( 4344): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4344): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4344):                  aa63bbd948f41d15fc72f585e
,E/Babel   ( 4403): Unexpected exception while authenticating.
,E/Babel   ( 4403): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4403): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4403): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4403): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4403): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4403): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4403): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4403): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4403): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  909): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4458 uid=10038 gids={50038}
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b63128 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/Adreno-EGL( 4344): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4344): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4344): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4344): Local Branch: 
I/Adreno-EGL( 4344): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4344): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4344):                  aa63bbd948f41d15fc72f585e
,I/RemoteViews.Performance( 1109): com.google.android.gms 2 13 3 12
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4471 uid=10077 gids={50077}
,D/Process (  909): killProcessQuiet, pid=4140
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 4140:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/SMSBackup( 4471): Got a database change event
,D/Process (  909): killProcessQuiet, pid=4161
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  909): Killing 4161:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4140
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,W/Settings( 4344): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4344/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,I/ActivityManager(  909): Recipient 4161
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  909): Client com.google.android.music (pid 4161): Died!
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,W/fb4a(:<default>):UserScope( 4207): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4207): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=7 [13][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4012): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,I/CheckinTask( 1198): Sending checkin request (9291 bytes)
D/PMS     (  909): acquireWL(42e3fe08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10014}
V/AlarmManager(  909): sending alarm PendingIntent{43290618: PendingIntentRecord{43a95568 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=115259, Int=0
W/ActivityThread( 1198): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/PMS     (  909): acquireWL(4285ae68): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4121 10014 null
I/ActivityManager(  909): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  909): releaseWL(4285ae68): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): releaseWL(42e3fe08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1198): [NET] getaddrinfo-, 1
,D/libc    ( 1198): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =b710 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 263
D/libc    (  357): [NET]res_nsend:resplen=84
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1198): [NET] getaddrinfo_proxy-, success
,E/fb4a(:<default>):LocalFbBroadcastManager( 4207): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
,D/libc    ( 4207): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4207): [NET] getaddrinfo-,err=8
D/libc    ( 4207): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4207): [NET] getaddrinfo-, 1
,D/libc    ( 4207): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =bf7f +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 18
D/libc    (  357): [NET]res_nsend:resplen=74
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4207): [NET] getaddrinfo_proxy-, success
,I/global  ( 4207): call createSocket() return a new socket.
D/libc    ( 4207): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4207): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4207): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4207): [NET] getaddrinfo-,err=8
D/PMS     (  909): releaseWL(43eabeb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 10.992MB for 32784-byte allocation
,D/PMS     (  909): acquireWL(423f2048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  909): releaseWL(423f2048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (1198/10028)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4012): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (1198/10028)
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4012): nl80211: survey data missing!
E/wpa_supplicant( 4012): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4012): environment dirty rate=2 [35][1][0]
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  909): acquireWL(42538a58): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4207 10026 null
,W/CheckinRequestBuilder( 1198): awaiting user notification for token
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b85208 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 10 3 12
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
I/CheckinTask( 1198): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1198): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1198/10028),
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4207/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  909): releaseWL(43275a80): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1198): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b4ce88 that was originally bound here
E/ActivityThread( 1198): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b4ce88 that was originally bound here
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
,I/GCM     ( 1338): GCM config loaded
,D/Messaging( 4429): mNeedToUpdateDate2 start
,D/MmsConfig( 4429): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4429): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4429): 
D/MmsAsyncWorkHandler( 4429): HM tk = 20001
,D/ReportIndicatorCache( 4429): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4429): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b417c8
D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,I/Messaging( 4429): mccmnc> 
D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4429): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4429): [DraftCache/1] refresh
,D/MmsConfig( 4429): networkCode: 
,D/Messaging( 4429): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4429): sense_version=6.0
D/PhoneStorageUtil( 4429): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4429): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4429): createReceiver
,D/Jerry   ( 4429): start to preload cursor >>>>>>>
,D/TelephUtils( 1220): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
V/MmsProvider( 1220): Update uri=content://mms, match=0
,V/MmsProvider( 1220): selection=st=129 AND m_type!=134
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/Messaging( 4429): Reset downloading state: 0
V/MmsSystemEventReceiver( 4429): TransactionService is going to be woken up.
,D/AccFlag ( 1220): sku_id=99
,V/TransactionService( 4429): 1-Creating TransactionService
,D/DraftCache( 4429): [DraftCache/457] rebuildCache
D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4429): onStartCommand: 1
,D/MmsSystemEventReceiver( 4429): unRegisterForConnectionStateChanges
V/TransactionService( 4429): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4429): Loading previous transactions.
,D/Messaging( 4429): mNeedToUpdateDate2: false
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1220): device_type: 1
D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/TransactionService( 4429): Force set service start id to 1
D/MmsSmsV2Provider( 1220):  phoneType = -1
D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
V/TransactionService( 4429): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4429): unRegisterForConnectionStateChanges
V/TransactionService( 4429): Destroying TransactionService
,D/TransactionService( 4429): stopSelfResult: true, mLastHandledServiceId: 1
D/Messaging( 4429): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,V/TransactionService( 4429): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 4429): ViewCache CreatePreload
,D/Messaging( 4429): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/Jerry   ( 1220): URI_DRAFT
,D/Cust_MMSMS( 4429): _has_set_default_values_2=true
,D/DraftCache( 4429): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4429): [DraftCache/457] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4429): 
D/MmsAsyncWorkHandler( 4429): HM tk = 20002
,D/MsgPreferenceUtils( 4429): def_index: 0
,D/MsgPreferenceUtils( 4429): globalIndex = 1
D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1220): sku_id=99
D/MsgPreferenceUtils( 4429): phone state: true
D/MsgPreferenceUtils( 4429): sd state: false
,D/MsgPreferenceUtils( 4429): vIndex = 0
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1220): sku_id=99
,I/global  ( 4207): I/O error closing connection
I/global  ( 4207): java.net.SocketException: Socket is closed
I/global  ( 4207): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4207): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4207): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4207): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4207): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4207): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4207): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4207): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4207): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4207): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4207): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4207): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4207): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4207): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4207): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4207): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4207): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4207): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4207): Removing a connection that never existed!
D/PMS     (  909): releaseWL(42538a58): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/GAV2    ( 4250): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  909): acquireWL(42609a58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1390 10028 null
,D/PMS     (  909): acquireWL(43a7f028): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1390 10028 null
,D/PMS     (  909): releaseWL(42609a58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  909): releaseWL(43a7f028): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4403, uid=10111, userID:0
,D/Process (  909): killProcessQuiet, pid=4207
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4207:com.facebook.katana/u0a26 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4207
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Process (  909): killProcessQuiet, pid=4235
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4235:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4235
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{43424430 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.htc.cs.dm
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1250): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/Launcher( 1250): Deferring update until onResume
,D/Launcher( 1250): waitUntilResume // bindAppsUpdated
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
,D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PeopleContactsSync( 1198): CP2 sync disabled
I/[PluginManager]RegisterService( 1375): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 1375): handle notify Blinkfeed plugin client changed,
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
,D/PMS     (  909): acquireWL(4366e310): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,I/ActivityManager(  909): Resuming delayed broadcast
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/ActivityManager(  909): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4526 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/PMS     (  909): releaseWL(4366e310): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  909):   Scheme: "smsto"
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4526, uid=10073, userID:0
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/Finsky  ( 4526): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (4526/10073)
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (4526/10073)
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/Finsky  ( 4526): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4526): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4526): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4526, uid=10073, userID:0
,D/Finsky  ( 4526): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4526): [1] 2.run: Finished loading 1 libraries.
,D/Process (  909): killProcessQuiet, pid=4179
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4179:com.android.chrome/u0a96 (adj 15): empty #17
,I/IcingCorporaProvider( 2664): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,D/PMS     (  909): acquireWL(43adf7e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3657 10160 null
,D/PMS     (  909): releaseWL(43adf7e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  909): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4561 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Finsky  ( 4526): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4526): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  909): Recipient 4179
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 13.507MB for 1821008-byte allocation
,D/HtcFingerPrintQuickLaunchProvider( 4561): -onCreate()
,V/Settings:HtcSettingsApplication( 4561): [4561/4561] onCreate()
,D/Process (  909): killProcessQuiet, pid=3784
,I/ActivityManager(  909): Killing 3784:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/IcingCorporaProvider( 2664): UpdateCorporaTask done [took 294 ms] updated apps [took 294 ms] 
,D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
,I/PeopleContactsSync( 1198): CP2 sync disabled
I/[PluginManager]RegisterService( 1375): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 1375): handle notify Blinkfeed plugin client changed
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(43b576d8): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  909): releaseWL(43b576d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/IcingCorporaProvider( 2664): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,W/PackageManager(  909): Unable to load service info ResolveInfo{43bd81b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  909): Recipient 3784
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42d353c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3657 10160 null
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 15.209MB for 1821008-byte allocation
D/PMS     (  909): releaseWL(42d353c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/IcingCorporaProvider( 2664): UpdateCorporaTask done [took 84 ms] updated apps [took 83 ms] 
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 16.945MB for 1821008-byte allocation
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41bc8fd8 +
,I/Prism.WidgetManager( 1250): onLoadItems() +
,D/Settings:HtcWirelessFeatureFlags( 4561): id/is att sku: 99/false
,W/SystemReader( 4561): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 4561): Cannot find support_harman, use default value instead
,W/SystemReader( 4561): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 4561): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4561): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4561): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4561): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]support         :false
,W/FingerprintManager( 4561): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4561): isSupportVoWifi: null
E/ActivityThread( 4561): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4561): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4561): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4561): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]support         :false
,W/FingerprintManager( 4561): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4561): isSupportVoWifi: null
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4561): Failed to find provider info for com.htc.vowifi
,D/PMS     (  909): acquireWL(43f9b280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10073}
,V/AlarmManager(  909): sending alarm PendingIntent{42d50368: PendingIntentRecord{423c9d28 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449671261630, Int=0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4561): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4561): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4561): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4561): [supportHomeButton]support         :false
,W/FingerprintManager( 4561): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4561): isSupportVoWifi: null
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4561): Failed to find provider info for com.htc.vowifi
,W/asset   ( 1250): Copying FileAsset 0x686f9ef8 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1250): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1250): onLoadItems() -
,I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41bc8fd8 -
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,W/PackageManager(  909): Unable to load service info ResolveInfo{43a99c08 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,D/PMS     (  909): releaseWL(43f9b280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PhoneApp( 1220): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1220): -- N1 =0
,D/PhoneApp( 1220): -- N2 =0
,D/PhoneApp( 1220): -- N3 =0
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/PlayEventLogger( 4526): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4526): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4526): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4526): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4526): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4526): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4526): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4526): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41e4fc28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 13 4 12
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,D/libc    ( 4526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4526): [NET] getaddrinfo-,err=8
D/libc    ( 4526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4526): [NET] getaddrinfo-, 1
,D/libc    ( 4526): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =1625 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 274
D/libc    (  357): [NET]res_nsend:resplen=87
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4526): [NET] getaddrinfo_proxy-, success
I/global  ( 4526): call createSocket() return a new socket.
D/libc    ( 4526): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4526): [NET] getaddrinfo-, SUCCESS
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4526): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4526): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/libc    ( 4526): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4526): [NET] getaddrinfo-,err=8
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4526): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4526): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4526): [1] DailyHygiene.reschedule: Scheduling new run in 83 minutes (failures=3)
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41bc8fd8 +
,I/Prism.WidgetManager( 1250): onLoadItems() +
,E/Prism.WidgetManager( 1250): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1250): onLoadItems() -
,I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41bc8fd8 -
,D/PMS     (  909): acquireWL(42596520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,I/BatteryService(  909): n_update end
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=99
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42596520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(42163148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
,V/AlarmManager(  909): sending alarm PendingIntent{42401598: PendingIntentRecord{4250a1f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=139540, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{41dd3568: PendingIntentRecord{424b1980 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=140048, Int=0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
,D/PMS     (  909): acquireWL(42618d98): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/PMS     (  909): acquireWL(425e1dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  909): releaseWL(425e1dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  909): releaseWL(42163148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42262fd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42618d98): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(42262fd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1375): service - has update message, not stop
,D/AutoSetting( 1375): service - mHandler: update timezone
,D/AutoSetting( 4121): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4121): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4121): service - onCreate()
,D/AutoSetting( 4121): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4121): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4121): service - mHandler: update timezone
D/AutoSetting( 4121): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4121): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4121): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4121): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4121): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4121): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1109): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41eedb68 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.htc.htclocationservice 3 13 3 11
,D/PMS     (  909): acquireWL(42d1a9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{420dd5c0: PendingIntentRecord{424ed168 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140567, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
V/AlarmManager(  909): sending alarm PendingIntent{429b5eb8: PendingIntentRecord{434573a8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449671277747, Int=0
,D/PMS     (  909): acquireWL(42d8c8d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): releaseWL(42d1a9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
,D/libc    (  357): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =acd +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  357): [NET]res_nsend:resplen=238
,D/libc    (  357): [NET]res_queryN: exit 3, ancount=10
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Finsky  ( 4526): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  909): acquireWL(43456dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43456dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  909): releaseWL(42d8c8d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{43a4e388 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): acquireWL(43427ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): releaseWL(43427ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=99
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  909): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1375): service - handleMessage() stop self
,D/AutoSetting( 1375): service - handleMessage() quit looper
,D/AutoSetting( 1375): service - onDestroy() END
,D/AutoSetting( 4121): service - handleMessage() stop self
,D/AutoSetting( 4121): service - onDestroy() END
,D/AutoSetting( 4121): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4250
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4250:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4250
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/Process (  909): killProcessQuiet, pid=4317
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Killing 4317:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4317
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(425d6518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(425d6518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43f1b048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=205023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43f1b048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42d46268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42d46268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderNotification, total:0
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 3931): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4603 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,W/ContextImpl( 4603): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4561): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4561): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4561): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4561): Cust_ConnectToPC   : spcsc>false
D/        ( 4561): Cust_ConnectToPC   : IPT>true
,D/        ( 4561): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4561): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4561): Index of the first 1 = -1
W/ContextImpl( 4561): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4561): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 4561): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 4561): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4561): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4561): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4561): [ACC]android_networking:tethering_guard_support=false
,D/Process (  909): killProcessQuiet, pid=4359
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  909): Killing 4359:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4359
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(42deab50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42deab50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(42d3c668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=265024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42d3c668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(43fbe050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43fbe050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3872): Connected to the server!
I/jxcore-log( 3872): 
,I/chromium( 3872): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  909): acquireWL(436e8b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436e8b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(435e68a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=325024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(435e68a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43fbc088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43fbc088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(4341d3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=385024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4341d3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(42df13d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42df13d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(425bc270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=445023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(425bc270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(42dc3a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42dc3a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(43f9b358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=505023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43f9b358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(430891c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(430891c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42e01208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=565024, Int=0
I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e01208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43c010c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c010c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1220): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1220): sku_id=99
D/ContactMessageStore( 1220): start background delete task...
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1220): size: 0 , 0
,D/ContactMessageStore( 1220): Background delete complete
,D/PMS     (  909): acquireWL(4366add0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=625023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4366add0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4326b660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4326b660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42e57438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=685023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e57438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(434240a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434240a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43416720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=745023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43416720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(433bffd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(433bffd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43f5bd00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=805023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43f5bd00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43a452b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/PMS     (  909): acquireWL(43b96270): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,V/AlarmManager(  909): sending alarm PendingIntent{41dd3568: PendingIntentRecord{424b1980 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=829025, Int=0
,D/PMS     (  909): releaseWL(43a452b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42cf8e48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43b96270): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(42cf8e48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(43b831a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43b831a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42d416d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=865023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42d416d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4319a330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4319a330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(427b7fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=925024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(427b7fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42605930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42605930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(426276f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426276f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43bb5d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=985024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43bb5d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,D/PMS     (  909): acquireWL(42d14d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41e093d8: PendingIntentRecord{4245d080 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=780510, Int=0
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4634 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{425937e0: PendingIntentRecord{42643b78 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449671343858, Int=10800000
,V/AlarmManager(  909): sending alarm PendingIntent{420301a0: PendingIntentRecord{425c4f90 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449671403521, Int=1800000,
V/AlarmManager(  909): sending alarm PendingIntent{42528c48: PendingIntentRecord{42607ed8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449672064339, Int=900000
,V/AlarmManager(  909): sending alarm PendingIntent{43a5e8e0: PendingIntentRecord{43428950 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449672133968, Int=0
,D/PMS     (  909): acquireWL(43c540d0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1198 10028 null
,D/PMS     (  909): acquireWL(42663c98): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1198 10028 null
,W/ContextImpl( 4603): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/EventLogService( 1198): Aggregate from 1449671247713 (log), 1449669603479 (data)
,D/PMS     (  909): releaseWL(43c540d0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
D/PowerUsageService( 4603): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4603): MY_DEBUG = false
,D/SmartSyncUtils( 4603): isEpsOn(), nState = 0
D/PMS     (  909): releaseWL(42d14d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  909): acquireWL(42cfa548): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4603 1000 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4634/10047)
,D/PMS     (  909): releaseWL(42663c98): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  909): releaseWL(42cfa548): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  909): acquireWL(42e61020): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4603 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4603): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4603): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4603): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4603): SettingOnTime = 1449698400000, randomSettingOnTime = 1449695483000
,D/SmartSyncScreenOnOffTimeReceiver( 4603): SettingOffTime = 1449687600000, randomSettingOffTime = 1449688089000
,D/SmartSyncScreenOnOffTimeReceiver( 4603): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4603): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4603): bNightModeTurnOffOnce = false
,D/PMS     (  909): releaseWL(42e61020): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=4378
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4378:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4378
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(43f4cda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
,V/AlarmManager(  909): sending alarm PendingIntent{42dbfb58: PendingIntentRecord{4250a658 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012731, Int=0
,D/PMS     (  909): acquireWL(43f463d8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1338 10028 null
,D/PMS     (  909): releaseWL(43f463d8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  909): acquireWL(43f460d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  909): releaseWL(43f4cda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  909): releaseWL(43f460d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  909): acquireWL(43f32678): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1338 10028 null
,D/GCM     ( 1338): Message class mow
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1338/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1338/10028)
,D/PMS     (  909): acquireWL(43f324f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  909): releaseWL(43f32678): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  909): releaseWL(43f324f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  909): acquireWL(43f27fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43f27fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43ee3aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1045023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43ee3aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43ee37a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43ee37a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43aa4300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43aa4300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43a8a040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1105023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43a8a040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43a89fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a89fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43a7ff48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1165024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43a7ff48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43a77a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a77a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(436202c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436202c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(43427650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1225023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43427650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43422b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43422b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(434200b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434200b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4341ef18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1285023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4341ef18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4341d458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4341d458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4341c6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1345023, Int=0
I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4341c6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(434129a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434129a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4340f0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1405024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4340f0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4340d838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4340d838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42d17700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1465024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42d17700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42599488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42599488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(424086b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1525024, Int=0
I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(424086b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(41f60500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(41f60500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42484b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1585023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42484b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42051140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42051140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(41b5c638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1645023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(41b5c638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(423329c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423329c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(41c29d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1705023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(41c29d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42ced668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42ced668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4247c1c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1765023, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4247c1c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(423d5418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423d5418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(423da6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1825024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  909): Prepared write state in 39ms
,I/ProcessStatsService(  909): Prepared write state in 22ms
,D/PMS     (  909): releaseWL(423da6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  909): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-43-23.bin
,D/PMS     (  909): acquireWL(43b3f7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43b3f7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42cee990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41ba1b10: PendingIntentRecord{41ba1ad8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1885024, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42cee990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4665): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4665): ====startRecUseTime====
D/htc.customization.log.level( 4665):  is 
W/CustomizationLogLevel( 4665): Level value is invalid, use default level 2
D/CustomizationManager( 4665):  Read ACC file spent 0.098 (s)
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4665): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4665): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4665): Parsing tag category name = system
I/CustomizationCIDLoader( 4665): Parsing tag category name = application
I/CustomizationCIDLoader( 4665): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4665): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4665): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4665): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4665): Parsing tag category name = Settings
D/CustomizationManager( 4665):  Read CID file spent 0.150 (s)
D/CustomizationManager( 4665):  All configurations done spent 0.151 (s)
W/HtcNativeFlag( 4665): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4665): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4665): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4665): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4665, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  909): killProcessQuiet, pid=3872
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  909): Killing 3872:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  909):   Force finishing activity ActivityRecord{42e09790 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  909): Copying FileAsset 0x62b67ec0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1184): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 3872 uid 10348
W/PackageSettings(  909): Skipping PackageSetting{42228038 com.example.hello/10355} due to missing metadata
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  909): channel '42002c90 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  909): channel '42002c90 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
D/WifiService(  909): Client connection lost with reason: 4
W/InputDispatcher(  909): Attempted to unregister already unregistered input channel '42002c90 com.test.thalitest.MainActivity (s)'
I/WindowState(  909): WIN DEATH: Window{42002c90 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/WindowManager(  909): WINDOW DIED Window{42002c90 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1774): Unregistering com.test.thalitest
E/acms    ( 1774): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1390): Ignoring removeGeofence because network location is disabled.
D/PMS     (  909): acquireWL(42608328): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1390 10028 null
D/PMS     (  909): releaseWL(42608328): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Scheme: "sms"
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/VoicemailCleanupService( 1274): Cleaning up data for package: com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/Launcher( 1250): Deferring update until onResume
D/Launcher( 1250): waitUntilResume // bindAppsRemoved
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/ActivityManager(  909): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4681 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
E/ExternalAccountType( 1309): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  909): Delaying start of: ServiceRecord{43f3e540 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 1198): CP2 sync disabled
I/Icing   ( 1198): doRemovePackageData com.test.thalitest
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
D/PMS     (  909): acquireWL(43bd9888): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
I/MultiDex( 4681): install
I/MultiDex( 4681): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4681): loading existing secondary dex files
I/MultiDex( 4681): load found 1 secondary dex files
I/MultiDex( 4681): install done
D/PMS     (  909): releaseWL(43bd9888): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4699 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4681): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4699): install
I/ActivityManager(  909): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4699): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4699): loading existing secondary dex files
I/MultiDex( 4699): load found 1 secondary dex files
I/MultiDex( 4699): install done
I/ActivityManager(  909): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1375): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SQLiteLog( 1375): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1375): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca58948
W/[PluginManager]RegisterService( 1375): provider may killed!
W/[PluginManager]RegisterService( 1375): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1375): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1375): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1375): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1375): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1375): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1375): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1375): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1375): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1375): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1375): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1375): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1375): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1375): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ProviderInstaller( 4699): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1375): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(424dea48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41e093d8: PendingIntentRecord{4245d080 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1719014, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{42392c40: PendingIntentRecord{42518548 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820155, Int=1800000
V/AlarmManager(  909): sending alarm PendingIntent{42465a40: PendingIntentRecord{425bfa60 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1851593, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{42e0b1a8: PendingIntentRecord{4250a658 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1912835, Int=0
D/Process (  909): killProcessQuiet, pid=4301
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/AlarmManager(  909): sending alarm PendingIntent{42528c48: PendingIntentRecord{42607ed8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449672964339, Int=900000
I/ActivityManager(  909): Killing 4301:com.htc.calendar/u0a13 (adj 15): empty #17
D/Prism.PackageStateRece_( 1250): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2664): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4721 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Recipient 4301
E/SQLiteDatabase( 4681): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4681): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4681): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4681): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4681): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4681): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4681): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4681): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4681): threadid=12: thread exiting with uncaught exception (group=0x41706e30)
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/AndroidRuntime( 4681): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4681): Process: com.google.android.gms.drive, PID: 4681
E/AndroidRuntime( 4681): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4681): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4681): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4681): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4681): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4681): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4681): 	at ctn.run(SourceFile:985)
E/SQLiteLog( 2664): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2664): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5cada158
W/dalvikvm( 2664): threadid=14: thread exiting with uncaught exception (group=0x41706e30)
E/AndroidRuntime( 2664): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2664): Process: com.google.android.googlequicksearchbox:search, PID: 2664
E/AndroidRuntime( 2664): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2664): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2664): 	at cid.d(PG:186)
E/AndroidRuntime( 2664): 	at clo.g(PG:594)
E/AndroidRuntime( 2664): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2664): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2664): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2664): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2664): 	at clr.tL(PG:827)
E/AndroidRuntime( 2664): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2664): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2664): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2664): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2664): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2664): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms.drive
E/ActivityManager(  909): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 4681): killProcess, pid=4681
D/Process ( 4681): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Process ( 2664): killProcess, pid=2664
D/Process ( 2664): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/ActivityManager(  909): Recipient 4681
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.gms.drive (pid 4681) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  909): Recipient 2664
I/ActivityManager(  909): Process com.google.android.googlequicksearchbox:search (pid 2664) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/MediaRouterService(  909): Client com.google.android.googlequicksearchbox (pid 2664): Died!
D/WifiService(  909): Client connection lost with reason: 4
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4721): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4721): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4721): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4721): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4721): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4721): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4721): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4721): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4721): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4721): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4721): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4721): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4721): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4721): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4721): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4721): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4721): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4721): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4721): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4721): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4721): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4721): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4721): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4721): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4721): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4721): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4721): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4721): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4721): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4721): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4721): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4721): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4721): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4721): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4721): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4721): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4721): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4721): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4721): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4721): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4721): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4721): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4721): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4721): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4721): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4721): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4721): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4721): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4721): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4721): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4721): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4721): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4721): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4721): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4721): threadid=11: thread exiting with uncaught exception (group=0x41706e30)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4721): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4721): Process: com.google.android.apps.docs, PID: 4721
E/AndroidRuntime( 4721): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4721): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4721): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4721): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4721): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4721): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4721): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 4721): killProcess, pid=4721
D/Process ( 4721): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4739 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
D/Process (  909): killProcessQuiet, pid=3750
I/ActivityManager(  909): Killing 3750:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@41bc8fd8 +
I/Prism.WidgetManager( 1250): onLoadItems() +
I/ActivityManager(  909): Recipient 3750
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
V/BluetoothSapService( 3931): onUnbind: android.bluetooth.IBluetoothSap
W/PackageManager(  909): Unable to load service info ResolveInfo{424cb870 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  909): Recipient 4721
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 4721) has died.
W/ContextImpl( 4739): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4752 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4739): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
E/SQLiteDatabase( 4739): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4739): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4739): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4739): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4739): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4739): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4739): threadid=10: thread exiting with uncaught exception (group=0x41706e30)
E/AndroidRuntime( 4739): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4739): Process: com.android.keychain, PID: 4739
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
E/AndroidRuntime( 4739): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4739): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4739): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4739): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4739): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4739): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.android.keychain
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4752): getInstance(Context context)
D/Process ( 4739): killProcess, pid=4739
D/Process ( 4739): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449673048782.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4739
I/ActivityManager(  909): Process com.android.keychain (pid 4739) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10363ms
D/AppTag  ( 4752): getInstance(Context context)
D/AppTag  ( 4752): onCreate()
D/PMS     (  909): acquireWL(42a546e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3657 10160 null

```
