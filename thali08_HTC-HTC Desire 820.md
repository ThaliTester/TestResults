#### Test 50650278dbf8a2a_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  901): acquireWL(43edcb78): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  901): releaseWL(43edcb78): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
I/SensorManager(  901): mEventCount = 900
D/CustomizationManager( 3857): ====startRecUseTime====
D/htc.customization.log.level( 3857):  is 
W/CustomizationLogLevel( 3857): Level value is invalid, use default level 2
D/CustomizationManager( 3857):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3857): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3857): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3857): Parsing tag category name = system
I/CustomizationCIDLoader( 3857): Parsing tag category name = application
I/CustomizationCIDLoader( 3857): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3857): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3857): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3857): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3857): Parsing tag category name = Settings
D/CustomizationManager( 3857):  Read CID file spent 0.098 (s)
D/CustomizationManager( 3857):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 3857): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3857): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3857): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3857): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  901): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  901): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  901): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  901): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  901): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  901): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3857
D/PMS     (  901): acquireHCC(44953d30): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 901 1000 null
D/PMS     (  901): acquireHCC(443e1ee8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 901 1000 null
W/asset   (  901): Copying FileAsset 0x64541700 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  901): @test_code: getHtcIntentFlag: 0 obj: 1147261416
D/PMS     (  901): acquireWL(44171140): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 901 1000 null
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42228ef0
I/SocialFeedProvider( 1246): +onPause
I/SocialFeedProvider( 1246): -onPause
E/cutils-trace( 3857): Error opening trace file: No such file or directory (2)
I/ActivityManager(  901): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3873 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1246): [trimMemory] 20
W/asset   ( 3873): Copying FileAsset 0x5c75c428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3873): Binding Chromium to main looper Looper (main, tid 1) {422042d8}
I/LibraryLoader( 3873): Expected native library version number "",actual native library version number ""
I/chromium( 3873): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3873): Initializing chromium process, renderers=0
D/PMS     (  901): acquireWL(43c0ddd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  901): acquireWL(43c0d860): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  901): java.lang.Throwable: stack dump
D/BluetoothManagerService(  901): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42adf0e0:true
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  901): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  901): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3873): 1109499152: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  901): releaseWL(43c0ddd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3873): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3873): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3873): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3873): Local Branch: 
I/Adreno-EGL( 3873): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3873): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3873):                  aa63bbd948f41d15fc72f585e
W/chromium( 3873): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3873): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3873): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3873): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3873): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3873): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3873): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3873): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3873): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3873): CordovaWebView is running on device made by: HTC
,W/AwContents( 3873): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  901): Disable input method client, pid=1246
,I/ActivityManager(  901): Displayed com.test.thalitest/.MainActivity: +249ms
,W/ResourceType( 3873): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3873): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4224b298, mServedView=org.apache.cordova.engine.SystemWebView{42211028 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 3873): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  901): Enable input method client, pid=3873
D/PMS     (  901): releaseWL(44171140): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3873): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3873): JniHelper::setJavaVM(0x41dc1010), pthread_self() = 1662414656
,D/JX-Cordova( 3873): jxcore cordova android initializing
,I/dalvikvm-heap( 3873): Grow heap (frag case) to 11.624MB for 144892-byte allocation
,I/dalvikvm-heap( 3873): Grow heap (frag case) to 11.739MB for 217334-byte allocation
,I/dalvikvm-heap( 3873): Grow heap (frag case) to 11.915MB for 325996-byte allocation
,I/dalvikvm-heap( 3873): Grow heap (frag case) to 12.189MB for 488990-byte allocation
,I/dalvikvm-heap( 3873): Grow heap (frag case) to 12.595MB for 733480-byte allocation
,I/dalvikvm-heap( 3873): Grow heap (frag case) to 14.042MB for 1650320-byte allocation
,I/dalvikvm-heap( 3873): Grow heap (frag case) to 15.454MB for 2475476-byte allocation
,I/dalvikvm-heap( 3873): Grow heap (frag case) to 17.510MB for 3713210-byte allocation
,W/jxcore-log( 3873): Initializing JXcore engine
,W/jxcore-log( 3873): JXcore engine is ready
,W/jxcore-log( 3873): Starting JXcore engine
,W/CpuWake (  901): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  901): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  901): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  901): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  901): >>release mCpuPerf_Freq wakelock
D/PMS     (  901): releaseHCC(44953d30): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  901): <<release mCpuPerf_Freq wakelock
,D/PMS     (  901): releaseHCC(443e1ee8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3873): Platform android
W/jxcore-log( 3873): 
,W/jxcore-log( 3873): Process ARCH arm
W/jxcore-log( 3873): 
,I/jxcore-log( 3873): JXcore Cordova bridge is ready!
I/jxcore-log( 3873): 
,W/jxcore-log( 3873): JXcore engine is started
,I/chromium( 3873): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  901): releaseWL(43c0d860): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  901): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3916 uid=10077 gids={50077}
D/PMS     (  901): acquireWL(4370be80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10077}
,V/AlarmManager(  901): sending alarm PendingIntent{42810948: PendingIntentRecord{42acab70 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450226374200, Int=60000
,D/PMS     (  901): releaseWL(4370be80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3916): SMSBackupAgentService started
,D/SMSBackup( 3916): Checking restore status
,D/SMSBackup( 3916): Restore complete
,D/SMSBackup( 3916): cancelCheckAlarm
,D/SMSBackup( 3916): SMSBackupAgentService completed: completed in 0.0 seconds
,I/ActivityManager(  901): Killing 3096:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  901): killProcessQuiet, pid=3096
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  901): Recipient 3096
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3873): Toggling radios to true
I/jxcore-log( 3873): 
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  901): checking for enable restriction...
,D/BluetoothManagerService(  901): checkBTEasState, ret=true
,I/BluetoothManagerService(  901): isBluetoothRestricted(): false
D/BluetoothManagerService(  901): enable(): region ID = 6
D/BluetoothManagerService(  901): enable():  mBluetooth =null mBinding = false
,W/HtcDLNAServiceManager(  901): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  901): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  901): Settings:Agentvalue: 1
W/Settings:Agent(  901): >> traceCallingStack()
,W/Settings:Agent(  901): Process.myPid(): 901
W/Settings:Agent(  901): Process.myTid(): 1258
W/Settings:Agent(  901): Process.myUid(): 1000
,W/Settings:Agent(  901): 
W/Settings:Agent(  901): 
,W/System.err(  901): java.lang.Throwable: stack dump
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  901): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  901): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  901): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  901): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  901): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  901): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  901): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  901): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  901): 
,W/Settings:Agent(  901): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  901): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  901): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3873): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/WifiService(  901): New client listening to asynchronous messages
D/WifiService(  901): setWifiEnabled: true pid=3873, uid=10348
E/WifiService(  901): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  901): isSprintWifiRestricted(): false
I/WifiService(  901): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  901): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  901): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  901): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  901): Settings:Agentvalue: 2
W/Settings:Agent(  901): >> traceCallingStack()
W/Settings:Agent(  901): Process.myPid(): 901
W/Settings:Agent(  901): Process.myTid(): 1100
W/Settings:Agent(  901): Process.myUid(): 1000
W/Settings:Agent(  901): 
W/Settings:Agent(  901): 
W/System.err(  901): java.lang.Throwable: stack dump
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  901): 	,at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  901): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  901): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  901): ,	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  901): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  901): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  901): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  901): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  901): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method),
W/Settings:Agent(  901): 
,W/Settings:Agent(  901): << traceCallingStack(): 1(ms)
I/ActivityManager(  901): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3931 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3873): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 3873): reconnect: Base Package Name=com.test.thalitest, uid=10348
,I/jxcore-log( 3873): Radios toggled
I/jxcore-log( 3873): 
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/PMS     (  901): acquireWL(42a7a090): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 901 1000 null
I/jxcore-log( 3873): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 3873): 
I/jxcore-log( 3873): Perf Test app loaded loaded
I/jxcore-log( 3873): 
I/jxcore-log( 3873): check test folder
I/jxcore-log( 3873): 
I/jxcore-log( 3873): found test : ./testFindPeers.js
I/jxcore-log( 3873): 
,D/AdapterServiceConfig( 3931): Adding HeadsetService
D/AdapterServiceConfig( 3931): Adding A2dpService
D/AdapterServiceConfig( 3931): Adding HidService
D/AdapterServiceConfig( 3931): Adding HealthService
D/AdapterServiceConfig( 3931): Adding PanService
,D/AdapterServiceConfig( 3931): Adding GattService
,I/jxcore-log( 3873): found test : ./testSendData.js
I/jxcore-log( 3873): 
,W/linker  ( 3931): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3931): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  901): java.lang.Throwable: stack dump
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  901): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  901): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  901): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42891680:true
,D/BluetoothAdapterState( 3931): make
,I/BluetoothAdapterState( 3931): Entering OffState
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3931): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  901): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  901): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  901): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  901): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  901): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapter( 3931): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@4221dae8
,D/BluetoothAdapter( 3931): onBluetoothServiceUp done
,D/BluetoothAdapter( 3873): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42d44d80
,D/BluetoothAdapter( 3873): onBluetoothServiceUp done
D/BluetoothAdapter(  901): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4288ed98
,D/BluetoothAdapter(  901): onBluetoothServiceUp done
D/BluetoothAdapter( 1230): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4233e1a0
,D/BluetoothAdapter( 1230): onBluetoothServiceUp done
D/BluetoothAdapter( 1217): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@422cea08
,D/BluetoothAdapter( 1217): onBluetoothServiceUp done
D/BluetoothAdapter( 1107): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4261d1e8
,D/BluetoothAdapter( 1107): onBluetoothServiceUp done
D/BluetoothAdapter( 1403): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42482ad8
,D/BluetoothAdapter( 1403): onBluetoothServiceUp done
D/BluetoothAdapter( 1751): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42816118
D/BluetoothAdapter( 1751): onBluetoothServiceUp done
,D/BluetoothManagerService(  901): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3931): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3931): Setting state to 11
I/BluetoothAdapterState( 3931): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3931): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  901): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  901): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  901): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  901): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3931): make
,I/BluetoothBondStateMachine( 3931): StableState(): Entering Off State
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/HeadsetService( 3931): Received start request. Starting profile...
D/HeadsetStateMachine( 3931): Version 1.6
,D/HeadsetStateMachine( 3931): make
,I/ActivityManager(  901): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3957 uid=10037 gids={50037, 3002, 3001}
,I/HeadsetStateMachine( 3931): setCurrentDevice, the latest mCurrentDevice is:null
,I/BluetoothAdapterState( 3931): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/A2dpService( 3931): Received start request. Starting profile...
V/Avrcp   ( 3931): make
,D/Avrcp   ( 3931): fillIntentFilter()
,D/A2dpStateMachine( 3931): make
,D/A2dpStateMachine( 3931): Enter Disconnected: -2
,D/HidService( 3931): Received start request. Starting profile...
D/HealthService( 3931): Received start request. Starting profile...
,I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/PanService( 3931): Received start request. Starting profile...
D/BluetoothTethering(  901): supplyMessenger
,D/BluetoothTethering(  901): supplyMessenger mAsyncChannel is null
D/PanService( 3931): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  901): got MESSAGE_CONNECT_PANSERVICE, call connect
,D/BluetoothTethering(  901): got CMD_CHANNEL_HALF_CONNECTED
,D/HtcBtWidget_BTWidgetProvider( 3957): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3957): updateWidget(context) for widget: 
,D/BtGatt.DebugUtils( 3931): handleDebugAction() action=null
D/BtGatt.GattService( 3931): Received start request. Starting profile...
,D/BtGatt.GattService( 3931): start()
V/BluetoothPbapService( 3931): Pbap Service onCreate
,V/BluetoothPbapService( 3931): Starting PBAP service
,D/Process (  901): killProcessQuiet, pid=3702
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 11
,D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 11
,I/ActivityManager(  901): Killing 3702:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
E/BluetoothMasService( 3931): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3931): Add permission for SmsProvider.
V/BluetoothMasService( 3931): Starting MAS instances
D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 11
I/MailMessageReceiver( 3931): reg:com.android.bluetooth.btservice.AdapterApp@42211050 with com.htc.util.mail.MailMessageReceiver@42251350
I/MailManager( 3931): MailManager contruct! com.htc.util.mail.MailMessageReceiver@42251350
V/EmailUtils( 3931): Manager Instance is not NULL
,I/Choreographer( 3873): Skipped 93 frames!  The application may be doing too much work on its main thread.
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  901): Client connection lost with reason: 4
I/ActivityManager(  901): Recipient 3702
,I/chromium( 3873): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/ActivityManager(  901): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3975 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  901): interfaceAdded wlan0
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
,D/Tethering(  901): wlan0 is not a tetherable iface, ignoring
D/Tethering(  901): interfaceLinkStateChanged wlan0, false
,D/Tethering(  901): interfaceStatusChanged wlan0, false
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
,D/Tethering(  901): interfaceAdded p2p0
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
,D/Tethering(  901): p2p0 is not a tetherable iface, ignoring
D/Tethering(  901): interfaceLinkStateChanged p2p0, false
D/Tethering(  901): interfaceStatusChanged p2p0, false
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
,D/PMS     (  901): releaseWL(42a7a090): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  901): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 3931): ============NULL aList========
,V/EmailUtils( 3931): <-getEmailAccountIdList
,V/BluetoothMasService( 3931): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 11
V/BluetoothMasService( 3931): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3931): Manager Instance is not NULL
D/EmailUtils( 3931): ============NULL aList========
,V/EmailUtils( 3931): <-getEmailAccountIdList
,D/HeadsetPhoneState( 3931): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
V/BluetoothSapService( 3931): Sap Service onCreate
V/BluetoothSapService( 3931): initBinder
V/BluetoothSapService( 3931): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@42257a38
,V/BluetoothSapReceiver( 3931): BluetoothSapReceiver init
,D/BluetoothSapService( 3931): setSapService()
V/BluetoothSapService( 3931): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3931): state: 12
D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 11
D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 3931): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothAdapterService( 3931): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3931): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/BluetoothTethering(  901): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  901): killProcessQuiet, pid=3390
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  901): Killing 3390:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/BluetoothMasReceiver( 3931): Bluetooth STATE CHANGED to 11
I/ActivityManager(  901): Recipient 3390
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  901): Client com.google.android.music (pid 3390): Died!
,I/qcom-bluetooth( 3994): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  901): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3995 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4012): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
I/qcom-bluetooth( 4013): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3995): Received state change = 11
I/qcom-bluetooth( 4015): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 4016): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 4017): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 4019): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  901): New client listening to asynchronous messages
,D/Process (  901): killProcessQuiet, pid=3373
,I/ActivityManager(  901): Killing 3373:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  901): Recipient 3373
,I/wpa_supplicant( 4023): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4023): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4023): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4023): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4023): Get randomness: len=20 entropy=1
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
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4023): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4023): nl80211: RFKILL status not available
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
D/wpa_supplicant( 4023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb808c758
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb808c758
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4023): htc_wext_command_init +
E/wpa_supplicant( 4023): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4023): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4023): nl80211: Use Multi channel concurrency
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
D/Tethering(  901): interfaceLinkStateChanged p2p0, false
D/Tethering(  901): interfaceStatusChanged p2p0, false
D/Tethering(  901): [isWifi] getHotspotEnabled: false
D/Tethering(  901): interfaceLinkStateChanged p2p0, false
D/Tethering(  901): interfaceStatusChanged p2p0, false
D/Tethering(  901): [isWifi] getHotsp,otEnabled: false
,D/WifiMonitor(  901): startMonitoring(wlan0) with mConnected = false
D/WifiDataStallTracker(  901): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  901): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  901): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4024 uid=10048 gids={50048}
,I/wpa_supplicant( 4023): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4023):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4023):  Initialization: WAPI: Initializing WAPI Supplicant
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
,I/wpa_supplicant( 4023): State: DISCONNECTED -> INACTIVE
,I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/HtcWiFiWidget_WiFiWidgetProvider( 4024): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4024): updateWidget(context) for widget: 
,D/Process (  901): killProcessQuiet, pid=3731
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  901): Killing 3731:com.htc.calendar/u0a13 (adj 15): empty #17
,I/qcom-bluetooth( 4036): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/qcom-bluetooth( 4037): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 4023): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4023): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4023): WPS: Set UUID for interface p2p0
,I/bt-btu  ( 3931): btu_task pending for preload complete event
D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
,D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4023): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18,
,D/wpa_supplicant( 4023): Using existing control interface directory.,
D/wpa_supplicant( 4023): ctrl_iface bind(PF_UNIX) failed: Address already in use
,D/wpa_supplicant( 4023): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4023): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
,D/wpa_supplicant( 4023): P2P: Own listen channel: 6
D/wpa_supplicant( 4023): P2P: Configured operating channel: 126:36,
,D/wpa_supplicant( 4023): P2P: Add operating class 81,
,I/wpa_supplicant( 4023): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4023): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4023): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4023): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4023): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4023): disable_scan_offload=1
D/wpa_supplicant( 4023): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4023): update_config=1
D/wpa_supplicant( 4023): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4023): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4023): manufacturer='HTC'
D/wpa_supplicant( 4023): model_name='HTC Desire 820'
D/wpa_supplicant( 4023): model_number='HTC Desire 820'
,D/wpa_supplicant( 4023): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4023): persistent_reconnect=1
D/wpa_supplicant( 4023): p2p_disabled=1
D/wpa_supplicant( 4023): hs20=1
D/wpa_supplicant( 4023): interworking=1
D/wpa_supplicant( 4023): Line: 18 - start of a new network block
D/wpa_supplicant( 4023): key_mgmt: 0x2
D/wpa_supplicant( 4023): priority=1 (0x1)
,D/wpa_supplicant( 4023): signinfail=0 (0x0),
,I/ActivityManager(  901): Recipient 3731
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
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
D/wpa_supplicant( 4023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb809c718
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
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
,D/wpa_supplicant( 4023): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4023): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4023): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  901): interfaceLinkStateChanged wlan0, false
,D/Tethering(  901): interfaceStatusChanged wlan0, false
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 4023): wapi_supplicant_init: Init WAI packet wlan0
,D/wpa_supplicant( 4023):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4023):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 4023):  Initialization: WAPI:set Staues=1 
,D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4023): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4023): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4023): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4023): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4023): TDLS: Driver uses external link setup
D/wpa_supplicant( 4023): WPS: Set UUID for interface wlan0
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
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4023): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4023): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4023): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4023): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_901-2
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
D/WifiNative-wlan0(  901): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4023): set wifi ON
,D/WifiNative-wlan0(  901):    returned true
V/RegulatoryObserver(  901): uevent:
V/RegulatoryObserver(  901): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4421, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  901): Regulatory Country Code:DE
V/RegulatoryObserver(  901): Start wifi-crda service to run crda.
V/RegulatoryObserver(  901): Country Code is DE
V/RegulatoryObserver(  901): Send broadcast country code message.
I/RegulatoryObserver(  901): Broadcast intent for crda country code: DE
,D/WifiNative-wlan0(  901): doString: DRIVER MACADDR
D/WifiDataStallTracker(  901): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  901): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/WifiConfigStore(  901): Loading config and enabling all networks
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiNative-wlan0(  901): doString: LIST_NETWORKS
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): list_network_info: ret=0x1, pos=0xb809f117 buf=0xb809f0e8
I/wpa_supplicant( 4023): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4023): 0	NG700	any	
D/WifiNative-wlan0(  901):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  901): 0	NG700	any	
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 ssid
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/HtcWiFiWidget_WiFiWidgetProvider( 4024): onWiFiStateChanged() for widget: 
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 bssid
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 priority,
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wep_tx_keyidx
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/HtcWiFiWidget_WiFiWidgetProvider( 4024): updateWidget(context) for widget: 
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wep_key1
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
,D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
,D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
,D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 psk
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4023): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 proto
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  901): Failed to look-up a string: W
,D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 pairwise
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  901): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 group
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  901): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
,D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_psk'
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  901): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  901): ***WAPI : readNetworkVariables WAPI_PSK_HEX key,
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  901): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
,D/WifiConfigStore(  901): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  901): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 limited
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 eap
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'eap'
I/wpa_supplicant( 4023): wpa_supplicant_scan enter
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
,I/wpa_supplicant( 4023): State: DISCONNECTED -> SCANNING
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 phase2
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4023): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4023): wpa_supplicant_trigger_scan +
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 4023): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'phase2'
D/wpa_supplicant( 4023): nl80211: Event message available
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 4023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 identity
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 password
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
,D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 engine
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 key_id
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  901): doString: GET_NETWORK 0 private_key
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4023): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  901): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  901): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4023): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4023): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SET manufacturer HTC
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'manufacturer'='HTC'
,D/wpa_supplicant( 4023): manufacturer='HTC'
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4023): model_name='HTC Desire 820'
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4023): model_number='HTC Desire 820'
D/WifiNative-wlan0(  901):    returned true
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SET config_methods physical_display virtual_push_button
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4023): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SET auto_interworking 0
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'auto_interworking'='0'
,D/wpa_supplicant( 4023): auto_interworking=0
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  901):    returned true
,D/WifiNative-wlan0(  901): doBoolean: RECONNECT
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doString: STATUS
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  901): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): SET_SCREEN_ON:On
I/wpa_supplicant( 4023): htc_wext_set_keepalive +
I/wpa_supplicant( 4023): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4023): getPrivFuncNum +	
I/wpa_supplicant( 4023): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SET ps 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  901):    returned true
I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiP2pService(  901): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  901): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-wlan0(  901): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): SETBAND: 0
D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4023): P2P: Add operating class 81
D/wpa_supplicant( 4023): P2P: Add operating class 115
,D/wpa_supplicant( 4023): P2P: Add operating class 116
D/wpa_supplicant( 4023): P2P: Add operating class 117
D/wpa_supplicant( 4023): P2P: Update channel list
I/wpa_supplicant( 4023): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4023): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4023): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4023): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4023): p2p_oper_reg_class=126
D/wpa_supplicant( 4023): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4023): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 4023): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4023): CTRL_IFACE SET 'p2p_oper_channel'='36'
,D/wpa_supplicant( 4023): p2p_oper_channel=36
E/wpa_supplicant( 4023): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4023): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4023): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4023): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4023): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: BSS_FLUSH 0
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: SCAN
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  901):    returned false
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  901): doBoolean: SET pno 0
,D/libc    (  901): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  901): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4023): wpa_supplicant_scan enter
D/WifiNative-wlan0(  901):    returned true
D/WifiMonitor(  901): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  901): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiNative-p2p0(  901): doBoolean: SET persistent_reconnect 1
,W/WifiHW  (  901): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4023): persistent_reconnect=1
I/wpa_supplicant( 4023): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  901):    returned true
D/WifiNative-p2p0(  901): doBoolean: SET device_name Android_63cc
W/WifiHW  (  901): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 4023): device_name='Android_63cc'
I/wpa_supplicant( 4023): Recv Cmd 2: SET device_name=Android_63cc
,D/WifiNative-p2p0(  901):    returned true
D/WifiNative-p2p0(  901): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  901): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 4023): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4023): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 4023): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiP2pService(  901): P2pEnablingState
D/WifiP2pService(  901): P2pEnablingState{ when=-3ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2p socket connection successful
D/WifiP2pService(  901): P2pEnabledState
D/WifiP2pService(  901): sending p2p connection changed broadcast
,D/WifiDisplayController(  901): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  901): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  901): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  901): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiNative-p2p0(  901):    returned true
D/WifiNative-p2p0(  901): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  901): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4023): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  901):    returned true
,D/WifiNative-p2p0(  901): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  901): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4023): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4023): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  901):    returned true
D/WifiNative-p2p0(  901): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  901): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4023): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4023): Single channel concurrency preference: sta
,I/wpa_supplicant( 4023): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  901):    returned true
D/WifiNative-p2p0(  901): doString: STATUS
W/WifiHW  (  901): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  901): doBoolean: P2P_FLUSH
W/WifiHW  (  901): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4023): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4023): P2P: Stopping find
D/wpa_supplicant( 4023): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4023): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4023): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  901):    returned true
D/WifiNative-p2p0(  901): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  901): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4023): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4023): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  901):    returned true
D/WifiNative-p2p0(  901): doString: LIST_NETWORKS
W/WifiHW  (  901): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4023): list_network_info: ret=0x22, pos=0xb809f10a buf=0xb809f0e8
I/wpa_supplicant( 4023): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4023): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  901):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  901): doBoolean: AP_SCAN 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  901):    returned false
D/WifiNative-p2p0(  901): doBoolean: SET wifi_display 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4023): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4023): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4023): WFD: Update WFD IE
I/wpa_supplicant( 4023): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4023): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  901):    returned true
D/WifiNative-p2p0(  901): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  901): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4023): WFD: Set subelement 0
D/wpa_supplicant( 4023): WFD: Update WFD IE
I/wpa_supplicant( 4023): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4023): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  901):    returned true
D/WifiP2pService(  901): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  901): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  901):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  901):  primary type: 10-0050F204-5
D/WifiDisplayController(  901):  secondary type: null
D/WifiDisplayController(  901):  wps: 0
D/WifiDisplayController(  901):  grpcapab: 0
D/WifiDisplayController(  901):  devcapab: 0
D/WifiDisplayController(  901):  status: 3
D/WifiDisplayController(  901):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  901):  WFD CtrlPort: 0
D/WifiDisplayController(  901):  WFD MaxThroughput: 0
D/WifiP2pService(  901): sending p2p persistent groups changed broadcast
D/WifiP2pService(  901): InactiveState
D/WifiP2pService(  901): InactiveState{ when=-9ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  901):  WFD CtrlPort: 7236
D/WifiP2pService(  901):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-9ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  901):  WFD CtrlPort: 7236
D/WifiP2pService(  901):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  901): Successfully set WFD info.
I/WifiDisplayController(  901): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
,D/WifiDisplayController(  901): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  901):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  901):  primary type: 10-0050F204-5
D/WifiDisplayController(  901):  secondary type: null
D/WifiDisplayController(  901):  wps: 0
D/WifiDisplayController(  901):  grpcapab: 0
D/WifiDisplayController(  901):  devcapab: 0
D/WifiDisplayController(  901):  status: 3
D/WifiDisplayController(  901):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  901):  WFD CtrlPort: 7236
D/WifiDisplayController(  901):  WFD MaxThroughput: 50
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  901):     Client/Owner: Client
D/WifiDisplayAdapter(  901):     GroupId: 
D/WifiDisplayAdapter(  901):     Passphrase: 
D/WifiDisplayAdapter(  901):     SessionId: 0
D/WifiDisplayAdapter(  901):     IP Address: }
V/AudioService(  901): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  901):     Client/Owner: Client
V/AudioService(  901):     GroupId: 
V/AudioService(  901):     Passphrase: 
V/AudioService(  901):     SessionId: 0
V/AudioService(  901):     IP Address: }
D/HtcEffectManagerBase(  901): onEventChanged id=5 status=false
D/HtcEffectManager(  901): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  901): convertEffect before=902
D/HtcEffectManager(  901): convertEffect after=902
,D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/Tethering(  901): interfaceLinkStateChanged p2p0, false
,D/Tethering(  901): interfaceStatusChanged p2p0, false
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4023): nl80211: Event message available
D/wpa_supplicant( 4023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 4023): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4023): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 4023): nl80211: Survey data missing
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4023): Sorted scan results
I/wpa_supplicant( 4023): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 4023): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4023): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4023): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 4023): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 4023): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 4023): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 4023): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4023): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4023): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4023): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4023): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4023): Add randomness: count=7 entropy=5
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4023): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 4023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4023): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4023): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4023): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4023): wpa_supplicant_pick_network+
I/wpa_supplicant( 4023): Selecting BSS from priority group 1
I/wpa_supplicant( 4023): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4023): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
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
I/wpa_supplicant( 4023): wpa_s->bt_sco_status, is 0
I/wpa_supplicant( 4023): wpa_s->reassociate is 0
I/wpa_supplicant( 4023): wpa_s->is_screen_on 1
I/wpa_supplicant( 4023): wpa_s->ifname wlan0
I/wpa_supplicant( 4023): End print parameters
I/wpa_supplicant( 4023): selected network = 2
D/wpa_supplicant( 4023): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb809d4e8  current_ssid=0x0
D/wpa_supplicant( 4023): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4023): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4023): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4023): check if in concurrent case
I/wpa_supplicant( 4023): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4023): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4023): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4023): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4023): RSN: PMKSA cache search - network_ctx=0xb809d4e8 try_opportunistic=0
D/wpa_supplicant( 4023): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4023): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4023): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4023): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4023): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4023): nl80211: Unsubscribe mgmt frames handle 0xb809c718 (mode change)
D/wpa_supplicant( 4023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb809c718
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Register frame type=0xd0 nl_handle=0xb809c718
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4023): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4023):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4023):   * freq=2412
,D/wpa_supplicant( 4023):   * Auth Type 0
,D/wpa_supplicant( 4023):   * WPA Versions 0x2
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4023): nl80211: Connect request send successfully
D/wpa_supplicant( 4023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): RSN: Ignored PMKID candidate without preauth flag
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 4023): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4023): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4023): reply (778) for get BSS: id=0
I/wpa_supplicant( 4023): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4023): freq=5220
I/wpa_supplicant( 4023): level=-51
I/wpa_supplicant( 4023): tsf=0000000105482186
I/wpa_supplicant( 4023): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4023): ssid=NG7005g
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=1
I/wpa_supplicant( 4023): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): freq=2412,
I/wpa_supplicant( 4023): level=-50
I/wpa_supplicant( 4023): tsf=0000000105482152
I/wpa_supplicant( 4023): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4023): ssid=01ABC
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=2
I/wpa_supplicant( 4023): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): freq=2412
I/wpa_supplicant( 4023): level=-50
I/wpa_supplicant( 4023): tsf=0000000105482173
I/wpa_supplicant( 4023): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 4023): ssid=NG700
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=3
I/wpa_supplicant( 4023): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 4023): freq=2437
I/wpa_supplicant( 4023): level=-79
I/wpa_supplicant( 4023): tsf=0000000105482199
I/wpa_supplicant( 4023): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 4023): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=4
I/wpa_supplicant( 4023): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4023): freq=2427
,I/wpa_supplicant( 4023): level=-81
I/wpa_supplicant( 4023): tsf=0000000105482210
I/wpa_supplicant( 4023): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4023): ssid=Gonzos
I/wpa_supplicant( 4023): ====
I/wpa_supplicant( 4023): id=5
I/wpa_supplicant( 4023): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 4023): freq=2437
I/wpa_supplicant( 4023): level=-88
I/wpa_supplicant( 4023): tsf=0000000105482220
I/wpa_supplicant( 4023): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4023): ssid=UPC4688432
I/wpa_supplicant( 4023): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 105482186, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 105482152, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 105482173, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 105482199, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (6) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 105482210, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 105482220, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 6 to mScanResults
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/bt-btu  ( 3931): btu_task received preload complete event
D/wpa_supplicant( 4023): EAPOL: disable timer tick
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/bt-btm  ( 3931): btm_acl_device_down
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
D/bt-btm  ( 3931): btm_read_white_list_size_complete 
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
E/bt-btm  ( 3931): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fa1941 
I/bt-btm  ( 3931): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3931): SMP_Register state=0
E/bt-btm  ( 3931): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fa1941 
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
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3931): BTM_AllocateSCN
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3931): BTM_AllocateSCN
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3931):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3931):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3931):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
,I/bt-btm  ( 3931):                : sec: 0x1086, service name [] (up to 21 chars saved)
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
E/bt-btif ( 3931): Write Extended Inqui
E/bt-btif ( 3931): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3931): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:2 len:6
I/bt-btm  ( 3931): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 3931): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
D/BluetoothAdapterProperties( 3931): Address is:80:01:84:8A:B3:68
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:1 len:14
I/bt-btm  ( 3931): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
,I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3931): Scan Mode:20
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:9 len:4
I/bt-btm  ( 3931): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3931):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 3931): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3931): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 3931): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3931): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 3931): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3931): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3931): BTM_GetHCIConnHandle
I/bt-btm  ( 3931): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
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
D/BluetoothAdapterProperties( 3931): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:8 len:36
D/BluetoothAdapter( 3931): getBluetoothService(): entry
D/BluetoothAdapter( 3931): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3931): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@422615f8
,D/BluetoothDevice( 3931): getService : Register callback
,D/BluetoothAdapterProperties( 3931): Adding bonded device:B4:CE:F6:AB:A4:6A
,D/BluetoothAdapterProperties( 3931): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 3931): Adding bonded device:34:FC:EF:9D:93:0B
,D/BluetoothAdapterProperties( 3931): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 3931): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3931): Adding bonded device:58:2A:F7:ED:96:BE
,I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3931): Remote class is:5898764
,I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 3931): Remote class is:5898764
,I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BluetoothRemoteDevices( 3931): Remote class is:5898764
,I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BluetoothRemoteDevices( 3931): Remote class is:5898764
,I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 3931): Remote class is:5898764
,I/bt-btif ( 3931): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3931): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothRemoteDevices( 3931): Remote class is:5898764
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4023): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 4023): Add randomness: count=8 entropy=6
I/wpa_supplicant( 4023): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4023): TDLS: Remove peers on association
D/wpa_supplicant( 4023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4023): htc_wext_set_keepalive +
I/wpa_supplicant( 4023): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4023): getPrivFuncNum +	
I/wpa_supplicant( 4023): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive fnum = 0x8bf6
I/bt-btif ( 3931): BTA_JvEnable
I/wpa_supplicant( 4023): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4023): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4023): Get randomness: len=32 entropy=7
D/Tethering(  901): interfaceLinkStateChanged wlan0, false
,D/Tethering(  901): interfaceStatusChanged wlan0, false
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
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
I/bt-btm  ( 3931): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373,
I/bt-btm  ( 3931):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3931): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
,I/bt-btm  ( 3931):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  901): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  901): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/bt_mct  ( 3931): hci lib postload completed
D/HTCRequest(  901): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  901): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  901): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  901): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  901): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  901): Enter handleAssociatedWithEvent
D/WifiStateMachine(  901): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  901): Associated
D/WifiStateMachine(  901): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  901): Exit handleAssociatedWithEvent
D/WifiStateMachine(  901): BSSID was changed, update WiFi database
D/Tethering(  901): interfaceLinkStateChanged wlan0, true
D/Tethering(  901): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  901): updateConnectedAP...
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 4023): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb809c9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4023):    addr=c0:ff:d4:d3:aa:48
I/bt-btif ( 3931): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 3931): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3931): ScanMode =  20
D/BluetoothAdapterProperties( 3931): State =  11
D/WifiApDatabaseHandler(  901): updateConnectedAP...
I/bt-btif ( 3931): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3931): Setting state to 12
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:7 len:4
,I/BluetoothAdapterState( 3931): Bluetooth adapter state changed: 11-> 12
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 11
D/BluetoothAdapterService( 3931): Broadcasting updateAdapterState() to 1 receivers.
D/WifiStateMachine(  901): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4023): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4023): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f7bb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/BluetoothManagerService(  901): +onBluetoothStateChange prev=11 new=12
D/wpa_supplicant( 4023):    broadcast key
D/BluetoothManagerService(  901): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  901): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/BluetoothManagerService(  901): Broadcasting onBluetoothStateChange(true) to 6 receivers.
E/wpa_supplicant( 4023): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4023): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/BluetoothHeadset( 1107): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3931): Entering On State
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4023): wlan0: Connect to SSID: NG700
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 4023): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4023): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  901): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4023): set send_ind_to_ndc = 0
,D/BluetoothAdapterProperties( 3931): Scan Mode:21
D/BluetoothAdapterService(1109503864)( 3931): Get Bonded Devices being called
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING (1)+
I/bt-btif ( 3931): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3931): getBondedDevices: length=6
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4023): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4023): EAP: EAP entering state DISABLED
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 4023): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4023): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4023): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/BluetoothAdapterProperties( 3931): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3931): Discoverable Timeout:120
I/bt-btm  ( 3931): BTM_SetDiscoverability
,I/bt-btm  ( 3931): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4023): EAPOL authentication completed successfully
I/wpa_supplicant( 4023): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/bt-btm  ( 3931): btm_ble_set_discoverability (BREDR not sup)flag=0x4
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 79
D/bt-btm  ( 3931): br_edr_supported=0x0
I/bt-btm  ( 3931): mode == BTM_BLE_NON_DISCOVERABLE 
D/wpa_supplicant( 4023): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,I/bt-btm  ( 3931): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3931): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3931): btm_ble_update_adv_flag old=0x4
D/wpa_supplicant( 4023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
I/bt-btm  ( 3931): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3931): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3931): BTM_SetConnectability
I/bt-btm  ( 3931): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3931): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3931): btm_ble_update_adv_flag new=0x0
,D/bt-btm  ( 3931): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3931): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3931): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/wpa_supplicant( 4023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  901): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/BluetoothHeadset( 1217): onBluetoothStateChange: up=true
D/Tethering(  901): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  901): This record is existed, only update it...
,D/Tethering(  901): interfaceStatusChanged wlan0, true
,D/BluetoothHeadset( 1107): Proxy object connected
D/Tethering(  901): [isWifi] getHotspotEnabled: false
I/QuickSettingMiniLite( 1107): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@42519e28
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/BluetoothPan(  901): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1217): Proxy object connected
D/WifiApDatabaseHandler(  901): updateConnectedAP...
,D/BluetoothHeadset( 1217): onBluetoothStateChange: up=true
,D/BluetoothPan(  901): BluetoothPAN Proxy object connected
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset( 1217): Proxy object connected
D/BluetoothPhoneService( 1217): BluetoothHeadset onServiceConnected
D/BluetoothHeadset(  901): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1217): 1110669928: getState(). Returning 12
,D/BluetoothA2dp(  901): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1109503864)( 3931): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3931): getBondedDevices: length=6
,D/BluetoothManagerService(  901): Bluetooth State Change Intent: 11 -> 12
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/WifiApDatabaseHandler(  901): updateConnectedAP...
D/BluetoothHeadset(  901): Proxy object connected
D/BluetoothAdapter(  901): 1119008272: getState(). Returning 12
V/BluetoothPbapReceiver( 3931): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3931): ***********state = 12
,D/BluetoothMasReceiver( 3931): Bluetooth STATE CHANGED to 12
,D/BluetoothA2dp(  901): Proxy object connected
D/PMS     (  901): acquireWL(42c776b8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3325 1000 null
,V/BluetoothSapReceiver( 3931): SapReceiver onReceive 
V/BluetoothSapReceiver( 3931): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 3931):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 3931): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 12
D/BluetoothAdapter(  901): 1119008272: getState(). Returning 12
,D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 12
V/BluetoothMasService( 3931): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3931): Manager Instance is not NULL
,D/HtcBtWidget_BTWidgetProvider( 3957): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3957): updateWidget(context) for widget: 
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  901): releaseWL(42c776b8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  901): acquireWL(4467afe0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3325 1000 null
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  901): java.lang.Throwable: stack dump
D/BluetoothManagerService(  901): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4386f1d0:true
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  901): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  901): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3325): new LocationAgent instance!!
D/HtcTagManager( 3325): HtcTagManager construction complete
D/WifiStateMachine(  901): fetchFrequency(), freq = 2412
D/WifiStateMachine(  901): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/BluetoothManagerService(  901): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/WifiDataStallTracker(  901): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  901): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/BluetoothManagerService(  901): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  901): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/WifiStateMachine(  901): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiStateTracker(  901): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  901): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  901): Provision feature enable=false
D/ConnectivityService(  901): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
D/EmailUtils( 3931): ============NULL aList========
V/EmailUtils( 3931): <-getEmailAccountIdList
V/BluetoothSapService( 3931): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3931): state: 12
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 12
D/WifiApDatabaseHandler(  901): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  901): This record is existed, only update it...
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
W/ContextImpl( 3931): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/WifiApDatabaseHandler(  901): updateConnectedAP...
V/BluetoothSapService( 3931): Starting SAP server process
D/BluetoothInputDevice( 3325): BluetoothInputDevice()
V/BluetoothPbapService( 3931): Handler(): got msg=1
D/BluetoothManagerService(  901): registerStateChangeCallback+
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  901): Registered receivers: 7
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
,D/BluetoothInputDevice( 3325): BluetoothInputDevice(): Binding service...
,D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
V/BluetoothPbapService( 3931): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3931): Pbap Service initSocket
,V/BluetoothMasService( 3931): handleMessage: mIsEmailEnabledtrue
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BtMns   ( 3931): BluetoothMns: isEmailEnabled: true
,D/BluetoothPan( 3325): BluetoothPan()
,D/BluetoothManagerService(  901): registerStateChangeCallback+
D/BluetoothAdapter( 3931): getBluetoothService(): entry
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  901): Registered receivers: 8
W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMasService( 3931): Map_prev 1
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
,D/BluetoothPan( 3325): BluetoothPan(): Binding service...
E/BluetoothServiceJni( 3931): SOCK FLAG = 1 ***********************
,I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
,I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3931):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3931): Succeed to create listening socket 
,V/BluetoothPbapService( 3931): Accepting socket connection...
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothAdapter( 3931): getBluetoothService(): entry
W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMap( 3325): Create BluetoothMap proxy object
E/BluetoothServiceJni( 3931): SOCK FLAG = 3 ***********************
D/BluetoothManagerService(  901): registerStateChangeCallback+
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:12
D/BluetoothManagerService(  901): Registered receivers: 9
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
E/BluetoothMap( 3325): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3931):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  901): registerStateChangeCallback+
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  901): Registered receivers: 10
,D/BluetoothSap( 3325): BluetoothSap() call bindService
D/BluetoothAdapter( 1107): 1112212968: getState(). Returning 12
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3931): getBluetoothService(): entry
,W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3931): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3931):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  901): updateConnectedAP...
D/BluetoothAdapter( 1107): 1112212968: getState(). Returning 12
D/BluetoothPbap( 3325): BluetoothPbap()
D/BluetoothManagerService(  901): registerStateChangeCallback+
I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1107): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
,D/BluetoothPbap( 3325): BluetoothPbap(): Binding service...
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  901): Registered receivers: 11
,D/BluetoothA2dp( 3325): BluetoothA2dp()
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService(  901): registerStateChangeCallback+
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  901): Registered receivers: 12
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
,D/BluetoothA2dp( 3325): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3325): BluetoothHeadset()
D/BluetoothManagerService(  901): registerStateChangeCallback+
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  901): Registered receivers: 13
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
I/QuickSettingWifi( 1107): receive.wifiConnect:false wifiAPname:null elapse:1
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
D/BluetoothHeadset( 3325): BluetoothHeadset(): Binding service...
D/BluetoothSapService( 3931): Sap_prev 1
D/DhcpStateMachine(  901): [StoppedState] Start DHCP
V/BluetoothSapService( 3931): SAP Service startRfcommListenerThread
V/BluetoothSapService( 3931): Sap Service initRfcommSocket
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/TAG     ( 3931): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 3931): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@42259310
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/HtcTagManager( 3325): startProxy
D/BluetoothAdapter( 3931): getBluetoothService(): entry
,W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,D/BluetoothAdapter( 1107): 1112212968: getState(). Returning 12
E/BluetoothServiceJni( 3931): SOCK FLAG = 3 ***********************
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3931):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): WiFioffload: SignalStrength: =97
V/BluetoothSapService( 3931): Succeed to create listening socket 
,V/BluetoothSapService( 3931): Accepting socket connection...
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  901): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/QuickSettingMiniLite( 1107): updateLiteState:no connect device!
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4023): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: DRIVER BTCOEXMODE 1
,W/ContextImpl( 3325): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/LocalBluetoothProfileManager( 3325): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3325): finishStartingService: stopping service
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  901): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  901): acquireWL(43c60c00): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 901 1000 null
D/WifiStateMachine(  901): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WISPrService( 3325): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothPan( 3325): BluetoothPAN Proxy object connected
D/PanProfile( 3325): Bluetooth service connected
D/BluetoothA2dp( 3325): Proxy object connected
D/A2dpProfile( 3325): Bluetooth service connected
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): Power_Mode_Type mode = 1
I/wpa_supplicant( 4023): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 61
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  901):    returned null
E/WifiStateMachine(  901): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  901): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  901):    returned null
,D/WifiStateMachine(  901): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiService(  901): New client listening to asynchronous messages
D/WifiP2pService(  901): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@446ab290 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@446ab290 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothPbapService( 3931): Pbap Service onBind
D/BluetoothInputDevice( 3325): Proxy object connected
D/WISPrService( 3325): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/HidProfile( 3325): Bluetooth service connected
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
D/BluetoothHeadset( 3325): Proxy object connected
D/HeadsetProfile( 3325): Bluetooth service connected
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3995): onCreate: going to find gatt base service first.
D/BluetoothAdapter( 3325): 1111079096: getState(). Returning 12
,D/SapServerProfile( 3325): Bluetooth service connected
D/BluetoothPbap( 3325): Proxy object connected
,D/PbapServerProfile( 3325): Bluetooth service connected
,D/PMS     (  901): releaseWL(4467afe0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
I/BluetoothFtpService( 3931): Ftp Service onCreate
D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 12
D/BluetoothMasReceiver( 3931): Bluetooth STATE CHANGED to 12
D/BluetoothFtpService( 3931): Ftp_prev 1
D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/System.err(  901): java.lang.Throwable: stack dump
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  901): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d12530:true
D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  901): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  901): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3931): getBluetoothService(): entry
W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3931): SOCK FLAG = 0 ***********************
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
D/BluetoothAdapter( 3931): getBluetoothService(): entry
W/BluetoothAdapter( 3931): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3931):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3931): Accept thread started.
E/BluetoothServiceJni( 3931): SOCK FLAG = 1 ***********************
I/bt-btif ( 3931): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3931): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3931): Write Extended Inquiry Response to controller
I/bt-btif ( 3931): BTA_JvRfcommStartServer
I/bt-btm  ( 3931): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3931):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3931): Run Accept thread
D/BluetoothAdapter( 3931): 1109522040: getState(). Returning 12
V/BluetoothMasService( 3931): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3931): Manager Instance is not NULL
D/[HTC_BLE][Constants]( 3995):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3995):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3995):  + discoverServicesOnBonded = false
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3995):  + Google LE service found. Using BaseLeProfilesGoogle.
D/EmailUtils( 3931): ============NULL aList========
,V/EmailUtils( 3931): <-getEmailAccountIdList
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3995): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@42220ec8
D/[HTC_BLE][Constants]( 3995): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3995): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3995): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3995): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3995): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
D/[HTC_BLE][Constants]( 3995): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,D/BluetoothMasService( 3931): Map_prev 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3995): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3325): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3995): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3995): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3995): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@42220ec8
D/HtcTagProfile( 3325): setup proxy
D/HtcPxpProfile( 3325): setup proxy
D/HtcFmpProfile( 3325): setup proxy
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3995): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@42220ec8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3995): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@42220ec8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@4222beb0
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3995): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@42220ec8
,W/System.err(  901): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  901): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@438ec7d0:true
,W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  901): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  901): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3746): new LocationAgent instance!!
,D/HtcTagManager( 3746): HtcTagManager construction complete
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/BluetoothInputDevice( 3746): BluetoothInputDevice()
D/RingtoneManager( 3995): getExternalStorageState=mounted
,D/BluetoothManagerService(  901): registerStateChangeCallback+
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  901): Registered receivers: 14
D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/BluetoothInputDevice( 3746): BluetoothInputDevice(): Binding service...
D/wpa_supplicant( 4023): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4023): EAPOL: disable timer tick
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[-1]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[1]: Daisy
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[2]: Feverfew
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3995):  + mAlertUri: content://settings/system/alarm_alert
,D/BluetoothPan( 3746): BluetoothPan()
,D/BluetoothManagerService(  901): registerStateChangeCallback+
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  901): Registered receivers: 15
D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/BluetoothPan( 3746): BluetoothPan(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3995): BleProfilesStateMachine is initialized...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3995): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3995): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3995): initScanModeInterface: true
,W/System.err(  901): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothMap( 3746): Create BluetoothMap proxy object
D/BluetoothManagerService(  901): registerStateChangeCallback+
,D/BluetoothManagerService(  901): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43efd7d0:true
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
,D/BluetoothManagerService(  901): Registered receivers: 16
,W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
W/System.err(  901): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  901): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3995): loadDeviceConfiguration() init =true
E/BluetoothMap( 3746): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3995):  + mTag.getPrimaryDeviceList() = []
D/BluetoothManagerService(  901): registerStateChangeCallback+
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3746): BluetoothSap() call bindService
D/BluetoothManagerService(  901): Registered receivers: 17
D/[HTC_BLE][Constants]( 3995):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3995):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 3995):  + discoverServicesOnBonded = false
,D/BluetoothPbap( 3746): BluetoothPbap()
,D/BluetoothManagerService(  901): registerStateChangeCallback+
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  901): Registered receivers: 18
D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/BluetoothPbap( 3746): BluetoothPbap(): Binding service...
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothA2dp( 3746): BluetoothA2dp()
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3995): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@4222beb0
D/BluetoothManagerService(  901): registerStateChangeCallback+
,D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  901): Registered receivers: 19
D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/BluetoothA2dp( 3746): BluetoothA2dp(): Binding service...
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,D/BluetoothHeadset( 3746): BluetoothHeadset()
,D/BluetoothManagerService(  901): registerStateChangeCallback+
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  901): Registered receivers: 20
D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/BluetoothHeadset( 3746): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3746): startProxy
,W/ContextImpl( 3746): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3746): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
D/LocalBluetoothProfileManager( 3746): setBluetoothStateOn
D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
D/HtcTagManager( 3746): startProxy
D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
D/BluetoothAdapterService(1109503864)( 3931): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3931): getBondedDevices: length=6
,D/BluetoothAdapter( 3746): getBluetoothService(): entry
D/BluetoothAdapter( 3746): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3746): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@422615a0
D/BluetoothDevice( 3746): getService : Register callback
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,E/BluetoothDevice( 3746): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/HtcTagManager( 3746): addHtcTagProfiles
,D/BluetoothInputDevice( 3746): Proxy object connected
,D/HidProfile( 3746): Bluetooth service connected
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/BluetoothPan( 3746): BluetoothPAN Proxy object connected
,D/PanProfile( 3746): Bluetooth service connected
D/SapServerProfile( 3746): Bluetooth service connected
D/BluetoothPbap( 3746): Proxy object connected
D/PbapServerProfile( 3746): Bluetooth service connected
D/BluetoothA2dp( 3746): Proxy object connected
,D/A2dpProfile( 3746): Bluetooth service connected
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/BluetoothHeadset( 3746): Proxy object connected
,D/HeadsetProfile( 3746): Bluetooth service connected
,D/BluetoothAdapter( 3746): 1109556904: getState(). Returning 12
,D/HtcTagManager( 3746): onServiceConnected
D/HtcTagProfile( 3746): setup proxy
D/HtcPxpProfile( 3746): setup proxy
,D/HtcFmpProfile( 3746): setup proxy
,D/libc    (  901): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  901): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/libc    (  901): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/libc    (  901): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/libc    (  901): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  901): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4023): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  901):    returned true
,D/WifiNative-wlan0(  901): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  901):    returned true
,D/WifiStateMachine(  901): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  901): releaseWL(43c60c00): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 4023): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): gateway: /192.168.1.1
,D/WifiNative-wlan0(  901): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4023): WiFi gateway: 0x101a8c0
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  901): VerifyingLinkState enter
D/WifiStateMachine(  901): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  901): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  901): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  901): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -49, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  901): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  901): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  901): startDataStallAlarm: tag=19835 delay=15s
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  901): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WifiWatchdogStateMachine(  901): WAN detection
,D/WISPrService( 3325): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  901): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  901): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  901): Provision feature enable=false
D/ConnectivityService(  901): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  901): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  901): default: teardown()
D/MDST    (  901): default: setTeardownRequested(true)
D/MDST    (  901): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
D/MDST    (  901): default: setTeardownRequested(true)
D/ConnectivityService(  901): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  901): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  901): syncGetConfiguredNetworks
E/ConnectivityService(  901): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b31210
D/ConnectivityService(  901): handleConnectivityChange: netType=1 doReset=false resetMask=0
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
D/ConnectivityService(  901): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  901): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  901): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  901): handleConnectivityChange: resetting
D/Nat464Xlat(  901): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  901): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  901): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  901):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  901): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  901): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  901): acquireWL(434f0e10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 901 1000 null
D/ConnectivityService(  901): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  901): getNetworkInfo networkType=1 called by  (901/1000)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1107): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/PMS     (  901): releaseWL(434f0e10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  901): mActiveDefaultNetwork: WIFI
,D/WIFI_ICON( 1107): WifiActivity: 1
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/Tethering(  901): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  901): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  901): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4114 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,V/Tethering(  901): bSetPropertyMultiRAB:false
,D/Tethering(  901): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
D/GpsLocationProvider(  901): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  901): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true,
,I/ConnectivityHelper( 1246): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  901): NoActiveNetworkState
I/Tethering(  901): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  901): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  901): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  901): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  901): Found interface wlan0
,D/Tethering(  901): TetherMasterSM: InitialState processMessage what=3
D/libc    (  901): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  901): [NET] getaddrinfo-,err=8
D/libc    (  901): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  901): [NET] getaddrinfo-, 1
,D/libc    (  901): [NET] getaddrinfo_proxy+
D/PMS     (  901): acquireWL(43506f20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 901 1000 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1403/10028)
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by com.htc.launcher (1246/10075)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.docs (3794/10100)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.musicenhancer (3413/10051)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1769/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/CaptivePortalTracker(  901): DelayedCaptiveCheckState
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/htcCheckinService(  901): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  901): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =10c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.docs (3794/10100)
,D/GpsLocationProvider(  901): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  901): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42c99c70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 126
D/libc    (  363): [NET]res_nsend:resplen=104
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  901): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  901): acquireWL(42af5c80): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 901 1000 WorkSource{10096}
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  901): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4023): WiFioffload: SignalStrength: =97
I/ActivityManager(  901): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4132 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/PMS     (  901): releaseWL(42af5c80): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiNative-wlan0(  901):    returned true
,I/MusicStore( 4114): Database version: 95
,I/IntentController( 1107): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1527): [EventService] EVENT_RESET_THEME_TIMESTAMP
,W/ContextImpl( 4114): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/DotMatrix( 1527): [EventService] isTheSameDay:false,timestamp is early than today:true
,I/FeedActionBar( 1246): updateLastUpdatedTime(in String) LAST UPDATED 1:38
D/PMS     (  901): acquireWL(43c61720): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 901 1000 WorkSource{10096}
,D/GpsLocationProvider(  901): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  901): NTP server returned: 1450226378872 (Wed Dec 16 01:39:38 CET 2015) reference: 108777 certainty: 10 system time offset: -30
D/PMS     (  901): acquireWL(42c32080): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 901 1000 WorkSource{10160}
D/PMS     (  901): releaseWL(42c99c70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  901): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  901): acquireWL(426d9068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/PMS     (  901): releaseWL(426d9068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  901): releaseWL(43506f20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4114): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  901): acquireWL(440058b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/PMS     (  901): releaseWL(440058b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4114): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42a61488): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/PMS     (  901): releaseWL(42c32080): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/PMS     (  901): releaseWL(42a61488): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4114): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(43871328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4114): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/DelayedSyncController( 4132): Delaying sync.
,I/jxcore-log( 3873): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3873): 
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/PMS     (  901): releaseWL(43871328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(43c18740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): releaseWL(43c61720): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4114, uid=10154, userID:0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/PMS     (  901): acquireWL(42cd96b8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 901 1000 WorkSource{10096}
,D/PMS     (  901): releaseWL(43c18740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  901):     Client/Owner: Client
D/WifiDisplayAdapter(  901):     GroupId: 
D/WifiDisplayAdapter(  901):     Passphrase: 
D/WifiDisplayAdapter(  901):     SessionId: 0
D/WifiDisplayAdapter(  901):     IP Address: }
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(43da1d08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/DelayedSyncController( 4132): Delaying sync.
D/PMS     (  901): releaseWL(43da1d08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/MediaRouterService(  901): Client com.google.android.music (pid 4114): Registered
,I/MediaRouter( 4114): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(439c3bb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  901):     Client/Owner: Client
D/WifiDisplayAdapter(  901):     GroupId: 
D/WifiDisplayAdapter(  901):     Passphrase: 
D/WifiDisplayAdapter(  901):     SessionId: 0
D/WifiDisplayAdapter(  901):     IP Address: }
D/PMS     (  901): releaseWL(42cd96b8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  901): releaseWL(439c3bb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
,I/NetworkMonitor( 4114): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.music (4114/10154)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
I/ActivityManager(  901): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4161 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4114): getSelectedRoute
,I/NetworkMonitor( 4114): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  901): getNetworkInfo networkType=1 called by com.google.android.music (4114/10154)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/Process (  901): killProcessQuiet, pid=3526
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
I/ActivityManager(  901): Killing 3526:com.google.android.gm/u0a107 (adj 15): empty #17
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4114, uid=10154, userID:0
,D/ACRA    ( 4161): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4161): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4161): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/SensorManager(  901): mEventCount = 1050
,W/SystemClassLoaderAdder( 4161): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4161): Preparing secondary program dexes.
,V/DexLibLoader( 4161): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4161): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4161): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4161): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4161): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4161): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4161): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4161): Dex already copied
D/OdexVerifier( 4161): Odex verification is skipped.
,V/DexLibLoader( 4161): Creating class loader
,V/DexLibLoader( 4161): Finished creating class loader
V/DexLibLoader( 4161): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4161): Dex already copied
D/OdexVerifier( 4161): Odex verification is skipped.
,V/DexLibLoader( 4161): Creating class loader
,V/DexLibLoader( 4161): Finished creating class loader
,V/DexLibLoader( 4161): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4161): Dex already copied
D/OdexVerifier( 4161): Odex verification is skipped.
,V/DexLibLoader( 4161): Creating class loader
,V/DexLibLoader( 4161): Finished creating class loader
,V/DexLibLoader( 4161): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4161): Dex already copied
D/OdexVerifier( 4161): Odex verification is skipped.
,V/DexLibLoader( 4161): Creating class loader
,V/DexLibLoader( 4161): Finished creating class loader
,V/DexLibLoader( 4161): Verifying classes from secondary dexes.
,I/ActivityManager(  901): Recipient 3526
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DexLibLoader( 4161): DexLibLoader.ensureDexLoaded took 106 ms
,I/PMS     (  901): Going to sleep due to screen timeout...
,I/SensorManager(  901): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42848c70
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  901): disable: get sensor name = CM36282 Light sensor
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 2
W/SensorService(  901): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42848c70, eanble = 0, strlen(mName) = 59
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  901): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42a653a0
W/SensorService(  901): Listener[1] = com.htc.smartdim.sensor_eye@42cac5e0
,W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  901): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  901): Couldn't get kernel wake lock stats
,V/LightsService(  901): setLight #2: color=#0
D/qdlights(  901): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  901): setLight #0: color=#0
,D/WirelessDisplayService(  901): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  901): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  901): mWirelessDisplayManager is null
,E/BTIF_CORE( 3931): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3931): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3931): Wake lock released
,D/WIFI_ICON( 1107): WifiActivity: 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/SurfaceControl(  901): Excessive delay in blankDisplay() while turning screen off: 372ms
D/PMS     (  901): nativeSetInteractive:false
D/PMS     (  901): nativeSetInteractive:false done
D/PMS     (  901): nativeSetAutoSuspend:true
D/PMS     (  901): nativeSetAutoSuspend:true done
D/HABCtrl (  901): TPE algorithm. remove timeout.
D/PMS     (  901): OOBE c monitor 11
I/InputManager(  901): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1230): ScreenObserver: OFF
,D/NfcService( 1230): applyRouting - 0
W/ResourceType( 3873): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3873): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42211028 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/NfcService( 1230): applyRouting -2
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  901): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42c5d0c8)
I/InputMethodManagerService(  901): screenObserver, isScreenOn=false
I/InputMethodManagerService(  901): Disable input method client, pid=3873
D/PMS     (  901): acquireWL(4469f088): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/PMS     (  901): releaseWL(4469f088): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  901): wakingUp
,V/KeyguardServiceDelegate(  901): **** SHOWN CALLED ****
I/WindowManager(  901): No lock screen! windowToken=null
,D/PMS     (  901): acquireWL(43a4d748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/PMN     (  901): onScreenOn
,D/AlarmManager(  901): ACTION_SCREEN_ON
,I/BatteryService(  901): n_update end
,I/AlarmManager(  901): [AlarmQueuing] recover blocked alarms
D/PMS     (  901): releaseWL(43a4d748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/AlarmManager(  901): [AlarmQueuing] done recovering
,I/AlarmManager(  901): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WirelessDisplayService(  901): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  901): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  901): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  901): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  901): startDataStallAlarm: tag=19836 delay=15s
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/AlarmManager(  901): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  901): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=98
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/MtpService( 2205): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2205): [MTP][onReceive]-
D/NfcService( 1230): applyRouting - 0
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/NfcService( 1230): applyRouting -2
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PMS     (  901): acquireWL(446aa590): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/PMS     (  901): releaseWL(446aa590): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  901): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
V/NotificationService(  901): batLight: plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c80000
D/qdlights(  901): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  901): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  901): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  901): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  901): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): SET_SCREEN_ON:On,
I/wpa_supplicant( 4023): htc_wext_set_keepalive +
I/wpa_supplicant( 4023): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4023): getPrivFuncNum +	
,I/wpa_supplicant( 4023): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4023): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  901):    returned true
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1107): stop update clock
D/qdlights(  901): [LedInfo] has indicator attribute
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1107): WifiActivity: 0
V/NotificationService(  901): batLight: plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c80000
D/qdlights(  901): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  901): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,D/WifiStateMachine(  901): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  901): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4023): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent DefaultState
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/NetworkPolicy(  901): updateScreenOn: false
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  901): acquireWL(4415b758): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
D/PMS     (  901): releaseWL(4415b758): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3995): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3995): onScreenOn: 1450226380153
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3995): onScreenOn: 1450226380154
,I/SensorManager(  901): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42a653a0
,W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  901): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 2
W/SensorService(  901): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42a653a0, eanble = 0, strlen(mName) = 91
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  901): Listener[0] = com.htc.smartdim.sensor_eye@42cac5e0
,W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  901): goingToSleep
D/PMS     (  901): acquireWL(44657aa8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 901 1000 null
,D/AlarmManager(  901): ACTION_SCREEN_OFF
I/AlarmManager(  901): [AlarmQueuing] screen off now: 
I/AlarmManager(  901): [AlarmQueuing] data connection: true
,I/AlarmManager(  901): [AlarmQueuing] wifi connection: true
,D/PMS     (  901): releaseWL(44657aa8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiDataStallTracker(  901): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  901): stopDataStallAlarm: current tag=19836 mDataStallAlarmIntent=PendingIntent{44606a38: PendingIntentRecord{42c5b6e0 android broadcastIntent}}
D/WifiNative-wlan0(  901): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  901): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4023): SET_SCREEN_ON:Off
I/wpa_supplicant( 4023): htc_wext_set_keepalive +
I/wpa_supplicant( 4023): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4023): getPrivFuncNum +	
I/wpa_supplicant( 4023): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4023): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4023): get_ip_address source addr = c0a80176
I/wpa_supplicant( 4023): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4023): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  901):    returned true
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  901): acquireWL(439330c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 901 1000 null
D/NetworkPolicy(  901): updateScreenOn: false
,D/wpa_supplicant( 4023): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): releaseWL(439330c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,W/dalvikvm( 4161): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,W/dalvikvm( 4161): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/DotMatrix( 1527): [EventService] getTotalRam: 1873 Mb
,W/dalvikvm( 4161): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4161): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4161): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4161): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4161): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/PMS     (  901): acquireWL(441f1b38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
,D/PMS     (  901): releaseWL(441f1b38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3995): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3995): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3995): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3995): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3995): onScreenOff
,W/dalvikvm( 4161): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4161): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4161): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/libc    (  901): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  901): [NET] getaddrinfo-,err=8
D/libc    (  901): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  901): [NET] getaddrinfo-, 1
D/libc    (  901): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c375 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  901): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  901): Find DNS Address www.htc.com/23.59.123.86
,W/fb4a(:<default>):StaticBindingVerifier( 4161): Verify
,D/WifiService(  901): New client listening to asynchronous messages
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4161/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4161): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4161): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  901): Disable JIT of com.htc.bgp
,I/ActivityManager(  901): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4190 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  901): killProcessQuiet, pid=3764
,I/ActivityManager(  901): Killing 3764:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  901): Recipient 3764
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 4190): Created com.android.providers.calendar.CalendarAlarmManager@4223cae0(com.android.providers.calendar.HtcCalendarProvider@42224e68)
,W/fb4a(:<default>):UserScope( 4161): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4161): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/CalendarProvider2( 4190): wait start:true
,W/fb4a(:<default>):UserScope( 4161): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/CalendarProvider2( 4190): wait end:false
,D/PMS     (  901): acquireWL(43c2d888): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/PMS     (  901): acquireWL(43867848): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
,D/PMS     (  901): releaseWL(43c2d888): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  901): releaseWL(43867848): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1338): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
D/libc    ( 1338): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1338): [NET] getaddrinfo-,err=8
D/libc    ( 1338): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1338): [NET] getaddrinfo-, 1
D/libc    ( 1338): [NET] getaddrinfo_proxy+
E/dalvikvm( 4161): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4161): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9957 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
E/dalvikvm( 4161): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4161): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4161): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4161): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4161): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4161): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4161): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4161): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4161): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
,D/PMS     (  901): acquireWL(4465d830): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1338 10028 null
W/dalvikvm( 4161): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4161): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4161): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4161): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4161): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4161): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4161): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/AutoSetting( 1376): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  901): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4215 uid=10078 gids={50078, 3003, 5012}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1338): [NET] getaddrinfo_proxy-, success
,D/AutoSetting( 1376): service - onCreate()
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.sense.hsp (1376/10053)
D/AutoSetting( 1376): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  901): request 42c51b18 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  901): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1376): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1376): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1376): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1376): service - onStartCommand() check timezone in 30000
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 9.960MB for 84664-byte allocation
D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.sense.hsp (1376/10053)
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 10.000MB for 39954-byte allocation
,D/MobileConnectivityChangeReceiver( 4215): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4215): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4215): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4215): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/libc    ( 1338): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1338): [NET] getaddrinfo-,err=8
W/ActivityThread( 1338): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 10.069MB for 79892-byte allocation
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4215/10078)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4215/10078)
,D/PMS     (  901): acquireWL(42a35360): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,I/ActivityManager(  901): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4230 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4215/10078)
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 10.096MB for 28144-byte allocation
D/PMS     (  901): acquireWL(436c9d00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
D/PMS     (  901): acquireWL(42ec3a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
D/PMS     (  901): releaseWL(42a35360): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
D/PMS     (  901): releaseWL(42ec3a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
I/CheckinService( 1199): Preparing to send checkin request
I/EventLogService( 1199): Accumulating logs since 1450226331988
,I/GoogleHttpClient( 1199): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1199): Using GMS GoogleHttpClient
,D/GCM     ( 1338): Connected
D/PMS     (  901): acquireWL(446e8118): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1338 10028 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4230): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/PMS     (  901): releaseWL(4465d830): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/WifiService(  901): New client listening to asynchronous messages
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4230): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4230): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1338/10028)
D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  901): handleInetConditionChange: starting a change hold
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4230): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/PMS     (  901): releaseWL(446e8118): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  901): acquireWL(4465a9d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1338 10028 null
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 10.275MB for 75760-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4230): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/ConnectivityService(  901): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  901): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=16 [12][2][0]
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4161/10026)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
,D/GCM     ( 1338): Message class mpf
D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1338/10028)
D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  901): handleInetConditionChange: currently in hold - not setting new end evt
W/BroadcastQueue(  901): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42b9ec88 u0 ReceiverList{42bbb9a8 4161 com.facebook.katana/10026/u0 remote:42665bc8}}
W/BroadcastQueue(  901): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42b8a068 u0 ReceiverList{42b8a868 4161 com.facebook.katana/10026/u0 remote:425aca70}}
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1338/10028)
D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  901): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
,D/PMS     (  901): releaseWL(4465a9d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  901): acquireWL(445bfd28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4161/10026)
,D/PMS     (  901): releaseWL(445bfd28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4161/10026)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4161/10026)
,D/ContactMessageStore( 1217): notify MmsSms
D/AccFlag ( 1217): sense_version=6.0
,D/AccFlag ( 1217): sku_id=99
,D/PMS     (  901): acquireWL(442dca10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1403 10028 null
,D/PMS     (  901): releaseWL(442dca10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,D/GCoreFlp( 1403): Unknown pending intent to remove.
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.magazines (4230/10151)
D/PMS     (  901): acquireWL(43c756d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1403 10028 null
W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,V/WebViewChromiumFactoryProvider( 4230): Binding Chromium to main looper Looper (main, tid 1) {42205170}
,I/LibraryLoader( 4230): Expected native library version number "",actual native library version number ""
,I/chromium( 4230): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4230): Initializing chromium process, renderers=0
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  901): releaseWL(43c756d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  901): acquireWL(437509c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4230): BLUETOOTH permission is missing!
D/PMS     (  901): acquireWL(435537b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  901): releaseWL(435537b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/NotificationStore( 1338): System rebooted after Notification storage file was last written
,I/NotificationStore( 1338): Deleting the file
,I/Adreno-EGL( 4230): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4230): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4230): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4230): Local Branch: 
I/Adreno-EGL( 4230): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4230): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4230):                  aa63bbd948f41d15fc72f585e
,W/CheckinRequestBuilder( 1199): awaiting user notification for token
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/NSApplication( 4230): Starting up...
,W/ContextImpl( 4161): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/RemoteViews( 1107): com.google.android.gms (false,0)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.magazines (4230/10151)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{424b8d78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/RemoteViews.Performance( 1107): com.google.android.gms 2 6 3 12
,W/ContextImpl( 4161): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.magazines (4230/10151)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4161): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  901): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4274 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.plus (3655/10160)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.plus (3655/10160)
,D/Process (  901): killProcessQuiet, pid=3794
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  901): Killing 3794:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
,I/ActivityManager(  901): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=4288 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/MultiDex( 4274): install
,I/MultiDex( 4274): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4274): loading existing secondary dex files
,I/MultiDex( 4274): load found 1 secondary dex files
,I/MultiDex( 4274): install done
,I/ProviderInstaller( 4274): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/CalendarApplication( 4288): onCreate
,D/AlertReceiver( 4288): beginStartingService
D/Process (  901): killProcessQuiet, pid=3814
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  901): acquireWL(42714fe0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4288 10013 null
I/ActivityManager(  901): Killing 3814:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 3814
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 4288): start to updateAlertNotification!
,D/AlertService( 4288): No fired or scheduled alerts
,D/HtcAlertUtils( 4288): -- cancelReminderNotification --
,D/HtcAlertUtils( 4288): broadcastExistReminder!
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 4288): stopSelfResult true
D/PMS     (  901): releaseWL(42714fe0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/PMS     (  901): acquireWL(44622830): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/PMS     (  901): releaseWL(44622830): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/ActivityManager(  901): Recipient 3794
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  901): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4306 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,W/WeatherRequest( 1107): request cur loc, but there is no sys cur
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/ActivityManager(  901): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4321 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
W/WeatherUtility( 4306): can't get weather sync account
,W/WeatherRequest( 4306): request cur loc, but there is no sys cur
,W/Settings( 4306): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PMS     (  901): acquireWL(42cae410): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4321 10070 null
D/ConnectivityService(  901): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  901): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  901): acquireWL(43c1d6f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4321 10070 null
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): releaseWL(42cae410): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/TodoTaskshortcut( 4321): update TASK shortcut>
,I/ActivityManager(  901): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4336 uid=10090 gids={50090, 3003, 5012, 1028}
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 2 16 17
,I/TodoTaskNotifyService( 4321): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 4321): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4321): stopSelfResult true
,D/Process (  901): killProcessQuiet, pid=3781
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  901): releaseWL(43c1d6f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  901): Killing 3781:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/WorldClock.Global( 4336): isHtcDevice = true
I/ActivityManager(  901): Recipient 3781
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.Global( 4336): isHtcDevice = true
,I/WorldClock.AlarmUtils( 4336): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4336): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4336): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/ActivityManager(  901): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4353 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/IntentController( 1107): receive(android.intent.action.ALARM_CHANGED,1,false)
I/CalendarProvider2( 4190): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4190): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  901): killProcessQuiet, pid=3830
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  901): killProcessQuiet, pid=3619
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 3830:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  901): Killing 3619:com.android.vending/u0a73 (adj 15): empty #17
,D/TimeService( 4353): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226382247
I/ActivityManager(  901): Recipient 3830
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  901): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4369 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  901): killProcessQuiet, pid=3916
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  901): Killing 3916:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 3916
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Settings( 4274): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  901): Recipient 3619
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (4274/10028)
,W/ContextImpl( 4369): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4369): isEpsOn(), nState = 0
D/PMS     (  901): acquireWL(42c736c0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4369 1000 null
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1376): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1376): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/SmartSyncUtils( 4369): getMobilePolicyEnabled, result = true
D/PMS     (  901): releaseWL(42c736c0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  901): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
I/ActivityManager(  901): Resuming delayed broadcast
,D/TetherSettings( 3325): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3325): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3325): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3325): Cust_ConnectToPC   : spcsc>false
D/        ( 3325): Cust_ConnectToPC   : IPT>true
D/        ( 3325): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3325): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3325): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3325): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3325): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3325): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3325):  defaultType:0
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  901): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  901): Resuming delayed broadcast
,W/ContextImpl( 4369): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4369): isEpsOn(), nState = 0
D/SmartSyncUtils( 4369): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4369): isEpsOn(), nState = 0
I/SensorManager(  901): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42cac5e0
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  901): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 1
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42cac5e0, eanble = 0, strlen(mName) = 36
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  901): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 0
W/SensorService(  901): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42cac5e0, eanble = 0, strlen(mName) = 36
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiService(  901): New client listening to asynchronous messages
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  901): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42cac5e0
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread(  901): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42cacb28 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  901): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42cacb28 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  901): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  901): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  901): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  901): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  901): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  901): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  901): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  901): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  901): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  901): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  901): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  901): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  901): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  901): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  901): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  901): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  901): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  901): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  901): 	at dalvik.system.NativeStart.main(Native Method)
,I/Adreno-EGL( 4274): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4274): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4274): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4274): Local Branch: 
I/Adreno-EGL( 4274): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4274): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4274):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  901): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4392 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  901): killProcessQuiet, pid=4024
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4024:com.htc.widget.process2/u0a48 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4024
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Adreno-EGL( 4274): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4274): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4274): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4274): Local Branch: 
I/Adreno-EGL( 4274): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4274): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4274):                  aa63bbd948f41d15fc72f585e
,I/Babel   ( 4392): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4392): MmsConfig.loadMmsSettings
,I/Adreno-EGL( 4274): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4274): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4274): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4274): Local Branch: 
I/Adreno-EGL( 4274): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4274): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4274):                  aa63bbd948f41d15fc72f585e
E/dalvikvm( 4392): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4392): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4392): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4392): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4392): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  901): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4416 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4392, uid=10111, userID:0
,D/MessageFrequencyProvider( 4416): onCreate
,W/Settings( 4392): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4392, uid=10111, userID:0
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4392, uid=10111, userID:0
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4392, uid=10111, userID:0
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4392, uid=10111, userID:0
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4392, uid=10111, userID:0
,I/ProviderInstaller( 4392): Installed default security provider GmsCore_OpenSSL
,V/GetPrviateResource( 4416): GetPrviateResource
,V/GetPrviateResource( 4416): GetPrviateResource
,D/MmsCustomizationProvider( 4416): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4416): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4392): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4392): MmsConfig.loadFromDatabase
,E/Babel   ( 4392): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4392): MmsConfig.loadFromResources
,E/Babel   ( 4392): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4392): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ActivityManager(  901): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,D/Process (  901): killProcessQuiet, pid=3957
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  901): Killing 3957:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 3957
,D/MessageCustFlag( 4416): sense_version=6.0
,D/BTAccessoryUtil( 4416): createReceiver
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BTAccessoryUtil( 4416): registerReceiver return intent = null
D/MessageCustFlag( 4416): sku_id=99
,W/SystemReader( 4416): Cannot find message_ambs_application_id, use default value instead
,D/Process (  901): killProcessQuiet, pid=3975
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.talk (4392/10111)
I/ActivityManager(  901): Resuming delayed broadcast
,I/ActivityManager(  901): Killing 3975:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Messaging( 4416): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4416): networkCode: 
D/MessageCustFlag( 4416): sku_id=99
D/MmsConfig( 4416): SIE smsPri: null
D/MmsConfig( 4416): networkCode: 
D/GCM     ( 1338): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/HtcTelephonyCapability( 4416): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4416): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4416): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4416): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  901): Recipient 3975
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.talk (4392/10111)
I/ActivityManager(  901): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  901): Resuming delayed broadcast
,D/PMS     (  901): acquireWL(44655cc0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4321 10070 null
,D/PMS     (  901): acquireWL(4464dce8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4321 10070 null
,D/PMS     (  901): acquireWL(4463e108): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4321 10070 null
,I/ActivityManager(  901): Delay finish: com.htc.task/.notification.NotifyReceiver
,D/PMS     (  901): releaseWL(44655cc0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4321): java.lang.NullPointerException
,W/System.err( 4321): java.lang.NullPointerException
W/System.err( 4321): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4321): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4321): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4321): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4321): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  901): acquireWL(4464dce8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4321 10070 null
W/NotifyReceiver( 4321): stopSelfResult false
E/TodoTaskNotifyService( 4321): java.lang.NullPointerException
W/System.err( 4321): java.lang.NullPointerException
W/System.err( 4321): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4321): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4321): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4321): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4321): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4321): mStartingService is null
,W/NotifyReceiver( 4321): stopSelfResult true
D/ProviderChangeReceiver( 4288): ---------------------------------------------------
,D/ProviderChangeReceiver( 4288): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4288): start to updateAlertNotification!
D/PMS     (  901): releaseWL(4463e108): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  901): releaseWL(4464dce8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  901): Resuming delayed broadcast
W/ContextImpl( 3746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  901): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/AlertService( 4288): No fired or scheduled alerts
D/HtcAlertUtils( 4288): -- cancelReminderNotification --
D/HtcAlertUtils( 4288): broadcastExistReminder!
D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  901): Resuming delayed broadcast
,I/ActivityManager(  901): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4442 uid=10038 gids={50038}
W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4392): UserRecoverableAuthException.
,E/Babel   ( 4392): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4392): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4392): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4392): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4392): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4392): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4392): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4392): Error getting auth token
,E/Babel   ( 4392): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4392): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4392): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4392): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4392): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4392): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,D/Process (  901): killProcessQuiet, pid=4114
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/Babel   ( 4392): Account registration failedRedacted-21
E/Babel   ( 4392): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4392): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4392): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4392): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4392): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4392): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,I/Babel   ( 4392): Account setup failed with error state:106 account:Redacted-21
I/ActivityManager(  901): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4455 uid=10077 gids={50077}
I/ActivityManager(  901): Killing 4114:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.talk (4392/10111)
I/Babel   ( 4392): Account sign in complete with state 106account: Redacted-21
,I/ActivityManager(  901): Recipient 4114
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  901): Client com.google.android.music (pid 4114): Died!
,D/SMSBackup( 4455): Got a database change event
,D/Process (  901): killProcessQuiet, pid=4161
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  901): Killing 4161:com.facebook.katana/u0a26 (adj 15): empty #17
W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Babel   ( 4392): Unexpected exception while authenticating.
,E/Babel   ( 4392): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.,
E/Babel   ( 4392): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4392): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4392): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4392): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4392): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4392): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4392): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4392): 	at java.lang.Thread.run(Thread.java:864)
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{425cee88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 8 2 12
,I/ActivityManager(  901): Recipient 4161
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  901): Client connection lost with reason: 4
,D/PMS     (  901): acquireWL(43c0cf10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1403 10028 null
,D/PMS     (  901): acquireWL(43c0c380): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1403 10028 null
,D/PMS     (  901): releaseWL(43c0cf10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  901): releaseWL(43c0c380): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/CheckinTask( 1199): Sending checkin request (9109 bytes)
,W/ActivityThread( 1199): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1199): [NET] getaddrinfo-,err=8
D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1199): [NET] getaddrinfo-, 1
,D/libc    ( 1199): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4b29 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 273
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1199): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1199): [NET] getaddrinfo-,err=8
,I/CheckinResponseProcessor( 1199): From server: 2 gservices updates and 0 deletes
D/PMS     (  901): acquireWL(4350d2d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
D/PMS     (  901): releaseWL(4350d2d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CertBlacklister(  901): Certificate blacklist changed, updating...
,I/CertBlacklister(  901): Certificate blacklist updated
,I/GservicesProvider( 1338): main difference update completed
,I/ActivityManager(  901): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4473 uid=10016 gids={50016, 3003, 5012, 2001}
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4215/10078)
,D/ConnectivityService(  901): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  901): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=12 [24][3][0]
,W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4473): Update started
,I/ActivityManager(  901): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,I/ActivityManager(  901): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4473): Received malformed URL while handling Gservices.CHANGED_ACTION
W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,D/ConnectivityService(  901): getAllNetworkInfo called by  (2205/10021)
W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4473): Update started
,I/ActivityManager(  901): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/DownloadManager( 2205): Download 155 starting
D/PMS     (  901): acquireWL(43c1c7e0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2205 10021 WorkSource{10016}
,D/ConnectivityService(  901): getAllNetworkInfo called by  (2205/10021)
I/RemoteViews( 1107): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1199): awaiting user notification for token
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{425e6970 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 10 3 12
W/ActivityThread( 2205): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/CheckinTask( 1199): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1199): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
I/ActivityManager(  901): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4473): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/ConnectivityService(  901): getAllNetworkInfo called by  (2205/10021)
E/UpdateRequestReceiver( 4473): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 4473): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/Process (  901): killProcessQuiet, pid=4215
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  901): Killing 4215:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4215
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DownloadManager( 2205): Download 156 starting
D/libc    ( 2205): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2205): [NET] getaddrinfo-,err=8
D/libc    ( 2205): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2205): [NET] getaddrinfo-, 1
,D/libc    ( 2205): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d501 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  901): acquireWL(4373e5c0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2205 10021 WorkSource{10016}
D/ConnectivityService(  901): getAllNetworkInfo called by  (2205/10021)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 2205): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2205): [NET] getaddrinfo-,err=8
D/libc    ( 2205): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2205): [NET] getaddrinfo-, 1
,D/libc    ( 2205): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =350 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
,I/ActivityManager(  901): Delay finish: com.google.android.gms/.analytics.internal.GServicesChangedReceiver
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [2][0][0]
D/PMS     (  901): releaseWL(436c9d00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1199): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4220fc58 that was originally bound here
E/ActivityThread( 1199): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4220fc58 that was originally bound here
E/ActivityThread( 1199): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1199): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1199): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1199): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1199): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1199): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1199): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1199): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1199): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1199): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1199): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1199): 	at bks.a(SourceFile:298)
E/ActivityThread( 1199): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1199): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1199): 	at java.lang.Thread.run(Thread.java:864)
,V/GA-SERVICE( 1199): Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1199, uid=10028, userID:0
I/ActivityManager(  901): Resuming delayed broadcast
D/PMS     (  901): acquireWL(441765c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
I/ActivityManager(  901): Delay finish: com.google.android.gms/.checkin.CheckinService$Receiver
D/PMS     (  901): acquireWL(441db7b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
D/PMS     (  901): releaseWL(437509c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  901): releaseWL(441765c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=49
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2205): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET]res_nsend:resplen=49
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2205): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  901): Resuming delayed broadcast
D/PMS     (  901): releaseWL(441db7b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/SystemUpdateService( 1199): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/PMS     (  901): acquireWL(43c18840): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1199 10028 null
I/ActivityManager(  901): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/SystemUpdateService( 1199): cancelUpdate (empty URL)
,I/SystemUpdateService( 1199): active receiver: disabled
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1199, uid=10028, userID:0
,I/SystemUpdateService( 1199): cancelUpdate (empty URL)
,I/SystemUpdateService( 1199): active receiver: disabled
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1199, uid=10028, userID:0
I/ActivityManager(  901): Resuming delayed broadcast
,D/GCM     ( 1338): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/PMS     (  901): releaseWL(43c18840): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
,I/ActivityManager(  901): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
,D/PMS     (  901): acquireWL(43be5448): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  901): releaseWL(43be5448): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DownloadManager( 2205): Ignoring Content-Length since Transfer-Encoding is also defined
I/ActivityManager(  901): Resuming delayed broadcast
,I/GCM     ( 1338): GCM config loaded
,I/ActivityManager(  901): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,D/SystemEventReceiver( 1199): Received GSERVICES_CHANGED broadcast
I/ActivityManager(  901): Resuming delayed broadcast
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,I/OcrUtils( 1199): Updating ocr activity enabled=false
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/GCoreUlr( 1403): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
D/PMS     (  901): acquireWL(43541e50): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1403 10028 null
,I/GCoreUlr( 1403): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  901): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4518 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  901): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,I/DownloadManager( 2205): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2205): Download 156 finished with status SUCCESS
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): releaseWL(4373e5c0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4518, uid=10031, userID:0
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4518, uid=10031, userID:0
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4518, uid=10031, userID:0
,D/PMS     (  901): acquireWL(4469f128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=4518, uid=10031, userID:0
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4518, uid=10031, userID:0
,D/PMS     (  901): releaseWL(4469f128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4518, uid=10031, userID:0
,D/PMS     (  901): acquireWL(4340f708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
,D/PMS     (  901): releaseWL(4340f708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/DownloadManager( 2205): Download 155 finished with status SUCCESS
D/PMS     (  901): releaseWL(43c1c7e0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/PMS     (  901): acquireWL(44219f38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
D/PMS     (  901): releaseWL(44219f38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  901): acquireWL(42c72120): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
,D/PMS     (  901): releaseWL(42c72120): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/GCoreUlr( 1403): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1403): Unknown pending intent to remove.
D/PMS     (  901): acquireWL(42c895a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
D/PMS     (  901): releaseWL(42c895a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  901): acquireWL(43861590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1403 10028 null
,D/PMS     (  901): releaseWL(43861590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null,
D/Messaging( 4416): mNeedToUpdateDate2 start
,D/MmsConfig( 4416): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4416): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4416): 
D/MmsAsyncWorkHandler( 4416): HM tk = 20001
,D/ReportIndicatorCache( 4416): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4416): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@4220c9d0
,I/Messaging( 4416): mccmnc> 
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4416): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4416): [DraftCache/1] refresh
,D/MmsConfig( 4416): networkCode: 
,D/Messaging( 4416): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PMS     (  901): acquireWL(440eb168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
,D/PMS     (  901): releaseWL(440eb168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/Messaging( 4416): mNeedToUpdateDate2: false
D/MessageCustFlag( 4416): sense_version=6.0
D/PhoneStorageUtil( 4416): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4416): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4416): createReceiver
D/Jerry   ( 4416): start to preload cursor >>>>>>>
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1217):  phoneType = -1
D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1217): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
V/MmsProvider( 1217): Update uri=content://mms, match=0
,V/MmsProvider( 1217): selection=st=129 AND m_type!=134
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/Messaging( 4416): Reset downloading state: 0
V/MmsSystemEventReceiver( 4416): TransactionService is going to be woken up.
,D/MmsSmsV2Provider( 1217):  phoneType = -1
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1217): sku_id=99
I/ActivityManager(  901): Delaying start of: ServiceRecord{4467a390 u0 com.htc.sense.mms/.transaction.TransactionService}
D/PMS     (  901): acquireWL(435108d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
D/Messaging( 4416): ViewCache CreatePreload
,D/Messaging( 4416): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4416): _has_set_default_values_2=true
,D/PMS     (  901): releaseWL(435108d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/DraftCache( 4416): [DraftCache/454] rebuildCache
D/MsgPreferenceUtils( 4416): def_index: 0
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1217):  phoneType = -1
D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
V/TransactionService( 4416): 1-Creating TransactionService
D/MsgPreferenceUtils( 4416): globalIndex = 1
D/MsgPreferenceUtils( 4416): phone state: true
D/MsgPreferenceUtils( 4416): sd state: false
D/MsgPreferenceUtils( 4416): vIndex = 0
D/Messaging( 4416): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
V/TransactionService( 4416): onStartCommand: 1
D/MmsSystemEventReceiver( 4416): unRegisterForConnectionStateChanges
V/TransactionService( 4416): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4416): Loading previous transactions.
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/Jerry   ( 1217): URI_DRAFT
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/AccFlag ( 1217): device_type: 1
D/DraftCache( 4416): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4416): [DraftCache/454] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4416): 
D/MmsAsyncWorkHandler( 4416): HM tk = 20002
D/TransactionService( 4416): Force set service start id to 1
V/TransactionService( 4416): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4416): unRegisterForConnectionStateChanges
V/TransactionService( 4416): Destroying TransactionService
,D/TransactionService( 4416): stopSelfResult: true, mLastHandledServiceId: 1
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1217): sku_id=99
,D/Process (  901): killProcessQuiet, pid=4132
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/TransactionService( 4416): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  901): Resuming delayed broadcast
I/ActivityManager(  901): Killing 4132:com.android.chrome/u0a96 (adj 15): empty #17
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1217): sku_id=99
,I/ActivityManager(  901): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4563 uid=10078 gids={50078, 3003, 5012}
,I/GCoreUlr( 1403): Unbound from all location providers
D/PMS     (  901): releaseWL(43541e50): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,E/PhoneMonitor( 4563): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4563): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  901): killProcessQuiet, pid=4230
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4563/10078)
,I/ActivityManager(  901): Killing 4230:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
I/ContactAccountLoggerTas( 2659): canRun() : Opted Out
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4563/10078)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4563/10078)
,I/Search.GservicesUpdateTask( 2659): Updating Gservices keys
D/PMS     (  901): acquireWL(4467f650): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
I/ActivityManager(  901): Recipient 4132
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  901): acquireWL(4466d658): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
D/PMS     (  901): releaseWL(4467f650): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  901): releaseWL(4466d658): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/ContactAccountLoggerTas( 2659): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2659): canRun() : Opted Out
I/ActivityManager(  901): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
,I/ContactAccountLoggerTas( 2659): canRun() : Opted Out
,I/ActivityManager(  901): Recipient 4230
,I/dalvikvm-heap( 3655): Grow heap (frag case) to 13.620MB for 1821008-byte allocation
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3655, uid=10160, userID:0
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/dalvikvm-heap( 3655): Grow heap (frag case) to 15.317MB for 1821008-byte allocation
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/googlenow
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3655, uid=10160, userID:0
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3655, uid=10160, userID:0
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Search.LoginHelper( 2659): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,W/Search.LoginHelper( 2659): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2659): canRun() : Opted Out
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{4262c610 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 8 3 12
I/ActivityManager(  901): Resuming delayed broadcast
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCM     ( 1338): GCM config loaded
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 ,
I/ActivityManager(  901): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  901): Resuming delayed broadcast
,D/ConnectivityService(  901): getAllNetworkInfo called by  (2205/10021)
,I/DownloadManager( 2205): Download 157 starting
D/PMS     (  901): acquireWL(42ceb9b0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2205 10021 WorkSource{10016}
D/ConnectivityService(  901): getAllNetworkInfo called by  (2205/10021)
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  901): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=100 [1][1][0]
,I/DownloadManager( 2205): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager(  901): Resuming delayed broadcast
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [10][0][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
,D/ConnectivityService(  901): getAllNetworkInfo called by  (2205/10021)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,D/Process (  901): killProcessQuiet, pid=3413
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
I/ActivityManager(  901): Killing 3413:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service
I/ActivityManager(  901): Recipient 3413
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  901): acquireWL(42ab5200): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2205 10021 WorkSource{10016}
,I/DownloadManager( 2205): Download 158 starting
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  901): getAllNetworkInfo called by  (2205/10021)
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2205): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2205): Download 157 finished with status SUCCESS
D/PMS     (  901): releaseWL(42ceb9b0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (2205/10021)
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=3 [31][1][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4473): Update downloaded, starting installation
,I/UpdateFetcherService( 4473): Started installation
I/ActivityManager(  901): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  901): Resuming delayed broadcast
,I/DownloadManager( 2205): Download 158 finished with status SUCCESS
D/PMS     (  901): releaseWL(42ab5200): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4473): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4473): Update downloaded, starting installation
,I/UpdateFetcherService( 4473): Started installation
I/ActivityManager(  901): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,D/DownloadManager( 2205): Download 158 already finished; skipping
,I/ActivityManager(  901): Resuming delayed broadcast
,I/ConfigUpdateInstallReceiver(  901): Not installing, new version is <= current version
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4392, uid=10111, userID:0
,D/Process (  901): killProcessQuiet, pid=4306
,I/ActivityManager(  901): Killing 4306:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  901): Recipient 4306
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  901): Killing 4336:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  901): killProcessQuiet, pid=4336
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  901): Recipient 4336
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  901): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  901): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  901): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/dalvikvm-heap( 3655): Grow heap (frag case) to 17.074MB for 1821008-byte allocation
,I/GAV2    ( 3655): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1376): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1376): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1376): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/PackageSettings(  901): Skipping PackageSetting{42962f78 com.example.hello/10356} due to missing metadata
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{44692370 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  901):   Scheme: "sms"
,D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1246): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  901):   Scheme: "smsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/Launcher( 1246): Deferring update until onResume
,D/Launcher( 1246): waitUntilResume // bindAppsUpdated
,I/[PluginManager]RegisterService( 1376): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
I/[PluginManager]RegisterService( 1376): handle notify Blinkfeed plugin client changed
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  901):   Scheme: "mms"
I/ActivityManager(  901): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  901):   Scheme: "mmsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/ActivityManager(  901): Resuming delayed broadcast
,I/ActivityManager(  901): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4607 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
,I/PeopleContactsSync( 1199): CP2 sync disabled
,I/PackageManager(  901):   Scheme: "sms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/PMS     (  901): acquireWL(434e5860): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
,I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  901):   Scheme: "smsto"
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  901):   Scheme: "mms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PMS     (  901): releaseWL(434e5860): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  901):   Scheme: "mmsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4607, uid=10073, userID:0
,D/Finsky  ( 4607): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  901): getAllNetworkInfo called by com.android.vending (4607/10073)
,D/ConnectivityService(  901): getAllNetworkInfo called by com.android.vending (4607/10073)
,D/Finsky  ( 4607): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4607): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4607): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4607, uid=10073, userID:0
,D/Finsky  ( 4607): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4607): [1] 2.run: Finished loading 1 libraries.
,D/Process (  901): killProcessQuiet, pid=4353
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  901): Killing 4353:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/IcingCorporaProvider( 2659): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  901): Recipient 4353
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  901): acquireWL(432a6440): PARTIAL_WAKE_LOCK  AsyncService 0x1 3655 10160 null
,D/PMS     (  901): releaseWL(432a6440): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4607): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4607): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/IcingCorporaProvider( 2659): UpdateCorporaTask done [took 281 ms] updated apps [took 281 ms] 
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@42294ed8 +
,I/Prism.WidgetManager( 1246): onLoadItems() +
,D/PMS     (  901): acquireWL(4350f810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10073}
,V/AlarmManager(  901): sending alarm PendingIntent{426c3f20: PendingIntentRecord{42450e78 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450226399918, Int=0
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=129907, Int=0
,D/PhoneApp( 1217): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1217): -- N1 =0
,D/PhoneApp( 1217): -- N2 =0
,D/PhoneApp( 1217): -- N3 =0
,W/asset   ( 1246): Copying FileAsset 0x67e9eb10 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1246): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1246): onLoadItems() -
,I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@42294ed8 -
,W/PackageManager(  901): Unable to load service info ResolveInfo{43a61c70 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  901): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  901): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  901): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  901): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  901): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  901): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  901): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  901): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  901): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  901): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  901): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  901): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  901): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  901): start
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4350f810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4607): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4607): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4607): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4607): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4607): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/PMS     (  901): acquireWL(4463db08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(4463db08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): closing low battery warning: level=98
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  901): acquireWL(4463e8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{423e9698: PendingIntentRecord{42b90220 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=138807, Int=0
,D/PMS     (  901): acquireWL(434eac00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): releaseWL(4463e8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(432e7fb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(434eac00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(432e7fb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1376): service - mHandler: update timezone
,D/AutoSetting( 4190): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4190): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  901): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  901): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4190): service - onCreate()
,D/AutoSetting( 4190): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4190): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4190): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 4190): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4190): service - mHandler: update timezone
,D/AutoSetting( 4190): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4190): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4190): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4190): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1107): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{423b2588 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.htclocationservice 2 10 2 11
,D/AutoSetting( 1376): service - handleMessage() stop self
,D/AutoSetting( 1376): service - onDestroy() END
,D/AutoSetting( 1376): service - handleMessage() quit looper
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  901): acquireWL(441d3418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10028}
,V/AlarmManager(  901): sending alarm PendingIntent{4260ebd0: PendingIntentRecord{42c731a0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140181, Int=0
,V/AlarmManager(  901): sending alarm PendingIntent{42aee8d0: PendingIntentRecord{42bcfd48 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141254, Int=0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
,V/AlarmManager(  901): sending alarm PendingIntent{439ffa10: PendingIntentRecord{43c49578 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450226414624, Int=563223000
,V/AlarmManager(  901): sending alarm PendingIntent{4269e240: PendingIntentRecord{441e95e0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450226416329, Int=0
,D/PMS     (  901): acquireWL(441c1528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  901): releaseWL(441c1528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  901): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  901): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  901): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  901): acquireWL(44166760): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 901 1000 null
D/PMS     (  901): acquireWL(440ed150): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/libc    (  901): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  901): [NET] getaddrinfo-,err=8
D/libc    (  901): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  901): [NET] getaddrinfo-, 1
,D/libc    (  901): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =dea3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  901): releaseWL(441d3418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  901): acquireWL(43dab050): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
D/PMS     (  901): releaseWL(440ed150): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/CheckinService( 1199): Preparing to send checkin request
,I/EventLogService( 1199): Accumulating logs since 1450226381414
,W/EventLogAggregator( 1199): Unknown tag: install_package_attempt
,W/EventLogAggregator( 1199): Unknown tag: snet
,W/EventLogAggregator( 1199): Unknown tag: snet_gcore
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  901): [NET] getaddrinfo_proxy-, success
I/global  (  901): call createSocket() return a new socket.
D/libc    (  901): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,I/GoogleHttpClient( 1199): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1199): Using GMS GoogleHttpClient
,D/GpsLocationProvider(  901): [handleDownloadXtraData] calling native_inject_xtra_data
D/ConnectivityService(  901): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/ConnectivityService(  901): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4023): environment dirty rate=2 [38][1][0]
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/GpsLocationProvider(  901): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  901): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  901):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  901): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1199): awaiting user notification for token
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{42656360 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 6 2 12
,D/Finsky  ( 4607): [1] 5.onFinished: Installation state replication succeeded.
,W/Settings( 4274): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (4274/10028)
,I/Adreno-EGL( 4274): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4274): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4274): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4274): Local Branch: 
I/Adreno-EGL( 4274): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4274): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4274):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4274): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4274): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4274): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4274): Local Branch: 
I/Adreno-EGL( 4274): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4274): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4274):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4274): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4274): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4274): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4274): Local Branch: 
I/Adreno-EGL( 4274): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4274): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4274):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 1199): Sending checkin request (9008 bytes)
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1199): [NET] getaddrinfo-,err=8
D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1199): [NET] getaddrinfo-, 1
,D/libc    ( 1199): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =841b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1199): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1199): [NET] getaddrinfo-,err=8
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  901): acquireWL(42b8a940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  901): releaseWL(42b8a940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  901): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4023): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4023): nl80211: survey data missing!
E/wpa_supplicant( 4023): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4023): environment dirty rate=0 [16][0][0]
D/ConnectivityService(  901): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1199): awaiting user notification for token
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{425f7090 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 10 4 12
,I/CheckinTask( 1199): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1199): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  901): releaseWL(43dab050): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1338): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 1199): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@42452d98 that was originally bound here
E/ActivityThread( 1199): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@42452d98 that was originally bound here
E/ActivityThread( 1199): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1199): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1199): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1199): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1199): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1199): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1199): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1199): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1199): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1199): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1199): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1199): 	at bks.a(SourceFile:298)
E/ActivityThread( 1199): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1199): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1199): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1199): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1338): GCM config loaded
,D/PMS     (  901): releaseWL(44166760): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{44677598 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  901): acquireWL(43531440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43531440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
,I/HtcPowerSaver(  901): >> updateStatus
D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1107): closing low battery warning: level=98
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  901): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4190): service - handleMessage() stop self
,D/AutoSetting( 4190): service - onDestroy() END
,D/AutoSetting( 4190): service - handleMessage() quit looper
,I/ActivityManager(  901): Killing 4369:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  901): killProcessQuiet, pid=4369
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  901): Recipient 4369
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  901): Client connection lost with reason: 4
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  901): acquireWL(441e2010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=189907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(441e2010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42cb1180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42cb1180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=98
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  901): acquireWL(43ca4bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43ca4bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  901): updateBatteryInfo
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=99,
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  901): acquireWL(42cf5540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=249907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42cf5540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(4463aa70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4463aa70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1107): closing low battery warning: level=99
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  901): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  901): acquireWL(44592bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=309907, Int=0
,D/PMS     (  901): releaseWL(44592bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43549580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43549580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  901): acquireWL(42c9c978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=369907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42c9c978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42c6bdb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42c6bdb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  901): updateBatteryInfo
,D/PowerUI ( 1107): closing low battery warning: level=99
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  901): acquireWL(43506b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43506b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  901): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1107): closing low battery warning: level=100
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 3931): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/DotMatrix( 1527): [EventService] reorderNotification, total:0
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  901): batLight: Full, plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c800
D/qdlights(  901): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,I/ActivityManager(  901): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4667 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,W/ContextImpl( 4667): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3325): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3325): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3325): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3325): Cust_ConnectToPC   : spcsc>false
D/        ( 3325): Cust_ConnectToPC   : IPT>true
,D/        ( 3325): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3325): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3325): Index of the first 1 = -1
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3325): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3325): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3325): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3325): [ACC]android_networking:tethering_guard_support=false
,D/Process (  901): killProcessQuiet, pid=4392
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  901): Killing 4392:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4392
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3873): Connected to the server!
I/jxcore-log( 3873): 
,I/chromium( 3873): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  901): acquireWL(441a72c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=429907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(441a72c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1338): GoogleAccountDataService.getToken()
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1338): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1338): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,W/GLSActivity( 1338): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1338): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1338): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1338): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1338): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1338): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{42536e78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4607): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4607): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4607): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4607): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4607): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4607): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4607): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4607): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1107): com.google.android.gms 2 8 3 12
,D/libc    ( 4607): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4607): [NET] getaddrinfo-,err=8
D/libc    ( 4607): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4607): [NET] getaddrinfo-, 1
,D/libc    ( 4607): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =432f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4607): [NET] getaddrinfo_proxy-, success
I/global  ( 4607): call createSocket() return a new socket.
D/libc    ( 4607): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4607): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4607): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4607): [NET] getaddrinfo-,err=8
,D/PMS     (  901): acquireWL(44695ab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(44695ab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  901): acquireWL(42cf14e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=489907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42cf14e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43c09968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43c09968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  901): acquireWL(43980548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=549907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(43980548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43715930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43715930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42c547c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  901): releaseWL(42c547c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  901): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(42b6d220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=609906, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42b6d220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43e60868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43e60868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1217): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1217): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1217): sku_id=99
D/ContactMessageStore( 1217): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/PMS     (  901): acquireWL(4467b6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=669906, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4467b6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43c0de88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43c0de88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  901): killProcessQuiet, pid=4321
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4321:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4321
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  901): acquireWL(43c0efe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=729906, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(43c0efe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(441df638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(441df638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42cd4ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=789907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42cd4ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43c1b608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43c1b608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42cac960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=849906, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42cac960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(441b43f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(441b43f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(43bfb238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=909907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(43bfb238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42ce9dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42ce9dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42d556e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=969907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42d556e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(4410be10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4410be10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  901): Sampling interval elapsed, updating statistics ..
,D/PMS     (  901): acquireWL(43c60a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42482ca0: PendingIntentRecord{42b3b9c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781391, Int=0
,V/AlarmManager(  901): sending alarm PendingIntent{42a437c0: PendingIntentRecord{42c67f10 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011516, Int=0
,D/ConnectivityService(  901): Done.
,D/ConnectivityService(  901): Setting timer for 720seconds
,I/ActivityManager(  901): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4699 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  901): sending alarm PendingIntent{42c06970: PendingIntentRecord{42cb6a70 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450226490648, Int=10800000
,V/AlarmManager(  901): sending alarm PendingIntent{42a7fa38: PendingIntentRecord{42abd6c8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450227211139, Int=900000
,D/PMS     (  901): acquireWL(445e8918): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1338 10028 null
,V/AlarmManager(  901): sending alarm PendingIntent{427f1830: PendingIntentRecord{42a9e340 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450227282641, Int=0
,D/PMS     (  901): releaseWL(445e8918): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  901): acquireWL(445d6a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,W/ContextImpl( 4667): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  901): releaseWL(445d6a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4667): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4667): MY_DEBUG = false
,D/PMS     (  901): acquireWL(4465d5b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4667 1000 null
,D/SmartSyncUtils( 4667): isEpsOn(), nState = 0
D/PMS     (  901): acquireWL(44c64bc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1338 10028 null
D/PMS     (  901): releaseWL(43c60a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.aurora (4699/10047)
,D/PMS     (  901): releaseWL(4465d5b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  901): acquireWL(42b6cde8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4667 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4667): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4667): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 18, nEnd = 23, bNormalRange = true
,D/GCM     ( 1338): Message class mow
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1338/10028)
D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1338/10028)
D/ConnectivityService(  901): handleInetConditionChange: starting a change hold
,D/PMS     (  901): releaseWL(44c64bc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  901): acquireWL(43031f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1338 10028 null
,D/PMS     (  901): releaseWL(43031f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 4667): [updateNmRange] new USERNIGHT_TIMESTART = 18, new USERNIGHT_TIMEEND = 23
,W/ContextImpl( 4667): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
I/FeedHostManager( 1246): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
D/SmartSyncScreenOnOffTimeReceiver( 4667): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4667): SettingOnTime = 1450303200000, randomSettingOnTime = 1450299602000
D/SmartSyncScreenOnOffTimeReceiver( 4667): SettingOffTime = 1450285200000, randomSettingOffTime = 1450290608000
,I/FeedHostManager( 1246): NightMode begin at 0, end at 7
,D/SmartSyncScreenOnOffTimeReceiver( 4667): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4667): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4667): bNightModeTurnOffOnce = false
D/PMS     (  901): acquireWL(42e4d7d8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1246 10075 null
,I/FeedHostManager( 1246): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1450227282848, BeginTime: 1450220400000, EndTime: 1450245600000
,I/FeedHostManager( 1246): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
D/PMS     (  901): releaseWL(42e4d7d8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  901): acquireWL(42cc0c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10075}
V/AlarmManager(  901): sending alarm PendingIntent{42d21ef8: PendingIntentRecord{44612ab0 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1450220400000, Int=0
D/PMS     (  901): acquireWL(42d936d0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1246 10075 null
D/PMS     (  901): releaseWL(42b6cde8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  901): releaseWL(42d936d0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  901): releaseWL(42cc0c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,D/ConnectivityService(  901): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  901): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,D/Process (  901): killProcessQuiet, pid=4288
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4288:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4288
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  901): acquireWL(42aa6478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1029907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42aa6478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42a4be68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42a4be68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42940f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1089907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42940f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(4274d3f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4274d3f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(426ab4c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1149907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(426ab4c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(424e41c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(424e41c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(4244c108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1209907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4244c108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(423325a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(423325a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  901): acquireWL(42c14bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1269907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42c14bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42af9a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42af9a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(436ec0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1329906, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(436ec0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(428ec328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(428ec328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(4258a2d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  901): releaseWL(4258a2d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(44241930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1389907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(44241930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(427bdb18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PMS     (  901): releaseWL(427bdb18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  901): updateBatteryInfo
,D/PowerUI ( 1107): closing low battery warning: level=100
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(4381fc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4381fc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42cce0e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1449907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42cce0e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42b20c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42b20c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(43e5d6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1509906, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(43e5d6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(440e8f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(440e8f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42cb08a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1569907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42cb08a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42b79700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42b79700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(428f47d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(428f47d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  901): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PMS     (  901): runPSCheck
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(43c62690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1629907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(43c62690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42733050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
I/BatteryService(  901): n_update end
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(42733050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(446a83d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1689907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(446a83d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42c69b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42c69b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(440eb580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1749907, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(440eb580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43a59888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43a59888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,D/PMS     (  901): acquireWL(435096b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1809907, Int=0
,D/PMS     (  901): releaseWL(435096b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43c75d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43c75d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  901): acquireWL(44630990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{4279c388: PendingIntentRecord{42787aa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1869907, Int=0
,I/ProcessStatsService(  901): Prepared write state in 41ms
I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(44630990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  901): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-19-00.bin
,D/PMS     (  901): acquireWL(42cf2df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42cf2df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4729): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4729): ====startRecUseTime====
D/htc.customization.log.level( 4729):  is 
W/CustomizationLogLevel( 4729): Level value is invalid, use default level 2
D/CustomizationManager( 4729):  Read ACC file spent 0.091 (s)
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4729): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4729): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4729): Parsing tag category name = system
I/CustomizationCIDLoader( 4729): Parsing tag category name = application
I/CustomizationCIDLoader( 4729): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4729): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4729): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4729): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4729): Parsing tag category name = Settings
D/CustomizationManager( 4729):  Read CID file spent 0.134 (s)
D/CustomizationManager( 4729):  All configurations done spent 0.134 (s)
W/HtcNativeFlag( 4729): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4729): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4729): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4729): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  901): deletePackageAsUser: pkg=com.test.thalitest, pid=4729, uid=2000 user=0
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  901): killProcessQuiet, pid=3873
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  901): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  901): Killing 3873:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  901):   Force finishing activity ActivityRecord{426f3370 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  901): Copying FileAsset 0x62bbc500 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  901): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  901): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  901): Got RemoteException sending setActive(false) notification to pid 3873 uid 10348
E/JavaBinder( 1182): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  901): Skipping PackageSetting{42962f78 com.example.hello/10356} due to missing metadata
I/WindowState(  901): WIN DEATH: Window{42a40670 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  901): Client connection lost with reason: 4
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1527): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1527): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  901): acquireWL(43cb3230): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1403 10028 null
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
I/acms    ( 1769): Unregistering com.test.thalitest
E/acms    ( 1769): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1403): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  901): releaseWL(43cb3230): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "sms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/VoicemailCleanupService( 1273): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "smsto"
I/Launcher( 1246): Deferring update until onResume
D/Launcher( 1246): waitUntilResume // bindAppsRemoved
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/InputMethodManagerService(  901): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  901):   Scheme: "mmsto"
D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/ExternalAccountType( 1307): Unsupported attribute readOnly
I/ActivityManager(  901): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4744 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "sms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  901):   Scheme: "smsto"
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mms"
I/MultiDex( 4744): install
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/MultiDex( 4744): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mmsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/MultiDex( 4744): loading existing secondary dex files
I/MultiDex( 4744): load found 1 secondary dex files
I/MultiDex( 4744): install done
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  901): Delaying start of: ServiceRecord{44637ec0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ActivityManager(  901): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4762 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 1199): CP2 sync disabled
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
I/ProviderInstaller( 4744): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 1199): doRemovePackageData com.test.thalitest
D/PMS     (  901): acquireWL(42ac0578): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
D/PMS     (  901): releaseWL(42ac0578): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  901): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4762): install
I/MultiDex( 4762): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4762): loading existing secondary dex files
I/MultiDex( 4762): load found 1 secondary dex files
I/MultiDex( 4762): install done
I/ProviderInstaller( 4762): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  901): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1376): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  901): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1376): handle notify Blinkfeed plugin client changed
I/ActivityManager(  901): Resuming delayed broadcast
D/Process (  901): killProcessQuiet, pid=3746
I/ActivityManager(  901): Killing 3746:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1246): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2659): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  901): Recipient 3746
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  901): Client connection lost with reason: 4
I/ActivityManager(  901): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4786 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2659): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x645c7e70
E/SQLiteDatabase( 4744): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4744): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4744): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4744): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4744): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4744): threadid=12: thread exiting with uncaught exception (group=0x41dd2e30)
W/dalvikvm( 2659): threadid=14: thread exiting with uncaught exception (group=0x41dd2e30)
E/AndroidRuntime( 4744): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4744): Process: com.google.android.gms.drive, PID: 4744
E/AndroidRuntime( 4744): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4744): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4744): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4744): 	at ctn.run(SourceFile:985)
E/AndroidRuntime( 2659): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2659): Process: com.google.android.googlequicksearchbox:search, PID: 2659
E/AndroidRuntime( 2659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2659): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2659): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2659): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2659): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2659): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2659): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2659): 	at cid.d(PG:186)
E/AndroidRuntime( 2659): 	at clo.g(PG:594)
E/AndroidRuntime( 2659): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2659): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2659): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2659): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2659): 	at clr.tL(PG:827)
E/AndroidRuntime( 2659): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2659): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2659): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2659): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2659): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2659): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  901): App crashed! Process: com.google.android.gms.drive
E/ActivityManager(  901): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 4744): killProcess, pid=4744
D/Process ( 4744): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
D/Process ( 2659): killProcess, pid=2659
D/Process ( 2659): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
I/ActivityManager(  901): Recipient 4744
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Process com.google.android.gms.drive (pid 4744) has died.
W/ActivityManager(  901): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  901): Recipient 2659
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Process com.google.android.googlequicksearchbox:search (pid 2659) has died.
D/MediaRouterService(  901): Client com.google.android.googlequicksearchbox (pid 2659): Died!
W/ActivityManager(  901): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  901): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/WifiService(  901): Client connection lost with reason: 4
E/SQLiteDatabase( 4786): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4786): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4786): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4786): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4786): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4786): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4786): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4786): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4786): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4786): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4786): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4786): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4786): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4786): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4786): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4786): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4786): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4786): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4786): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4786): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4786): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4786): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4786): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4786): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4786): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4786): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4786): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4786): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4786): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4786): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4786): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4786): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4786): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4786): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4786): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4786): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4786): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4786): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4786): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4786): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4786): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4786): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4786): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4786): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4786): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4786): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4786): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4786): threadid=11: thread exiting with uncaught exception (group=0x41dd2e30)
E/ActivityManager(  901): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4786): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4786): Process: com.google.android.apps.docs, PID: 4786
E/AndroidRuntime( 4786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4786): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4786): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4786): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4786): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4786): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
D/Process ( 4786): killProcess, pid=4786
D/Process ( 4786): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  901): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4804 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  901): Recipient 4786
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Process com.google.android.apps.docs (pid 4786) has died.
W/ContextImpl( 4804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  901): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4817 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4804): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4804): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4804): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4804): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4804): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4804): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4804): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4804): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4804): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4804): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4804): threadid=10: thread exiting with uncaught exception (group=0x41dd2e30)
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@42294ed8 +
I/Prism.WidgetManager( 1246): onLoadItems() +
E/AndroidRuntime( 4804): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4804): Process: com.android.keychain, PID: 4804
E/AndroidRuntime( 4804): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4804): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4804): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4804): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4804): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4804): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4804): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4804): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4804): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  901): App crashed! Process: com.android.keychain
D/ErrorReport(  901): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4817): getInstance(Context context)
D/Process ( 4804): killProcess, pid=4804
D/Process ( 4804): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  901): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  901): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450228182615.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  901): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  901): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  901): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  901): 	... 4 more
D/AppTag  ( 4817): getInstance(Context context)
D/AppTag  ( 4817): onCreate()
I/ActivityManager(  901): Recipient 4804
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Process com.android.keychain (pid 4804) has died.
W/ActivityManager(  901): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10417ms
D/PMS     (  901): acquireWL(42c921b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3655 10160 null
D/PMS     (  901): releaseWL(42c921b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  901): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4835 uid=10098 gids={50098, 3003, 5012}
D/Process (  901): killProcessQuiet, pid=4442
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4442:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
I/ActivityManager(  901): Recipient 4442
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 4835): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4835 dbg=false s=true
I/DeviceManagement( 4835): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4835): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]

```
