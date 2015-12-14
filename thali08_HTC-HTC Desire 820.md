#### Test 50650278e3ff7c2_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  907): mEventCount = 900
,E/cutils-trace( 3830): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3830): ====startRecUseTime====
D/htc.customization.log.level( 3830):  is 
W/CustomizationLogLevel( 3830): Level value is invalid, use default level 2
D/CustomizationManager( 3830):  Read ACC file spent 0.081 (s)
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3830): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3830): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3830): Parsing tag category name = system
I/CustomizationCIDLoader( 3830): Parsing tag category name = application
I/CustomizationCIDLoader( 3830): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3830): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3830): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3830): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3830): Parsing tag category name = Settings
D/CustomizationManager( 3830):  Read CID file spent 0.128 (s)
D/CustomizationManager( 3830):  All configurations done spent 0.128 (s)
W/HtcNativeFlag( 3830): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3830): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3830): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3830): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  907): acquireHCC(43acbbb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3830
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1136840816
D/PMS     (  907): acquireHCC(43ac5940): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
D/PMS     (  907): acquireWL(43ab05a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f947a0
I/SocialFeedProvider( 1246): +onPause
I/SocialFeedProvider( 1246): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3841 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1246): [trimMemory] 20
W/asset   ( 3841): Copying FileAsset 0x5c790418 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3841): Binding Chromium to main looper Looper (main, tid 1) {41b4f418}
I/LibraryLoader( 3841): Expected native library version number "",actual native library version number ""
I/chromium( 3841): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3841): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c2a2e8:true
D/BluetoothAdapter( 3841): 1102466640: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  907): acquireWL(438e4098): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): acquireWL(438df5c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): releaseWL(438e4098): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3841): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3841): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3841): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3841): Local Branch: 
I/Adreno-EGL( 3841): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3841): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3841):                  aa63bbd948f41d15fc72f585e
W/chromium( 3841): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3841): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3841): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3841): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3841): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3841): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3841): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3841): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3841): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3841): CordovaWebView is running on device made by: HTC
,W/AwContents( 3841): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1246
,I/InputMethodManagerService(  907): Enable input method client, pid=3841
W/ResourceType( 3841): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3841): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b963d8, mServedView=org.apache.cordova.engine.SystemWebView{41b5c168 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 3841): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +286ms
,D/PMS     (  907): releaseWL(43ab05a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3841): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3841): JniHelper::setJavaVM(0x4162d010), pthread_self() = 1662613288
,D/JX-Cordova( 3841): jxcore cordova android initializing
,W/dalvikvm( 3841): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.511MB for 64402-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.569MB for 96598-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.652MB for 144892-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.768MB for 217334-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 11.941MB for 325996-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 12.603MB for 733480-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 13.205MB for 1100216-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 14.087MB for 1650320-byte allocation
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 15.463MB for 2475476-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(43acbbb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(43ac5940): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3841): Grow heap (frag case) to 17.516MB for 3713210-byte allocation
,W/jxcore-log( 3841): Initializing JXcore engine
,W/jxcore-log( 3841): JXcore engine is ready
,W/jxcore-log( 3841): Starting JXcore engine
,W/jxcore-log( 3841): Platform android
W/jxcore-log( 3841): 
,W/jxcore-log( 3841): Process ARCH arm
W/jxcore-log( 3841): 
,D/PMS     (  907): releaseWL(438df5c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3841): JXcore Cordova bridge is ready!
I/jxcore-log( 3841): 
,W/jxcore-log( 3841): JXcore engine is started
,I/chromium( 3841): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3885 uid=10077 gids={50077}
,D/PMS     (  907): acquireWL(43887648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
,V/AlarmManager(  907): sending alarm PendingIntent{4202d7a0: PendingIntentRecord{426e50c0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450100311885, Int=60000
,D/PMS     (  907): releaseWL(43887648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3885): SMSBackupAgentService started
,D/SMSBackup( 3885): Checking restore status
,D/SMSBackup( 3885): Restore complete
,D/SMSBackup( 3885): cancelCheckAlarm
,D/SMSBackup( 3885): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  907): killProcessQuiet, pid=3391
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3391:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3391
,D/MediaRouterService(  907): Client com.google.android.music (pid 3391): Died!
,I/jxcore-log( 3841): Toggling radios to true
I/jxcore-log( 3841): 
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  907): checking for enable restriction...
,D/BluetoothManagerService(  907): checkBTEasState, ret=true
,I/BluetoothManagerService(  907): isBluetoothRestricted(): false
,D/BluetoothManagerService(  907): enable(): region ID = 6
D/BluetoothManagerService(  907): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 1
,W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1102
W/Settings:Agent(  907): Process.myUid(): 1000
,W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  907): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  907): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3841): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=3841, uid=10348
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 917
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/ActivityManager(  907): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3900 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3841): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 3841): reconnect: Base Package Name=com.test.thalitest, uid=10348
,I/jxcore-log( 3841): Radios toggled
I/jxcore-log( 3841): 
,D/PMS     (  907): acquireWL(4380aa88): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3841): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 3841): 
I/jxcore-log( 3841): Perf Test app loaded loaded
I/jxcore-log( 3841): 
I/Choreographer( 3841): Skipped 81 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3841): check test folder
I/jxcore-log( 3841): 
,I/jxcore-log( 3841): found test : ./testFindPeers.js
I/jxcore-log( 3841): 
,D/AdapterServiceConfig( 3900): Adding HeadsetService
D/AdapterServiceConfig( 3900): Adding A2dpService
D/AdapterServiceConfig( 3900): Adding HidService
D/AdapterServiceConfig( 3900): Adding HealthService
D/AdapterServiceConfig( 3900): Adding PanService
,D/AdapterServiceConfig( 3900): Adding GattService
,I/jxcore-log( 3841): found test : ./testSendData.js
I/jxcore-log( 3841): 
,W/linker  ( 3900): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3900): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  907): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43f62c60:true
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3900): make
,I/BluetoothAdapterState( 3900): Entering OffState
,I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3900): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  907): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  907): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapter( 1461): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41dd01e0
,D/BluetoothAdapter( 1461): onBluetoothServiceUp done
D/BluetoothAdapter( 1109): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41fa35a0
D/BluetoothAdapter( 1109): onBluetoothServiceUp done
D/BluetoothAdapter(  907): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@43f63618
,D/BluetoothAdapter(  907): onBluetoothServiceUp done
D/BluetoothAdapter( 1228): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c8a180
,D/BluetoothAdapter( 1228): onBluetoothServiceUp done
D/BluetoothAdapter( 1220): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41dd7340
,D/BluetoothAdapter( 1220): onBluetoothServiceUp done
,D/BluetoothAdapter( 1756): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42162720
,D/BluetoothAdapter( 1756): onBluetoothServiceUp done
D/BluetoothAdapter( 3841): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@426a9700
,D/BluetoothAdapter( 3841): onBluetoothServiceUp done
D/BluetoothAdapter( 3900): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b68c30
D/BluetoothAdapter( 3900): onBluetoothServiceUp done
,D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3900): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3900): Setting state to 11
I/BluetoothAdapterState( 3900): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3900): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  907): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3900): make
I/IntentController( 1109): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3900): StableState(): Entering Off State
,D/HeadsetService( 3900): Received start request. Starting profile...
D/HeadsetStateMachine( 3900): Version 1.6
,D/HeadsetStateMachine( 3900): make
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3926 uid=10037 gids={50037, 3002, 3001}
I/HeadsetStateMachine( 3900): setCurrentDevice, the latest mCurrentDevice is:null
I/BluetoothAdapterState( 3900): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/A2dpService( 3900): Received start request. Starting profile...
V/Avrcp   ( 3900): make
D/Avrcp   ( 3900): fillIntentFilter()
,I/QuickSettingBluetooth( 1109): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 3900): make
D/A2dpStateMachine( 3900): Enter Disconnected: -2
D/HidService( 3900): Received start request. Starting profile...
D/HealthService( 3900): Received start request. Starting profile...
,D/PanService( 3900): Received start request. Starting profile...
,D/BluetoothTethering(  907): supplyMessenger
D/BluetoothTethering(  907): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  907): got MESSAGE_CONNECT_PANSERVICE, call connect
,D/BluetoothTethering(  907): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 3900): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BtGatt.DebugUtils( 3900): handleDebugAction() action=null
D/BtGatt.GattService( 3900): Received start request. Starting profile...
,D/BtGatt.GattService( 3900): start()
V/BluetoothPbapService( 3900): Pbap Service onCreate
,V/BluetoothPbapService( 3900): Starting PBAP service
D/HtcBtWidget_BTWidgetProvider( 3926): onBTStateChanged() for widget: 
,D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 11
D/HtcBtWidget_BTWidgetProvider( 3926): updateWidget(context) for widget: 
,D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 11
E/BluetoothMasService( 3900): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3900): Add permission for SmsProvider.
V/BluetoothMasService( 3900): Starting MAS instances
D/Process (  907): killProcessQuiet, pid=3675
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 11
,I/MailMessageReceiver( 3900): reg:com.android.bluetooth.btservice.AdapterApp@41b5c198 with com.htc.util.mail.MailMessageReceiver@41b9c418
I/MailManager( 3900): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b9c418
,V/EmailUtils( 3900): Manager Instance is not NULL
,I/chromium( 3841): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/ActivityManager(  907): Killing 3675:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3944 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  907): interfaceAdded wlan0
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): wlan0 is not a tetherable iface, ignoring
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): interfaceAdded p2p0
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): p2p0 is not a tetherable iface, ignoring
D/PMS     (  907): releaseWL(4380aa88): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/libc    (  907): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/ActivityManager(  907): Recipient 3675
D/WifiService(  907): Client connection lost with reason: 4
,I/wpa_supplicant( 3958): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 3958): Add randomness: count=1 entropy=0
D/wpa_supplicant( 3958): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3958): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 3958): Get randomness: len=20 entropy=1
D/wpa_supplicant( 3958): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3958): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 3958): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 3958): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3958): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 3958): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3958): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3958): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3958): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3958): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3958): update_config=1
D/wpa_supplicant( 3958): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3958): device_name='Android_63cc'
D/wpa_supplicant( 3958): manufacturer='HTC'
D/wpa_supplicant( 3958): model_name='HTC_PHONE'
D/wpa_supplicant( 3958): model_number='1234'
D/wpa_supplicant( 3958): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3958): p2p_oper_reg_class=126
D/wpa_supplicant( 3958): p2p_oper_channel=36
D/wpa_supplicant( 3958): p2p_ssid_postfix='-Android_63cc'
,D/wpa_supplicant( 3958): persistent_reconnect=1
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 3958): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3958): nl80211: RFKILL status not available
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 95
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/wpa_supplicant( 3958): nl80211: Using driver-based roaming
D/wpa_supplicant( 3958): nl80211: TDLS supported
D/wpa_supplicant( 3958): nl80211: TDLS external setup
D/wpa_supplicant( 3958): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3958): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3958): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3958): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3958): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3958): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 3958): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3958): nl80211: Subscribe to mgmt frames with non-AP handle 0xb848f758
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb848f758
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3958): htc_wext_command_init +
E/wpa_supplicant( 3958): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 3958): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3958): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3958): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3958): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3958): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3958): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3958): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3958): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  907): interfaceLinkStateChanged p2p0, false
D/Tethering(  907): interfaceStatusChanged p2p0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged p2p0, false
D/Tethering(  907): interfaceStatusChanged p2p0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/EmailUtils( 3900): ============NULL aList========
,V/EmailUtils( 3900): <-getEmailAccountIdList
,V/BluetoothMasService( 3900): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 11
V/BluetoothMasService( 3900): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3900): Manager Instance is not NULL
D/EmailUtils( 3900): ============NULL aList========
,V/EmailUtils( 3900): <-getEmailAccountIdList
V/BluetoothSapService( 3900): Sap Service onCreate
,V/BluetoothSapService( 3900): initBinder
V/BluetoothSapService( 3900): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41ba1808
,V/BluetoothSapReceiver( 3900): BluetoothSapReceiver init
D/BluetoothSapService( 3900): setSapService()
V/BluetoothSapService( 3900): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3900): state: 12
,D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 11
D/BluetoothAdapterService( 3900): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3900): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3900): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3900): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3900): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 3900): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothAdapterService( 3900): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3900): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  907): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  907): killProcessQuiet, pid=3374
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/BluetoothMasReceiver( 3900): Bluetooth STATE CHANGED to 11
I/ActivityManager(  907): Killing 3374:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/qcom-bluetooth( 3966): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  907): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3969 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
D/WifiMonitor(  907): startMonitoring(wlan0) with mConnected = false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1109): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1109): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/qcom-bluetooth( 3984): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
I/wpa_supplicant( 3958): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 3958):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 3958):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3958):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3958): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3958): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3958): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3958): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3958): nl80211: Flush PMKIDs
E/wpa_supplicant( 3958): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 3958): State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 3985): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
I/ActivityManager(  907): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=3986 uid=10048 gids={50048}
,I/qcom-bluetooth( 3996): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4000): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4001): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4002): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/QuickSettingWifi( 1109): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3969): Received state change = 11
I/ActivityManager(  907): Recipient 3374
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcWiFiWidget_WiFiWidgetProvider( 3986): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 3986): updateWidget(context) for widget: 
,D/Process (  907): killProcessQuiet, pid=3698
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  907): Killing 3698:com.htc.calendar/u0a13 (adj 15): empty #17
,D/WifiService(  907): New client listening to asynchronous messages
I/ActivityManager(  907): Recipient 3698
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/wpa_supplicant( 3958): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3958): TDLS: Driver uses external link setup
D/wpa_supplicant( 3958): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 3958): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3958): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3958): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): Using existing control interface directory.
D/wpa_supplicant( 3958): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 3958): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 3958): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 3958): P2P: Own listen channel: 11
D/wpa_supplicant( 3958): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 3958): P2P: Add operating class 81
I/wpa_supplicant( 3958): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 3958): netlink: Operstate: linkmode=-1, operstate=5
,D/Process (  907): killProcessQuiet, pid=3598
D/wpa_supplicant( 3958): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3958): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 3958): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3958): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3958): disable_scan_offload=1
D/wpa_supplicant( 3958): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 3958): update_config=1
D/wpa_supplicant( 3958): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3958): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3958): manufacturer='HTC'
D/wpa_supplicant( 3958): model_name='HTC Desire 820'
D/wpa_supplicant( 3958): model_number='HTC Desire 820'
D/wpa_supplicant( 3958): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 3958): persistent_reconnect=1
D/wpa_supplicant( 3958): p2p_disabled=1
D/wpa_supplicant( 3958): hs20=1
D/wpa_supplicant( 3958): interworking=1
D/wpa_supplicant( 3958): Line: 18 - start of a new network block
D/wpa_supplicant( 3958): key_mgmt: 0x2
D/wpa_supplicant( 3958): priority=1 (0x1)
,D/wpa_supplicant( 3958): signinfail=0 (0x0)
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3598:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3598
,D/wpa_supplicant( 3958): Priority group 1
D/wpa_supplicant( 3958):    id=0 ssid='NG700'
I/wpa_supplicant( 3958): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 3958): nl80211: RFKILL status not available
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3958): nl80211: Using driver-based roaming
D/wpa_supplicant( 3958): nl80211: TDLS supported
D/wpa_supplicant( 3958): nl80211: TDLS external setup
,D/wpa_supplicant( 3958): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3958): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3958): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3958): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3958): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3958): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 3958): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3958): nl80211: Subscribe to mgmt frames with non-AP handle 0xb849f718
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3958): htc_wext_command_init +
I/wpa_supplicant( 3958): htc_wext_command_init -
I/wpa_supplicant( 3958): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 3958): Don't set 00 to countryID.conf
D/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 3958): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 3958): nl80211: Use separate P2P group interface
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3958): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3958): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3958): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3958): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3958): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3958): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false,
,I/qcom-bluetooth( 4006): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/qcom-bluetooth( 4007): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3900): btu_task pending for preload complete event
,I/wpa_supplicant( 3958): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 3958):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3958):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3958):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 3958): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3958): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3958): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3958): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3958): nl80211: Flush PMKIDs
,E/wpa_supplicant( 3958): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 3958): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3958): TDLS: Driver uses external link setup
D/wpa_supplicant( 3958): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 3958): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3958): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3958): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3958): Using existing control interface directory.
,I/wpa_supplicant( 3958): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3958): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 3958): Auto country group 1: ch36
I/wpa_supplicant( 3958): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3958): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 3958): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 3958): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3958): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 3958): Get randomness: len=20 entropy=0
V/RegulatoryObserver(  907): uevent:
V/RegulatoryObserver(  907): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  907): Regulatory Country Code:DE
D/wpa_supplicant( 3958): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 3958): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_907-2
D/wpa_supplicant( 3958): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 3958): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3958): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3958): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3958): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3958): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3958): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3958): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3958): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3958): nl80211: Event message available
D/wpa_supplicant( 3958): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 3958): nl80211: Regulatory domain change
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3958): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3958): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3958): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3958): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3958): P2P: Add operating class 81
D/wpa_supplicant( 3958): P2P: Add operating class 115
D/wpa_supplicant( 3958): P2P: Add operating class 116
D/wpa_supplicant( 3958): P2P: Add operating class 117
D/wpa_supplicant( 3958): P2P: Update channel list
D/wpa_supplicant( 3958): p2p0: Updating hw mode
D/WifiNative-wlan0(  907): doBoolean: SET_WIFI_ON 1
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 95
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3958): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3958): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3958): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3958): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3958): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 3958): wpa_supplicant_scan enter
I/wpa_supplicant( 3958): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3958): ap_scan=1 , scan_req =1
I/wpa_supplicant( 3958): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 3958): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): set wifi ON
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 3958): nl80211: Event message available
D/wpa_supplicant( 3958): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
,D/WifiNative-wlan0(  907):    returned true
V/RegulatoryObserver(  907): Start wifi-crda service to run crda.
V/RegulatoryObserver(  907): Country Code is DE
V/RegulatoryObserver(  907): Send broadcast country code message.
I/RegulatoryObserver(  907): Broadcast intent for crda country code: DE
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiNative-wlan0(  907): doString: DRIVER MACADDR
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  907): Loading config and enabling all networks
D/WifiNative-wlan0(  907): doString: LIST_NETWORKS
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): list_network_info: ret=0x1, pos=0xb84a2117 buf=0xb84a20e8
I/wpa_supplicant( 3958): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3958): 0	NG700	any	
I/IntentController( 1109): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  907):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  907): 0	NG700	any	
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 ssid
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 bssid
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'bssid'
D/WIFI_ICON( 1109): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 priority
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
,D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/HtcWiFiWidget_WiFiWidgetProvider( 3986): onWiFiStateChanged() for widget: 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'as_cert_file'
D/HtcWiFiWidget_WiFiWidgetProvider( 3986): updateWidget(context) for widget: 
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 3958): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 proto
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  907): Failed to look-up a string: W
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  907): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 group
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  907): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_PSK key
,D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT as cert null
,D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 limited
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 eap
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 phase2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 identity
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 password
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
,D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 engine
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'engine_id',
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 key_id
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 private_key
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 3958): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  907): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  907): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 3958): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3958): WPS: Set UUID for interface wlan0
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET manufacturer HTC
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 3958): manufacturer='HTC'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 3958): model_name='HTC Desire 820'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 3958): model_number='HTC Desire 820'
D/WifiNative-wlan0(  907):    returned true
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 3958): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET auto_interworking 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 3958): auto_interworking=0
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: STATUS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): SET_SCREEN_ON:On
I/wpa_supplicant( 3958): htc_wext_set_keepalive +
I/wpa_supplicant( 3958): htc_wext_set_keepalive: enable=0, type=2, interval=15
,D/wpa_supplicant( 3958): getPrivFuncNum +	
I/wpa_supplicant( 3958): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3958): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3958): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3958): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3958): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET ps 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 3958): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
W/Settings(  907): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  907): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): SETBAND: 0
D/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 3958): P2P: Add operating class 81
D/wpa_supplicant( 3958): P2P: Add operating class 115
D/wpa_supplicant( 3958): P2P: Add operating class 116
D/wpa_supplicant( 3958): P2P: Add operating class 117
D/wpa_supplicant( 3958): P2P: Update channel list
I/wpa_supplicant( 3958): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 3958): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3958): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 3958): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 3958): p2p_oper_reg_class=126
D/wpa_supplicant( 3958): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3958): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 3958): P2P: Own oper channel update failed: -1
,D/wpa_supplicant( 3958): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 3958): p2p_oper_channel=36
E/wpa_supplicant( 3958): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3958): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3958): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 3958): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 3958): P2P_OP_CH: save_config, class=126, ch=36
D/WifiP2pService(  907): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: BSS_FLUSH 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  907):    returned false
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 3958): wpa_supplicant_scan enter
D/WifiNative-wlan0(  907):    returned true
D/libc    (  907): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/QuickSettingWifi( 1109): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiMonitor(  907): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  907): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  907): P2pEnablingState
D/WifiNative-p2p0(  907): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 3958): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 3958): persistent_reconnect=1
I/wpa_supplicant( 3958): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET device_name Android_63cc
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 3958): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 3958): device_name='Android_63cc'
,I/wpa_supplicant( 3958): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 3958): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 3958): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 3958): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 3958): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 3958): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 3958): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
,D/wpa_supplicant( 3958): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3958): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 3958): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 3958): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 3958): Single channel concurrency preference: sta
I/wpa_supplicant( 3958): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doString: STATUS
W/WifiHW  (  907): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  907): doBoolean: P2P_FLUSH
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 3958): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 3958): P2P: Stopping find
D/wpa_supplicant( 3958): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 3958): P2P: State IDLE -> IDLE
I/wpa_supplicant( 3958): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  907):    returned true
,D/WifiNative-p2p0(  907): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 3958): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 3958): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiP2pService(  907): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2p socket connection successful
D/WifiP2pService(  907): P2pEnabledState
D/WifiP2pService(  907): sending p2p connection changed broadcast
D/WifiDisplayController(  907): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  907): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  907): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  907): mWfdEnabled :false, networkInfo.isConnected() :false
,D/WifiP2pService(  907): Send p2p flush in initializeP2pSettings
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doString: LIST_NETWORKS
W/WifiHW  (  907): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 3958): list_network_info: ret=0x22, pos=0xb84a210a buf=0xb84a20e8
I/wpa_supplicant( 3958): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3958): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  907):    returned network id / ssid / bssid / flags
,D/WifiNative-p2p0(  907): doBoolean: AP_SCAN 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "AP_SCAN 1"
,D/WifiNative-p2p0(  907):    returned false
,D/WifiNative-p2p0(  907): doBoolean: SET wifi_display 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 3958): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 3958): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 3958): WFD: Update WFD IE
I/wpa_supplicant( 3958): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3958): Recv Cmd 2: SET wifi_display
,D/WifiNative-p2p0(  907):    returned true
,D/WifiNative-p2p0(  907): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  907): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 3958): WFD: Set subelement 0
D/wpa_supplicant( 3958): WFD: Update WFD IE
I/wpa_supplicant( 3958): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3958): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  907):    returned true
,V/AudioService(  907): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  907):     Client/Owner: Client
V/AudioService(  907):     GroupId: 
V/AudioService(  907):     Passphrase: 
V/AudioService(  907):     SessionId: 0
V/AudioService(  907):     IP Address: }
,D/HtcEffectManagerBase(  907): onEventChanged id=5 status=false
,D/WifiDisplayController(  907): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  907):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  907):  primary type: 10-0050F204-5
D/WifiDisplayController(  907):  secondary type: null
D/WifiDisplayController(  907):  wps: 0
D/WifiDisplayController(  907):  grpcapab: 0
D/WifiDisplayController(  907):  devcapab: 0
D/WifiDisplayController(  907):  status: 3
D/WifiDisplayController(  907):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  907):  WFD CtrlPort: 0
D/WifiDisplayController(  907):  WFD MaxThroughput: 0
D/WifiP2pService(  907): sending p2p persistent groups changed broadcast
D/WifiP2pService(  907): InactiveState
D/WifiP2pService(  907): InactiveState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  907):  WFD CtrlPort: 7236
D/WifiP2pService(  907):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-12ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  907):  WFD CtrlPort: 7236
D/WifiP2pService(  907):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  907): Successfully set WFD info.
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/WifiDisplayController(  907): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  907):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  907):  primary type: 10-0050F204-5
D/WifiDisplayController(  907):  secondary type: null
D/WifiDisplayController(  907):  wps: 0
D/WifiDisplayController(  907):  grpcapab: 0
D/WifiDisplayController(  907):  devcapab: 0
D/WifiDisplayController(  907):  status: 3
D/WifiDisplayController(  907):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  907):  WFD CtrlPort: 7236
D/WifiDisplayController(  907):  WFD MaxThroughput: 50
D/HtcEffectManager(  907): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  907): convertEffect before=902
D/HtcEffectManager(  907): convertEffect after=902
,D/wpa_supplicant( 3958): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3958): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 3958): nl80211: if_removed already cleared - ignore event
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 3958): EAPOL: disable timer tick
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3958): nl80211: Event message available
D/wpa_supplicant( 3958): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 3958): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3958): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 3958): nl80211: Survey data missing
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3958): Sorted scan results
I/wpa_supplicant( 3958): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 3958): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 3958): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 3958): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 3958): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-84
I/wpa_supplicant( 3958): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 3958): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 3958): [NULL] 0c:bd:51:2b:c1:25 freq=2437 level=-89
I/wpa_supplicant( 3958): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 3958): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 3958): Add randomness: count=2 entropy=0
D/wpa_supplicant( 3958): Add randomness: count=3 entropy=1
D/wpa_supplicant( 3958): Add randomness: count=4 entropy=2
D/wpa_supplicant( 3958): Add randomness: count=5 entropy=3
D/wpa_supplicant( 3958): Add randomness: count=6 entropy=4
D/wpa_supplicant( 3958): Add randomness: count=7 entropy=5
D/wpa_supplicant( 3958): Add randomness: count=8 entropy=6
D/wpa_supplicant( 3958): Add randomness: count=9 entropy=7
D/wpa_supplicant( 3958): Add randomness: count=10 entropy=8
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=1 len=6,
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3958): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3958): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 3958): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1,
,D/wpa_supplicant( 3958): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3958): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: AP 64:7c:34:b0:03:6e type 0 added
,D/wpa_supplicant( 3958): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3958): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 3958): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3958): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 3958): WPS: AP[4] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3958): WPS: AP[5] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 3958): wpa_supplicant_pick_network+
I/wpa_supplicant( 3958): Selecting BSS from priority group 1
,I/wpa_supplicant( 3958): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3958): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3958): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 3958): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available,
D/wpa_supplicant( 3958):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 3958):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48,
I/wpa_supplicant( 3958): Start print parameters
I/wpa_supplicant( 3958): wpa_s->wpa_state is 3
,I/wpa_supplicant( 3958): wpa_s->br_have_IP is 0
I/wpa_supplicant( 3958): isConcurrentMode() is 0
I/wpa_supplicant( 3958): wpa_s->br_mirror_status is 0,
I/wpa_supplicant( 3958): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 3958): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 3958): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 3958): wpa_s->reassociate is 0
,I/wpa_supplicant( 3958): wpa_s->is_screen_on 1
I/wpa_supplicant( 3958): wpa_s->ifname wlan0,
I/wpa_supplicant( 3958): End print parameters
,I/wpa_supplicant( 3958): selected network = 1,
,D/wpa_supplicant( 3958): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84a04e8  current_ssid=0x0
D/wpa_supplicant( 3958): wlan0: Request association with c0:ff:d4:d3:aa:48,
,I/wpa_supplicant( 3958): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 3958): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 3958): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 3958): check if in concurrent case
,I/wpa_supplicant( 3958): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 3958): wpa_supplicant_associate, 1777
D/wpa_supplicant( 3958): wpa_supplicant_associate, 1780
D/wpa_supplicant( 3958): wpa_supplicant_associate, 1795
,D/wpa_supplicant( 3958): RSN: PMKSA cache search - network_ctx=0xb84a04e8 try_opportunistic=0
D/wpa_supplicant( 3958): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 3958): RSN: No PMKSA cache entry found
,I/wpa_supplicant( 3958): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 3958): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 3958): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 3958): nl80211: Set mode ifindex 22 iftype 2 (STATION),
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 6,
D/wpa_supplicant( 3958): nl80211: Unsubscribe mgmt frames handle 0xb849f718 (mode change)
D/wpa_supplicant( 3958): nl80211: Subscribe to mgmt frames with non-AP handle 0xb849f718
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Register frame type=0xd0 nl_handle=0xb849f718
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3958): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 3958):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3958):   * freq=2412
D/wpa_supplicant( 3958):   * Auth Type 0
D/wpa_supplicant( 3958):   * WPA Versions 0x2
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 3958): nl80211: Connect request send successfully
,D/wpa_supplicant( 3958): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3958): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 3958): reply (1197) for get BSS: id=0
I/wpa_supplicant( 3958): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3958): freq=5220
I/wpa_supplicant( 3958): level=-49
I/wpa_supplicant( 3958): tsf=0000000106222435
I/wpa_supplicant( 3958): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3958): ssid=NG7005g
I/wpa_supplicant( 3958): ====
I/wpa_supplicant( 3958): id=1
I/wpa_supplicant( 3958): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3958): freq=2412
I/wpa_supplicant( 3958): level=-48
I/wpa_supplicant( 3958): tsf=0000000106222468
I/wpa_supplicant( 3958): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3958): ssid=NG700
I/wpa_supplicant( 3958): ====
I/wpa_supplicant( 3958): id=2
I/wpa_supplicant( 3958): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 3958): freq=2412
I/wpa_supplicant( 3958): level=-49
I/wpa_supplicant( 3958): tsf=0000000106222459
I/wpa_supplicant( 3958): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 3958): ssid=01ABC
I/wpa_supplicant( 3958): ====
I/wpa_supplicant( 3958): id=3
I/wpa_supplicant( 3958): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 3958): freq=2427
I/wpa_supplicant( 3958): level=-77
I/wpa_supplicant( 3958): tsf=0000000106222481
I/wpa_supplicant( 3958): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 3958): ssid=Gonzos
I/wpa_supplicant( 3958): ====
I/wpa_supplicant( 3958): id=4
I/wpa_supplicant( 3958): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 3958): freq=2437
I/wpa_supplicant( 3958): level=-84
I/wpa_supplicant( 3958): tsf=0000000106222490
I/wpa_supplicant( 3958): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 3958): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 3958): ====
I/wpa_supplicant( 3958): id=5
I/wpa_supplicant( 3958): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 3958): freq=2462
I/wpa_supplicant( 3958): level=-87
I/wpa_supplicant( 3958): tsf=0000000106222500
I/wpa_supplicant( 3958): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 3958): ssid=UPC Wi-Free
I/wpa_supplicant( 3958): ====
I/wpa_supplicant( 3958): id=6
I/wpa_supplicant( 3958): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 3958): freq=2462
I/wpa_supplicant( 3958): level=-87
I/wpa_supplicant( 3958): tsf=0000000106222519
I/wpa_supplicant( 3958): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 3958): ssid=UPC5999698,
I/wpa_supplicant( 3958): ====
I/wpa_supplicant( 3958): id=7
I/wpa_supplicant( 3958): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 3958): freq=2437
I/wpa_supplicant( 3958): level=-89
I/wpa_supplicant( 3958): tsf=0000000106222531
I/wpa_supplicant( 3958): flags=
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 106222435, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 106222468, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -49, frequency: 2412, timestamp: 106222459, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 106222481, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -84, frequency: 2437, timestamp: 106222490, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 106222500, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2462, timestamp: 106222519, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 106222531, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (9) end of scan result ==
D/WifiStateMachine(  907): 8: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 106222510, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 9 to mScanResults
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 3958): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3958): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3958): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3958): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 3958): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 3958): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 3958): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3958): nl80211: Event message available
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 3958): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 3958): nl80211: Connect event
D/wpa_supplicant( 3958): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 3958): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3958): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 3958): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3958): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3958): Add randomness: count=11 entropy=9
I/wpa_supplicant( 3958): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 3958): TDLS: Remove peers on association
D/wpa_supplicant( 3958): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 3958): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 3958): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 3958): htc_wext_set_keepalive +
I/wpa_supplicant( 3958): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 3958): getPrivFuncNum +	
I/wpa_supplicant( 3958): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3958): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3958): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3958): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3958): Get randomness: len=32 entropy=10
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  907): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Associated
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  907): BSSID was changed, update WiFi database
I/wpa_supplicant( 3958): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb849f9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 3958):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 3958): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 3958): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f1bb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 3958):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 3958): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 3958): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3958): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3958): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 3958): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 3958): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 3958): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 3958): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3958): set send_ind_to_ndc = 0
I/wpa_supplicant( 3958): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3958): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3958): EAPOL: External notification - portValid=1
D/wpa_supplicant( 3958): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 3958): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 3958): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 3958): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3958): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 3958): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 3958): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3958): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 3958): EAPOL authentication completed successfully
I/wpa_supplicant( 3958): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 79
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/wpa_supplicant( 3958): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3958): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3958): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
,I/IntentController( 1109): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1109): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1756/10178)
,D/WISPrService( 3325): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3325): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiService(  907): New client listening to asynchronous messages
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  907): doBoolean: MOBILE_TYPE Unknown
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): WiFioffload: update mobile network = Unknown
D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): Power_Mode_Type mode = 1
I/wpa_supplicant( 3958): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
,E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/PMS     (  907): acquireWL(4254d4d0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421145a8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421145a8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1109): receive.wifiConnect:false wifiAPname:null elapse:0
,I/bt-btu  ( 3900): btu_task received preload complete event
,D/bt-btm  ( 3900): btm_acl_device_down
D/bt-btm  ( 3900): btm_acl_reset_paging
,D/bt-btm  ( 3900): btm_acl_set_discing
,I/bt-btm  ( 3900): btm_reset_complete
,I/bt-btm  ( 3900): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3900): Start reading local supported commands
,D/bt-btm  ( 3900): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3900): BTM reads next extended features page (1)
,D/bt-btm  ( 3900): BTM reads next extended features page (2)
,D/bt-btm  ( 3900): BTM reached last extended features page (2)
,D/bt-btm  ( 3900): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3900): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3900): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3900): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3900): btm_read_ble_wl_size 
D/bt-btm  ( 3900): btm_read_white_list_size_complete 
,D/bt-btm  ( 3900): btm_get_ble_buffer_size 
D/bt-btm  ( 3900): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3900): btm_read_ble_local_supported_features 
,D/bt-btm  ( 3900): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3900): btm_reset_ctrlr_complete: max_page_number: 2
,D/bt-btm  ( 3900): btm_decode_ext_features_page page: 0
,D/bt-btm  ( 3900): Local supported ACL packet types: 0xcc18
,D/bt-btm  ( 3900): Local supported SCO packet types: 0x038f
,D/bt-btm  ( 3900): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3900): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3900):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3900): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3900): BTM_SetInquiryMode
I/bt-btm  ( 3900): BTM_SetPageScanType
I/bt-btm  ( 3900): BTM_SetInquiryScanType
D/bt-btm  ( 3900): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3900): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3900): BTM_BleLoadLocalKeys
D/bt-btm  ( 3900): BTM_BleLoadLocalKeys
I/bt-btm  ( 3900): BTM_Sec: application registered
E/bt-btm  ( 3900): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fc3941 
I/bt-btm  ( 3900): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3900): SMP_Register state=0
E/bt-btm  ( 3900): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fc3941 
I/bt-btm  ( 3900): BTM_Sec: application registered
D/bt-btm  ( 3900): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3900): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3900): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3900): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3900): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3900): BTM_RegBusyLevelNotif
I/bt-att  ( 3900): GATT_Register
D/bt-att  ( 3900): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3900): allocated gatt_if=3
I/bt-att  ( 3900): GATT_StartIf gatt_if=3
D/bt-att  ( 3900): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3900): gatt_find_the_connected_bda found=0 found_idx=7
,I/bt-btm  ( 3900): Calling BTA_HhEnable
,E/bt-btif ( 3900): Calling BTA_HhEnable
I/bt-btm  ( 3900): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
E/bt-btif ( 3900): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3900): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3900): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:1 len:14
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3900): BTM_AllocateSCN
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3900): BTM_AllocateSCN
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btm  ( 3900): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3900):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3900):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3900):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3900):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3900):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3900):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3900):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3900):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3900): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3900): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
D/bt-avp  ( 3900): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3900): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btm  ( 3900): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3900):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3900):                : sec: 0x80,, service name [] (up to 21 chars saved)
D/bt-btm  ( 3900): BTM_GetHCIConnHandle
I/bt-btm  ( 3900): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3900): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3900): BTM_GetHCIConnHandle
I/bt-btm  ( 3900): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3900): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3900): BTM_GetHCIConnHandle
I/bt-btm  ( 3900): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3900): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3900): BTM_GetHCIConnHandle
I/bt-btm  ( 3900): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3900): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3900): BTM_GetHCIConnHandle
I/bt-btm  ( 3900): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3900): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3900): GATT_Register
D/bt-att  ( 3900): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3900): allocated gatt_if=4
I/bt-att  ( 3900): GATT_StartIf gatt_if=4
D/bt-att  ( 3900): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3900): gatt_find_the_connected_bda found=0 found_idx=7
I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3900): Scan Mode:20
I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3900): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:8 len:30
D/BluetoothAdapter( 3900): getBluetoothService(): entry
D/BluetoothAdapter( 3900): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3900): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41bac6c0
D/BluetoothDevice( 3900): getService : Register callback
D/BluetoothAdapterProperties( 3900): Adding bonded device:B4:CE:F6:AB:A4:6A
D/BluetoothAdapterProperties( 3900): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 3900): Adding bonded device:34:FC:EF:9D:93:0B
D/BluetoothAdapterProperties( 3900): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3900): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3900): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3900): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3900): Remote class is:5898764
I/bt-btif ( 3900): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3900): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3900): Remote class is:5898764
I/bt-btif ( 3900): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3900): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
D/BluetoothRemoteDevices( 3900): Remote class is:5898764
I/bt-btif ( 3900): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3900): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 3900): Remote class is:5898764
,I/bt-btif ( 3900): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3900): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothRemoteDevices( 3900): Remote class is:5898764
,I/bt-btif ( 3900): BTA_JvEnable
I/bt-btm  ( 3900): BTM_ReadConnectability
,I/bt-btm  ( 3900): BTM_ReadDiscoverability
I/bt-btm  ( 3900): BTM_SetDiscoverability
I/bt-btm  ( 3900): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3900): br_edr_supported=0x2
I/bt-btm  ( 3900): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3900): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3900): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3900): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3900): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3900): BTM_SetConnectability
I/bt-btm  ( 3900): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3900): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3900): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3900): BTM_SetDiscoverability
,I/bt-btm  ( 3900): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3900): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3900): br_edr_supported=0x0
I/bt-btm  ( 3900): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3900): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3900): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3900): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3900): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3900): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
,I/bt-btm  ( 3900): BTM_SetConnectability
I/bt-btm  ( 3900): btm_ble_set_connectability mode=0x0 combined_mode=0x0,
I/bt-btm  ( 3900): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3900): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3900): bta_pan_co_init
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3900): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3900):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374,
I/bt-btm  ( 3900):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3900): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3900):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3900): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373,
I/bt-btm  ( 3900):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
E/bt_mct  ( 3900): hci lib postload completed
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:10
,I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btif ( 3900): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3900): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3900): ScanMode =  20
D/BluetoothAdapterProperties( 3900): State =  11
I/bt-btif ( 3900): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3900): Setting state to 12
I/BluetoothAdapterState( 3900): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterService( 3900): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btm  ( 3900): BTM_SetDiscoverability
I/bt-btm  ( 3900): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3900): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3900): br_edr_supported=0x0
I/bt-btm  ( 3900): mode == BTM_BLE_NON_DISCOVERABLE ,
I/bt-btm  ( 3900): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3900): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3900): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3900): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3900): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3900): BTM_SetConnectability
I/bt-btm  ( 3900): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3900): new flag=0x0 cur flag=0x4
,D/bt-btm  ( 3900): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3900): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3900): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3900): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  907): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 3900): Entering On State
D/BluetoothHeadset( 1109): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3900): Scan Mode:21
I/bt-btif ( 3900): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 3900): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3900): Discoverable Timeout:120
D/BluetoothAdapterService(1102471360)( 3900): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3900): getBondedDevices: length=5
,D/BluetoothHeadset( 1220): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1109): Proxy object connected
I/QuickSettingMiniLite( 1109): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e66490
D/BluetoothPan(  907): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1220): Proxy object connected
,D/BluetoothHeadset( 1220): onBluetoothStateChange: up=true
,D/BluetoothPan(  907): BluetoothPAN Proxy object connected
D/BluetoothAdapterService(1102471360)( 3900): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3900): getBondedDevices: length=5
D/BluetoothHeadset(  907): onBluetoothStateChange: up=true
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset( 1220): Proxy object connected
,D/BluetoothPhoneService( 1220): BluetoothHeadset onServiceConnected
,D/BluetoothA2dp(  907): onBluetoothStateChange: up=true
D/BluetoothHeadset(  907): Proxy object connected
,D/BluetoothManagerService(  907): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1109): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothAdapter( 1220): 1103785936: getState(). Returning 12
D/wpa_supplicant( 3958): EAPOL: startWhen --> 0
,D/wpa_supplicant( 3958): EAPOL: disable timer tick
,D/BluetoothAdapter(  907): 1111966336: getState(). Returning 12
,V/BluetoothPbapReceiver( 3900): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3900): ***********state = 12
,D/BluetoothA2dp(  907): Proxy object connected
,D/BluetoothAdapter(  907): 1111966336: getState(). Returning 12
,D/BluetoothMasReceiver( 3900): Bluetooth STATE CHANGED to 12
,V/BluetoothSapReceiver( 3900): SapReceiver onReceive 
V/BluetoothSapReceiver( 3900): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3900):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3900): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  907): acquireWL(42be04b0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3325 1000 null
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/BluetoothManagerService(  907): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 12
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 12
V/BluetoothMasService( 3900): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3900): Manager Instance is not NULL
,D/HtcBtWidget_BTWidgetProvider( 3926): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3926): updateWidget(context) for widget: 
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c93488:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): releaseWL(42be04b0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  907): acquireWL(43b1ef08): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3325 1000 null
I/LocationAgent( 3325): new LocationAgent instance!!
D/HtcTagManager( 3325): HtcTagManager construction complete
D/EmailUtils( 3900): ============NULL aList========
V/EmailUtils( 3900): <-getEmailAccountIdList
V/BluetoothSapService( 3900): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3900): state: 12
D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 12
W/ContextImpl( 3900): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 3900): Starting SAP server process
V/BluetoothPbapService( 3900): Handler(): got msg=1
D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
V/BluetoothPbapService( 3900): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3900): Pbap Service initSocket
V/BluetoothMasService( 3900): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 3900): BluetoothMns: isEmailEnabled: true
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothInputDevice( 3325): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothMasService( 3900): Map_prev 1
D/BluetoothAdapter( 3900): getBluetoothService(): entry
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 7
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3900): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
D/BluetoothInputDevice( 3325): BluetoothInputDevice(): Binding service...
E/BluetoothServiceJni( 3900): SOCK FLAG = 1 ***********************
I/bt-btif ( 3900): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btif ( 3900): BTA_JvRfcommStartServer
I/bt-btm  ( 3900): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3900):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3900): Succeed to create listening socket 
,V/BluetoothPbapService( 3900): Accepting socket connection...
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothAdapter( 3900): getBluetoothService(): entry
W/BluetoothAdapter( 3900): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3900): SOCK FLAG = 3 ***********************
I/bt-btif ( 3900): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btif ( 3900): BTA_JvRfcommStartServer
I/bt-btm  ( 3900): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3900):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothPan( 3325): BluetoothPan()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothAdapter( 3900): getBluetoothService(): entry
W/BluetoothAdapter( 3900): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 8
E/BluetoothServiceJni( 3900): SOCK FLAG = 3 ***********************
I/bt-btif ( 3900): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btif ( 3900): BTA_JvRfcommStartServer
I/bt-btm  ( 3900): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3900):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
,D/BluetoothPan( 3325): BluetoothPan(): Binding service...
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothAdapter( 1109): 1105183608: getState(). Returning 12
D/BluetoothMap( 3325): Create BluetoothMap proxy object
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 9
E/BluetoothMap( 3325): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothSap( 3325): BluetoothSap() call bindService
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 10
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothAdapter( 1109): 1105183608: getState(). Returning 12
D/BluetoothPbap( 3325): BluetoothPbap()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 11
I/QuickSettingBluetooth( 1109): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1109): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
,D/BluetoothPbap( 3325): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 3325): BluetoothA2dp()
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 12
D/BluetoothSapService( 3900): Sap_prev 1
D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
D/BluetoothA2dp( 3325): BluetoothA2dp(): Binding service...
V/BluetoothSapService( 3900): SAP Service startRfcommListenerThread
V/BluetoothSapService( 3900): Sap Service initRfcommSocket
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3900): getBluetoothService(): entry
,W/BluetoothAdapter( 3900): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3900): SOCK FLAG = 3 ***********************
I/bt-btif ( 3900): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btif ( 3900): BTA_JvRfcommStartServer
I/bt-btm  ( 3900): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3900):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
V/BluetoothSapService( 3900): Succeed to create listening socket 
D/BluetoothHeadset( 3325): BluetoothHeadset()
V/BluetoothSapService( 3900): Accepting socket connection...
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 13
D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
D/BluetoothHeadset( 3325): BluetoothHeadset(): Binding service...
,D/BluetoothAdapter( 1109): 1105183608: getState(). Returning 12
,I/QuickSettingMiniLite( 1109): updateLiteState:no connect device!
,D/HtcTagManager( 3325): startProxy
,W/ContextImpl( 3325): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3325): LocalBluetoothProfileManager construction complete
V/TAG     ( 3900): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 3900): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41ba2f48
,D/DockEventReceiver( 3325): finishStartingService: stopping service
D/BluetoothPan( 3325): BluetoothPAN Proxy object connected
D/PanProfile( 3325): Bluetooth service connected
D/BluetoothInputDevice( 3325): Proxy object connected
,D/HidProfile( 3325): Bluetooth service connected
,V/BluetoothPbapService( 3900): Pbap Service onBind
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3969): onCreate: going to find gatt base service first.
,D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
,D/BluetoothA2dp( 3325): Proxy object connected
,D/A2dpProfile( 3325): Bluetooth service connected
,I/BluetoothFtpService( 3900): Ftp Service onCreate
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 12
,D/BluetoothMasReceiver( 3900): Bluetooth STATE CHANGED to 12
,D/BluetoothHeadset( 3325): Proxy object connected
,D/HeadsetProfile( 3325): Bluetooth service connected
D/BluetoothAdapter( 3900): getBluetoothService(): entry
,W/BluetoothAdapter( 3900): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3325): 1104068008: getState(). Returning 12
E/BluetoothServiceJni( 3900): SOCK FLAG = 0 ***********************
,I/bt-btif ( 3900): BTA_JvCreateRecordByUser
D/BluetoothFtpService( 3900): Ftp_prev 1
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btif ( 3900): BTA_JvRfcommStartServer
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
I/bt-btm  ( 3900): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3900):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@442e55a0:true
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/BtOppRfcommListener( 3900): Accept thread started.
D/BluetoothAdapter( 3900): getBluetoothService(): entry
,W/BluetoothAdapter( 3900): getBluetoothService() called with no BluetoothManagerCallback
,D/SapServerProfile( 3325): Bluetooth service connected
D/BluetoothPbap( 3325): Proxy object connected
E/BluetoothServiceJni( 3900): SOCK FLAG = 1 ***********************
,I/bt-btif ( 3900): BTA_JvCreateRecordByUser
D/PbapServerProfile( 3325): Bluetooth service connected
D/bt-sdp  ( 3900): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3900): Write Extended Inquiry Response to controller
I/bt-btif ( 3900): BTA_JvRfcommStartServer
I/bt-btm  ( 3900): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
,I/bt-btm  ( 3900):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,D/PMS     (  907): releaseWL(43b1ef08): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
V/BluetoothFtpService:RfcommSocketAcceptThread( 3900): Run Accept thread
D/[HTC_BLE][Constants]( 3969):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3969):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3969):  + discoverServicesOnBonded = false
D/BluetoothAdapter( 3900): 1102489536: getState(). Returning 12
V/BluetoothMasService( 3900): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3900): Manager Instance is not NULL
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3969):  + Google LE service found. Using BaseLeProfilesGoogle.
D/EmailUtils( 3900): ============NULL aList========
,V/EmailUtils( 3900): <-getEmailAccountIdList
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3969): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6c148
D/[HTC_BLE][Constants]( 3969): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3969): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3969): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3969): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3969): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
D/[HTC_BLE][Constants]( 3969): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,D/BluetoothMasService( 3900): Map_prev 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3969): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3325): onServiceConnected,
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3969): Received state change = 12
D/HtcTagProfile( 3325): setup proxy
D/HtcPxpProfile( 3325): setup proxy
,D/HtcFmpProfile( 3325): setup proxy
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3969): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3969): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6c148
,D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3969): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6c148
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3969): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6c148, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b77130
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3969): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6c148
,W/System.err(  907): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425c1b88:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3712): new LocationAgent instance!!
,D/HtcTagManager( 3712): HtcTagManager construction complete
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/RingtoneManager( 3969): getExternalStorageState=mounted
,D/BluetoothInputDevice( 3712): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 14
D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/BluetoothInputDevice( 3712): BluetoothInputDevice(): Binding service...
,D/BluetoothPan( 3712): BluetoothPan()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 15
D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/BluetoothPan( 3712): BluetoothPan(): Binding service...
,W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3969):  + mAlertUri: content://settings/system/alarm_alert
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3969): BleProfilesStateMachine is initialized...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3969): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3969): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3969): initScanModeInterface: true
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3969): loadDeviceConfiguration() init =true
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3969):  + mTag.getPrimaryDeviceList() = []
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42648428:true
D/[HTC_BLE][Constants]( 3969):  + defaultServices = 0
D/BluetoothMap( 3712): Create BluetoothMap proxy object
D/[HTC_BLE][Constants]( 3969):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3969):  + discoverServicesOnBonded = false
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothMap( 3712): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  907): Registered receivers: 16
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 17
,D/BluetoothSap( 3712): BluetoothSap() call bindService
,D/BluetoothPbap( 3712): BluetoothPbap()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 18
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3969): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b77130
,W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/BluetoothPbap( 3712): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 3712): BluetoothA2dp()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 19
D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/BluetoothA2dp( 3712): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3712): BluetoothHeadset()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 20
D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/BluetoothHeadset( 3712): BluetoothHeadset(): Binding service...
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,D/HtcTagManager( 3712): startProxy
,W/ContextImpl( 3712): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3712): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3712): setBluetoothStateOn
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/HtcTagManager( 3712): startProxy
D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
D/BluetoothAdapterService(1102471360)( 3900): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3900): getBondedDevices: length=5
D/BluetoothAdapter( 3712): getBluetoothService(): entry
D/BluetoothAdapter( 3712): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3712): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41bac618
D/BluetoothDevice( 3712): getService : Register callback
E/BluetoothDevice( 3712): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
D/HtcTagManager( 3712): addHtcTagProfiles
,E/BluetoothDevice( 3712): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/HtcTagManager( 3712): addHtcTagProfiles
,E/BluetoothDevice( 3712): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/HtcTagManager( 3712): addHtcTagProfiles
,E/BluetoothDevice( 3712): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/HtcTagManager( 3712): addHtcTagProfiles
,E/BluetoothDevice( 3712): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/HtcTagManager( 3712): addHtcTagProfiles
,D/BluetoothInputDevice( 3712): Proxy object connected
,D/HidProfile( 3712): Bluetooth service connected
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/BluetoothPan( 3712): BluetoothPAN Proxy object connected
D/PanProfile( 3712): Bluetooth service connected
D/SapServerProfile( 3712): Bluetooth service connected
D/BluetoothPbap( 3712): Proxy object connected
D/PbapServerProfile( 3712): Bluetooth service connected
,D/BluetoothA2dp( 3712): Proxy object connected
D/A2dpProfile( 3712): Bluetooth service connected
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/BluetoothHeadset( 3712): Proxy object connected
D/HeadsetProfile( 3712): Bluetooth service connected
,D/BluetoothAdapter( 3712): 1102524192: getState(). Returning 12
,D/HtcTagManager( 3712): onServiceConnected
D/HtcTagProfile( 3712): setup proxy
D/HtcPxpProfile( 3712): setup proxy
,D/HtcFmpProfile( 3712): setup proxy
,I/SensorManager(  907): mEventCount = 1050
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421f16b8
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  907): pid=907, uid=1000
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
W/BatSI   (  907): Couldn't get kernel wake lock stats
,V/LightsService(  907): setLight #0: color=#0
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421f16b8, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423bca10
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42624610
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97",
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): WiFioffload: SignalStrength: =97,
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): Power_Mode_Type mode = 0
,I/wpa_supplicant( 3958): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4254d4d0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3958): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): WiFi gateway: 0x101a8c0
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -48, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20428 delay=15s
,I/IntentController( 1109): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1109): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1756/10178)
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  907): WAN detection
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/WISPrService( 3325): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@42479e80
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/QuickSettingWifi( 1109): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  907): acquireWL(4276b738): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=100 [1][1][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4276b738): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 390ms
D/PMS     (  907): nativeSetInteractive:false
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43ad5118)
D/NfcService( 1228): ScreenObserver: OFF
I/IntentController( 1109): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1228): applyRouting - 0
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): OOBE c monitor 11
D/PMN     (  907): wakingUp
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=3841
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
,D/NfcService( 1228): applyRouting -2
W/ResourceType( 3841): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3841): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b5c168 VFEDH.C. .F...... 0,0-720,1134 #64}
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): acquireWL(44091450): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  907): releaseWL(44091450): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/PMS     (  907): acquireWL(4309c7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMN     (  907): onScreenOn
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1228): applyRouting - 0
D/NfcService( 1228): applyRouting -2
,D/MtpService( 2520): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/AutoSetting( 1364): receiver - intent: android.intent.action.USER_PRESENT
,D/MtpService( 2520): [MTP][onReceive]-
D/PMS     (  907): releaseWL(4309c7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): acquireWL(43fc9150): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): releaseWL(43fc9150): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/jxcore-log( 3841): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3841): 
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/AutoSetting( 1364): service - onCreate()
,D/AutoSetting( 1364): service - AddressCache: using context: com.htc.Weather
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/ClockThread( 1109): stop update clock
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/TetherSettings( 3325): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3325): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3325): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3325): Cust_ConnectToPC   : spcsc>false
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20429 delay=15s
D/        ( 3325): Cust_ConnectToPC   : IPT>true
D/        ( 3325): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3325): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3325): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3325): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1364): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  907): request 424879c0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3958): SET_SCREEN_ON:On
I/wpa_supplicant( 3958): htc_wext_set_keepalive +
I/wpa_supplicant( 3958): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3958): getPrivFuncNum +	
I/wpa_supplicant( 3958): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3958): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3958): htc_wext_set_keepalive - ret = 0
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
I/wpa_supplicant( 3958): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3958): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/PSReceiver( 3325): onReceive:android.intent.action.USER_PRESENT
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-48 , oldRssi= -200
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3958): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
I/SmartNS_PSService( 3325): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3325): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3325):  defaultType:0
D/WIFI_ICON( 1109): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1109): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  373): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
W/ActivityManager(  907): Disable JIT of com.htc.bgp
,I/ActivityManager(  907): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4089 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/NetworkPolicy(  907): updateScreenOn: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(434610d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
,D/PMS     (  907): releaseWL(434610d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3969): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3969): onScreenOn: 1450100318331
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3969): onScreenOn: 1450100318331
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423bca10
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423bca10, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42624610
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(43bd7858): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20429 mDataStallAlarmIntent=PendingIntent{43847d80: PendingIntentRecord{43beeae0 android broadcastIntent}}
D/PMS     (  907): releaseWL(43bd7858): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 3958): SET_SCREEN_ON:Off
I/wpa_supplicant( 3958): htc_wext_set_keepalive +
I/wpa_supplicant( 3958): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3958): getPrivFuncNum +	
I/wpa_supplicant( 3958): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3958): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3958): get_ip_address source addr = c0a80176
I/wpa_supplicant( 3958): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 3958): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/PMS     (  907): acquireWL(4378fcf0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,D/NetworkPolicy(  907): updateScreenOn: false
I/CalendarProvider2( 4089): Created com.android.providers.calendar.CalendarAlarmManager@41b8faf8(com.android.providers.calendar.HtcCalendarProvider@41b77e80)
D/ContactMessageStore( 1220): start background delete task...
D/ContactMessageStore( 1220): size: 0 , 0
D/ContactMessageStore( 1220): Background delete complete
,D/wpa_supplicant( 3958): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/CalendarProvider2( 4089): wait start:true
D/PMS     (  907): releaseWL(4378fcf0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/CalendarProvider2( 4089): wait end:false
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4110 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 4110): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): acquireWL(43412878): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
D/PMS     (  907): releaseWL(43412878): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/SmartSyncUtils( 4110): isEpsOn(), nState = 0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3969): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3969): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3969): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3969): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3969): onScreenOff
D/AutoSetting( 1364): service - mHandler: cancel location update
,D/AutoSetting( 1364): service -           changes count: 0
D/PMS     (  907): acquireWL(43c00cf8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4110 1000 null
,D/SmartSyncUtils( 4110): getMobilePolicyEnabled, result = true
D/PMS     (  907): releaseWL(43c00cf8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4110): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4110): isEpsOn(), nState = 0
D/SmartSyncUtils( 4110): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4110): getMobilePolicyEnabled, result = true
D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42624610
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42624610, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42624610, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42624610
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4262c0a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4262c0a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,E/BTIF_CORE( 3900): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3900): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3900): Wake lock released
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4131 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1246): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(43ffbce8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1756/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1246/10075)
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (3763/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1774/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3413/10051)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (3763/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1,
D/libc    (  365): [NET] +++++ res_nsend xid =71f +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43c29f20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=100 [2][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 115
D/libc    (  365): [NET]res_nsend:resplen=104
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/MusicStore( 4131): Database version: 95
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4131): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4153 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/PMS     (  907): releaseWL(425a16a8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/DotMatrix( 1527): [EventService] EVENT_RESET_THEME_TIMESTAMP
I/FeedActionBar( 1246): updateLastUpdatedTime(in String) LAST UPDATED 14:37
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1527): [EventService] isTheSameDay:false,timestamp is early than today:true
,I/IntentController( 1109): receive(android.intent.action.TIME_SET,4,false)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4131): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(43900948): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 907 1000 WorkSource{10096}
D/PMS     (  907): acquireWL(425a16a8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 907 1000 WorkSource{10096}
,I/CalendarProvider2( 4089): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4089): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(442d5070): PARTIAL_WAKE_LOCK  *sync*/com.htc.showme/com.htc.showme/***** 0x1 907 1000 WorkSource{10082}
,I/ActivityManager(  907): Start proc com.htc.showme for service com.htc.showme/.sync.SyncService: pid=4171 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(4421b790): PARTIAL_WAKE_LOCK  *sync*/gmail-ls/com.google/***** 0x1 907 1000 WorkSource{10107}
,I/ActivityManager(  907): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=4183 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  907): releaseWL(43c29f20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4131): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4407ec60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4131): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4131): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4131, uid=10154, userID:0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  907): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  907): NTP server returned: 1450100319003 (Mon Dec 14 14:38:39 CET 2015) reference: 110689 certainty: 9 system time offset: -258
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4407ec60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(425c66d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(425c66d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(423ec1f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  907): reportAGpsStatus with type = 12090status = 30767ipAddr = [B@41fd3840ssid = nullpassword = null
D/GpsLocationProvider(  907): xtraDownloadRequest
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  907): [handleMessage] INJECT_NTP_TIME_FINISHED
D/GpsLocationProvider(  907): [handleMessage] REPORT_AGPS_STATUS
D/GpsLocationProvider(  907): handleReportAgpsStatus with type = 12090status = 30767ipAddr = [B@41fd3840ssid = password = null
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 12090
D/GpsLocationProvider(  907): reportAGpsStatus agpsConnInfo is null for type 12090
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/DelayedSyncController( 4153): Delaying sync.
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(423ec1f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
W/GAV2    ( 4183): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/[AppShowMeDebug]SyncAdapter( 4171): onPerformSync() 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42503ab8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET] +++++ res_nsend xid =332a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): killProcessQuiet, pid=3236
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.showme (4171/10082)
D/PMS     (  907): releaseWL(43900948): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/MediaRouterService(  907): Client com.google.android.music (pid 4131): Registered
I/ActivityManager(  907): Killing 3236:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/[AppShowMeDebug]CheckUpdateTask( 4171): check and download urlSKUBased = http://showme.htctouch.com/prod/LU15A_CTH=401/; urlDeviceBased = http://showme.htctouch.com/prod/LU15A_CTH/; urlSKUTestDeviceBased = http://showme-test.htc.com.tw/testpub/LU15A_CTH=401/; urlTestDeviceBased = http://showme-test.htc.com.tw/testpub/LU15A_CTH/
I/MediaRouter( 4131): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Recipient 3236
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,I/NetworkMonitor( 4131): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4239d970): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4131/10154)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4217 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4171): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 4
D/libc    ( 4171): [NET] getaddrinfo-,err=8
D/libc    ( 4171): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    ( 4171): [NET] getaddrinfo-, 1
D/libc    ( 4171): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7806 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958),: send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/MediaRouter( 4131): getSelectedRoute
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/NetworkMonitor( 4131): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4131/10154)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42503ab8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43fa8bd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(43fa8bd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/Process (  907): killProcessQuiet, pid=3733
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4131, uid=10154, userID:0
I/ActivityManager(  907): Killing 3733:com.google.android.partnersetup/u0a31 (adj 15): empty #17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Recipient 3733
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): env,ironment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=246
D/libc    (  365): [NET]res_queryN: exit 3, ancount=6
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4171): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 4217): ACRA is enabled for com.facebook.katana, intializing...
D/PMS     (  907): releaseWL(4239d970): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/ACRA    ( 4217): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4217): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,W/SystemClassLoaderAdder( 4217): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4217): Preparing secondary program dexes.
,V/DexLibLoader( 4217): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4217): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4217): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4217): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4217): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4217): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4217): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4217): Dex already copied
D/OdexVerifier( 4217): Odex verification is skipped.
,V/DexLibLoader( 4217): Creating class loader
,V/DexLibLoader( 4217): Finished creating class loader
V/DexLibLoader( 4217): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4217): Dex already copied
D/OdexVerifier( 4217): Odex verification is skipped.
,V/DexLibLoader( 4217): Creating class loader
,V/DexLibLoader( 4217): Finished creating class loader
V/DexLibLoader( 4217): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4217): Dex already copied
D/OdexVerifier( 4217): Odex verification is skipped.
,V/DexLibLoader( 4217): Creating class loader
,V/DexLibLoader( 4217): Finished creating class loader
V/DexLibLoader( 4217): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4217): Dex already copied
D/OdexVerifier( 4217): Odex verification is skipped.
,V/DexLibLoader( 4217): Creating class loader
,V/DexLibLoader( 4217): Finished creating class loader
,V/DexLibLoader( 4217): Verifying classes from secondary dexes.
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/DexLibLoader( 4217): DexLibLoader.ensureDexLoaded took 135 ms
,I/Gmail   ( 4183): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/libc    ( 4171): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 4
,D/libc    ( 4171): [NET] getaddrinfo-,err=8
D/libc    ( 4171): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    ( 4171): [NET] getaddrinfo-, 1
D/libc    ( 4171): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =bda3 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=6
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4171): [NET] getaddrinfo_proxy-, success
,I/Gmail   ( 4183): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4183): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4183): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gm (4183/10107)
,I/[AppShowMeDebug]SyncAdapter( 4171): Sync task finished
,I/Gmail   ( 4183): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5334, normalSync: true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43ffe2b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(442d5070): PARTIAL_WAKE_LOCK  *sync*/com.htc.showme/com.htc.showme/***** 0x1 WorkSource{10082}
,D/Process (  907): killProcessQuiet, pid=3763
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=5 [40][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Killing 3763:com.google.android.apps.docs/u0a100 (adj 15): empty #17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Recipient 3763
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): env,ironment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(432a2368): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 907 1000 WorkSource{10096}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43ffe2b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4404cbc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4404cbc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/DelayedSyncController( 4153): Delaying sync.
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43468ed8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(432a2368): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv ,error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSUser ( 1391): GoogleAccountDataService.getToken()
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com mail
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42596f50): PARTIAL_WAKE_LOCK  *sync*/subscribedfeeds/com.google/***** 0x1 907 1000 WorkSource{10028}
D/PMS     (  907): releaseWL(43468ed8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43402960): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43402960): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1391): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1391): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken,(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1391): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1391): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1391): 	at dalvik.system.NativeStart.run(Native Method)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews( 1109): com.google.android.gms (false,0)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b74b30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews.Performance( 1109): com.google.android.gms 1 7 2 12
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!,
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/GLSUser ( 1391): GoogleAccountDataService.getToken()
D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com mail
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1391): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1391): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1391): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1391): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1391): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4401e980): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 28352, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 111931, reason: Periodic
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41bd1fc0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42596f50): PARTIAL_WAKE_LOCK  *sync*/subscribedfeeds/com.google/***** 0x1 WorkSource{10028}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/RemoteViews.Performance( 1109): com.google.android.gms 1 13 3 12
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSUser ( 1391): GoogleAccountDataService.getToken()
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): d,oString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/ExternalAccountType( 1307): Unsupported attribute readOnly
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com mail
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_,command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(44076ca8): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 907 1000 WorkSource{10108}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1391): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1391): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1391): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1391): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1391): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  907): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4254 uid=10108 gids={50108, 3003, 5012}
D/PMS     (  907): releaseWL(4401e980): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426b3758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews( 1109): com.google.android.gms (false,0)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c16738 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews.Performance( 1109): com.google.android.gms 1 6 2 12
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/Wi,fiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,W/AbstractGoogleClient( 4254): Application name is not set. Call Builder#setApplicationName.
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(426b3758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/SyncManager(  907): failed sync operation  u0 (com.google), gmail-ls, PERIODIC, latestRunTime 28344, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), gmail-ls, PERIODIC, latestRunTime 112064, reason: Periodic
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43202648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(4421b790): PARTIAL_WAKE_LOCK  *sync*/gmail-ls/com.google/***** 0x1 WorkSource{10107}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
,D/Process (  907): killProcessQuiet, pid=3783
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,I/ActivityManager(  907): Killing 3783:com.htc.backup/1000 (adj 15): empty #17
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_s,upplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/PMS     (  907): acquireWL(426ea910): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts/com.google/***** 0x1 907 1000 WorkSource{10028}
D/PMS     (  907): releaseWL(43202648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(431b1698): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(431b1698): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426e4b58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/,WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(426e4b58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42f9f708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4217): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4217): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4217): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4217): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4217): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4217): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0,
W/dalvikvm( 4217): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3783
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/Wif,iHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42f9f708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/calendar
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/CalendarSyncAdapter( 4254): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 4254): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 4254): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 4254): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 4254): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:836)
E/CalendarSyncAdapter( 4254): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:412)
E/CalendarSyncAdapter( 4254): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:345)
E/CalendarSyncAdapter( 4254): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:463)
E/CalendarSyncAdapter( 4254): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 4254): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 4254): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 4254): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 4254): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 4254): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 4254): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 4254): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 4254): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 4254): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 4254): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 4254): 	... 12 more
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c95570 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 7 2 12
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(440936f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 28367, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 112351, reason: Periodic
,D/Process (  907): killProcessQuiet, pid=3750
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(44076ca8): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 WorkSource{10108}
I/ActivityManager(  907): Killing 3750:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
I/ActivityManager(  907): Recipient 3750
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSUser ( 1391): GoogleAccountDataService.getToken()
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1307): Unsupported attribute readOnly
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958),: send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com cp
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(42f52440): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.people/com.google/***** 0x1 907 1000 WorkSource{10028}
D/PMS     (  907): releaseWL(440936f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(423bbca0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,W/GLSActivity( 1391): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1391): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1391): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1391): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1391): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/ContactsSyncAdapter( 1391): innerSync failed
D/ContactsSyncAdapter( 1391): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1391): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1391): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1391): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1391): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1391): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1391): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1391): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
D/ContactsSyncAdapter( 1391): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1391): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
D/ContactsSyncAdapter( 1391): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1391): 	at android.os.Binder.execTransact(Binder.java:412)
D/ContactsSyncAdapter( 1391): 	at dalvik.system.NativeStart.run(Native Method)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c987a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 9 3 12
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 28392, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 112459, reason: Periodic
D/PMS     (  907): releaseWL(423bbca0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(426034d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(426034d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43f95a50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(426ea910): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts/com.google/***** 0x1 WorkSource{10028}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/PeopleSync( 1199): onPerformSync() [5005f081]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(4243b888): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d7e2 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4278 uid=10106 gids={50106, 3003, 5012}
D/PMS     (  907): releaseWL(43f95a50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43683658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/,WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/PeopleDatabaseHelper( 1199): cleanUpNonGplusAccounts done.
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(43683658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4217): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplican,t( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4217): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/PeopleSync( 1199): Setting subscription: result=true [5005f081]
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/PeopleSync( 1199): Starting sync, feed=null [5005f081]
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/FbInjectorInitializer( 4217): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,I/NewsWeather( 4278): LocationClient connecting
,D/PMS     (  907): acquireWL(43497628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
,D/PMS     (  907): releaseWL(43497628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4278): NewsAccounts: 2, AllSystemAccounts 1.
E/dalvikvm( 4278): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4278): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4278): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4278): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4278): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,W/fb4a(:<default>):StaticBindingVerifier( 4217): Verify
,I/PeopleSync( 1199): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,I/ProviderInstaller( 4278): Installed default security provider GmsCore_OpenSSL
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(432d12e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/NewsWeather( 4278): Last usage 0, idle 1450100321s, sync interval 2592000s
,I/NewsWeather( 4278): setPeriodicSync in seconds 2592000
D/PMS     (  907): releaseWL(432d12e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PeopleSync( 1199): Sync finished, successful=false, took 67ms
,I/NewsWeather( 4278): onConnected null
,I/PeopleSync( 1199): Cannot authenticate [5005f081]
I/PeopleSync( 1199): arx: BadAuthentication
I/PeopleSync( 1199): 	at arj.a(SourceFile:411)
I/PeopleSync( 1199): 	at byt.b(SourceFile:91)
I/PeopleSync( 1199): 	at bxr.b(SourceFile:334)
I/PeopleSync( 1199): 	at byd.b(SourceFile:355)
I/PeopleSync( 1199): 	at byd.a(SourceFile:325)
I/PeopleSync( 1199): 	at byd.a(SourceFile:304)
I/PeopleSync( 1199): 	at iur.a(SourceFile:460)
I/PeopleSync( 1199): 	at hoi.e(SourceFile:905)
I/PeopleSync( 1199): 	at hoi.a(SourceFile:220)
I/PeopleSync( 1199): 	at hoa.a(SourceFile:251)
I/PeopleSync( 1199): 	at hoa.a(SourceFile:170)
I/PeopleSync( 1199): 	at hoa.onPerformSync(SourceFile:89)
I/PeopleSync( 1199): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,W/GCoreFlp( 1461): No location to return for getLastLocation()
,I/NewsWeather( 4278): LocationClient onConnected: location null
D/PMS     (  907): acquireWL(440756a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
D/PMS     (  907): acquireWL(424e5b98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
D/PMS     (  907): releaseWL(440756a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4278): ApiOperation url https://news.google.com/news/exec/fetchNewsEditions
D/PMS     (  907): releaseWL(424e5b98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/WifiService(  907): New client listening to asynchronous messages
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,I/PeopleSync( 1199): Sync finished, duration: 290 [5005f081]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4217/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.gms.people, PERIODIC, latestRunTime 28405, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.gms.people, PERIODIC, latestRunTime 112997, reason: Periodic
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(440c3af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42f52440): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.people/com.google/***** 0x1 WorkSource{10028}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/fb4a(:<default>):BaseAnalyticsConfig( 4217): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/fb4a(:<default>):BaseAnalyticsConfig( 4217): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(4403cfe0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.plus.action/com.google/***** 0x1 907 1000 WorkSource{10028}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(440c3af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44046110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews( 1109): com.google.android.gms (false,0)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/dalvikvm-heap( 4217): Grow heap (frag case) to 9.509MB for 73240-byte allocation
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c9c3a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and,_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/NewsWeather( 4278): Unrecoverable authentication exception
E/NewsWeather( 4278): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4278): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4278): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.c.hL(SourceFile:84)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:137)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4278): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
I/RemoteViews.Performance( 1109): com.google.android.gms 2 8 2 12
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Process (  907): killProcessQuiet, pid=3799
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Killing 3799:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Recipient 3799
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(44046110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4278): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4278): [NET] getaddrinfo-,err=8
D/libc    ( 4278): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4278): [NET] getaddrinfo-, 1
D/libc    ( 4278): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/libc    (  365): [NET] +++++ res_nsend xid =cacc +++++
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211,: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=70
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4278): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42605818): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): acquireWL(43815e78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(42605818): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(43687200): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(43815e78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/fb4a(:<default>):UserScope( 4217): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  907): acquireWL(440981c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4403cfe0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.plus.action/com.google/***** 0x1 WorkSource{10028}
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4217): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/fb4a(:<default>):UserScope( 4217): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(425a2710): PARTIAL_WAKE_LOCK  *sync*/com.google.android.videos.sync/com.google/***** 0x1 907 1000 WorkSource{10165}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4312 uid=10165 gids={50165, 3003, 5012, 1028, 1015, 3002}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/GCM     ( 1391): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(440981c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
,D/PMS     (  907): releaseWL(43687200): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/libc    ( 4278): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4278): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/libc    ( 1391): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1391): [NET] getaddrinfo-,err=8
D/libc    ( 1391): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1391): [NET] getaddrinfo-, 1
,D/libc    ( 1391): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2d8f +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/PMS     (  907): acquireWL(425e1d28): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1391 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/AutoSetting( 1364): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 211
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1391): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4329 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1364/10053)
D/AutoSetting( 1364): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1364): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1364): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1364): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1364/10053)
,E/dalvikvm( 4217): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4217): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4217): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4217): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4217): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4217): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4217): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4217): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4217): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4217): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4217): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4217): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4217): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4217): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4217): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4217): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4217): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4217): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/MobileConnectivityChangeReceiver( 4329): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4329): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4329): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4329): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4329/10078)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4329/10078)
,I/dalvikvm-heap( 4217): Grow heap (frag case) to 9.916MB for 39954-byte allocation
D/PMS     (  907): acquireWL(43c02598): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.NetworkChangeReceiver: pid=4345 uid=10098 gids={50098, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3556
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3556:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4329/10078)
,I/ActivityManager(  907): Recipient 3556
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(44394a38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(43c02598): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/dalvikvm-heap( 4217): Grow heap (frag case) to 9.993MB for 79892-byte allocation
I/CheckinService( 1199): Preparing to send checkin request
,I/EventLogService( 1199): Accumulating logs since 1450098516968
,I/DeviceManagement( 4345): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4345 dbg=false s=true
,I/DeviceManagement( 4345): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
,I/DeviceManagement( 4345): WorkflowService: Starting workflow service
,I/DeviceManagement( 4345): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41b84a78] args=[Bundle[mParcelledData.dataSize=804]]
,D/libc    ( 1391): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1391): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4217): Grow heap (frag case) to 10.026MB for 84664-byte allocation
W/ActivityThread( 1391): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4363 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=10 [10][1][0]
W/EventLogAggregator( 1199): Unknown tag: install_package_attempt
W/EventLogAggregator( 1199): Unknown tag: snet
,W/EventLogAggregator( 1199): Unknown tag: snet_gcore
D/ContactMessageStore( 1220): notify MmsSms
D/AccFlag ( 1220): sense_version=6.0
,D/AccFlag ( 1220): sku_id=99
,I/DeviceManagement( 4345): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 4345): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
,I/DeviceManagement( 4345): NetworkChangeWorkflow: ==================================================
,I/DeviceManagement( 4345): ModelRegistry: Loading model meta data from resources...
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.videos (4312/10165)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
D/PMS     (  907): acquireWL(44058e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/PMS     (  907): releaseWL(44058e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/DeviceManagement( 4345): SessionStateController: Checking invariants...
,I/GoogleHttpClient( 1199): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1199): Using GMS GoogleHttpClient
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4363): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/GCM     ( 1391): Connected
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  907): acquireWL(43fda7d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1391 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/PMS     (  907): releaseWL(425e1d28): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1391/10028)
,W/ContextImpl( 4363): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/PMS     (  907): releaseWL(43fda7d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PlayMovies( 4312): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GAV2    ( 4363): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [4][0][0]
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4217): Grow heap (frag case) to 10.275MB for 75760-byte allocation
D/PMS     (  907): acquireWL(44001340): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
D/PMS     (  907): acquireWL(42c2c220): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1391 10028 null
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/PMS     (  907): releaseWL(44001340): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/ContextImpl( 4363): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4363): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4217/10026)
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,I/NewsWeather( 4278): NewsEditionsResponse.current_edition: wt: 0
I/NewsWeather( 4278): ww: 0
I/NewsWeather( 4278): wx: "GB"
I/NewsWeather( 4278): wy: "en"
I/NewsWeather( 4278): wz: "U.K."
I/NewsWeather( 4278): id: "uk"
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b15288 u0 ReceiverList{42f04d50 4217 com.facebook.katana/10026/u0 remote:42f049b0}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42bbd7e0 u0 ReceiverList{42bbd780 4217 com.facebook.katana/10026/u0 remote:426b88d8}}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1391/10028)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1391): Message class mpf
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1391/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4217/10026)
,D/PMS     (  907): acquireWL(43b4b9e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,I/DeviceManagement( 4345): BackgroundController: Invariants are unchanged.
D/PMS     (  907): releaseWL(42c2c220): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): releaseWL(43b4b9e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4217/10026)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/DeviceManagement( 4345): SessionStateController: Checking invariants...
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4217/10026)
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.videos (pid 4312): Registered
,I/NewsWeather( 4278): syncNewsAppData traffic type BACKGROUND_POLL
,I/MediaRouter( 4312): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/PlayMovies( 4312): MediaRouteManager.maybeRestoreRoute:188 sessionRestore routeId: 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.videos (4312/10165)
,D/PlayMovies( 4312): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/GCoreFlp( 1461): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(4346cff8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
,D/PMS     (  907): releaseWL(4346cff8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4363/10151)
,I/NewsWeather( 4278): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(443094e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PlayMovies( 4312): TransferService.onCreate:52 creating transfer service
,V/WebViewChromiumFactoryProvider( 4363): Binding Chromium to main looper Looper (main, tid 1) {41b49de8}
,I/LibraryLoader( 4363): Expected native library version number "",actual native library version number ""
,I/chromium( 4363): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4363): Initializing chromium process, renderers=0
D/PMS     (  907): releaseWL(443094e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.videos (4312/10165)
,I/DeviceManagement( 4345): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
D/PMS     (  907): acquireWL(440429f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): acquireWL(4403ebf8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/AudioManagerAndroid( 4363): BLUETOOTH permission is missing!
,W/ContextImpl( 4217): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.videos (4312/10165)
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/PMS     (  907): releaseWL(4403ebf8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=1, flag=1, pid=4312, uid=10165, userID:0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4217): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/MediaRouter( 4312): getSelectedRoute
I/Adreno-EGL( 4363): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4363): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4363): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4363): Local Branch: 
I/Adreno-EGL( 4363): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4363): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4363):                  aa63bbd948f41d15fc72f585e
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/PlayMovies( 4312): MediaRouteManager.onRouteAdded:140 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
D/PlayMovies( 4312): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4217): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.videos (4312/10165)
W/ContextImpl( 4312): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.videos/files/Movies
,D/PMS     (  907): acquireWL(43bfc0c8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.videos (4312/10165)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.videos (4312/10165)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=2, flag=1, pid=4312, uid=10165, userID:0
I/DeviceManagement( 4345): Perf: *** Cache update - start...
I/DeviceManagement( 4345): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4345): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4345): Perf: *** Enabled app cache update - complete: 1 ms
I/DeviceManagement( 4345): Perf: *** Config cache update - start...
I/DeviceManagement( 4345): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4345): ConfigCacheController: *** Updating stale config cache entries...
I/NSApplication( 4363): Starting up...
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4363/10151)
W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4363/10151)
D/PMS     (  907): releaseWL(43bfc0c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/dalvikvm( 4345): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
,W/dalvikvm( 4345): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 4345): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4427 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3521
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  907): Killing 3521:com.android.vending/u0a73 (adj 15): empty #17
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
D/PMS     (  907): acquireWL(423d03c0): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/NewsWeather( 4278): Unrecoverable authentication exception
E/NewsWeather( 4278): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4278): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4278): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4278): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4278): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1199): awaiting user notification for token
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ca1a18 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3521
I/RemoteViews.Performance( 1109): com.google.android.gms 2 10 2 12
,W/System.err( 4345): Starting the internal HTTP client
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c9b2a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/DeviceManagement( 4345): ConfigCacheController: Getting config update from server: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.aurora/versions/ddcde851-94d3-4ce2-896c-ddafd2987e4a/cid/MDozOjIwMTUtMDgtMjFUMDk6MTU6MTcuMTg4Wg
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 6 3 12
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/PMS     (  907): releaseWL(423d03c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/PlayMovies( 4312): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:70 Cannot get user auth
E/PlayMovies( 4312): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4312): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 4312): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 4312): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 4312): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 4312): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 4312): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 4312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c14ca8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayMovies( 4312): AccountManagerWrapper.blockingAuthenticate:165 Authentication failed
E/PlayMovies( 4312): com.google.android.videos.accounts.AccountManagerWrapper$AuthTokenException: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4312): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:71)
E/PlayMovies( 4312): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 4312): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 4312): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 4312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/PlayMovies( 4312): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4312): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 4312): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 4312): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 4312): 	... 4 more
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 7 2 12
D/PMS     (  907): acquireWL(424588e8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/Process (  907): killProcessQuiet, pid=3885
D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 28467, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4252f430): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(425a2710): PARTIAL_WAKE_LOCK  *sync*/com.google.android.videos.sync/com.google/***** 0x1 WorkSource{10165}
,I/ActivityManager(  907): Killing 3885:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 113920, reason: Periodic
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
,D/PMS     (  907): releaseWL(424588e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Recipient 3885
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4446 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42bb8068): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/DeviceManagement( 4345): DeviceClientResource: Active network...
I/DeviceManagement( 4345):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/ExternalAccountType( 1307): Unsupported attribute readOnly
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4427/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4427/10160)
D/BuildInfo( 4345): Created new instance: com.htc.cs.lib.hms.BuildInfo@41dee888
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
I/DeviceManagement( 4345): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42bb8068): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4427/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4427/10160)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4446): install
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4446): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4250e858): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4427 10160 null
,D/PMS     (  907): acquireWL(4250e080): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/MultiDex( 4446): loading existing secondary dex files
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4446): load found 1 secondary dex files
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/MultiDex( 4446): install done
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4345): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4345): [NET] getaddrinfo-, 1
,D/libc    ( 4345): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  365): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4345): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43383d50): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 907 1000 WorkSource{10097}
D/PMS     (  907): releaseWL(4250e080): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1756/10178)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(42124720): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4427 10160 null
,D/PMS     (  907): releaseWL(4250e858): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/NewsWeather( 4278): Failed to syncNewsAppData
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,E/NewsWeather( 4278): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): acquireWL(44047db8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,D/PMS     (  907): releaseWL(44047db8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  907): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4470 uid=10097 gids={50097, 3003, 5012, 1028}
,D/PMS     (  907): releaseWL(4252f430): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(438b3ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4345): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4345): [NET] getaddrinfo-,err=8
D/libc    ( 4345): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4345): [NET] getaddrinfo-, 1
D/libc    ( 4345): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =96f4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=4484 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(44028808): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Process (  907): killProcessQuiet, pid=3413
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/PMS     (  907): releaseWL(44028808): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Killing 3413:com.htc.musicenhancer/u0a51 (adj 15): empty #17
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ProviderInstaller( 4446): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42124720): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/PMS     (  907): releaseWL(438b3ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): killProcessQuiet, pid=3986
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 28442, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4262bc78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/ActivityManager(  907): Killing 3986:com.htc.widget.process2/u0a48 (adj 15): empty #17
,D/PMS     (  907): releaseWL(4243b888): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
V/com.google.android.apps.common.multidex.Tracer( 4470): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4470): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4470): Package last updated: Mar 27, 2015 8:20:30.0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/CalendarApplication( 4484): onCreate
V/com.google.android.apps.common.multidex.Tracer( 4470): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4470): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4470): Package last updated: Mar 27, 2015 8:20:30.0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/AlertReceiver( 4484): beginStartingService
V/com.google.android.apps.common.multidex.Tracer( 4470): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41b629f8, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41b63768, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41b63ac0]
,V/com.google.android.apps.common.multidex.Tracer( 4470): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41b629f8.
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  907): killProcessQuiet, pid=3926
I/ActivityManager(  907): Recipient 3986
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Killing 3926:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
,D/PMS     (  907): acquireWL(44059ea0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4484 10013 null
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/com.google.android.apps.common.multidex.Tracer( 4470): Patching was successful.
,I/ActivityManager(  907): Recipient 3926
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3413
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=204
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4345): [NET] getaddrinfo_proxy-, success
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(440b8b98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/AlertService( 4484): start to updateAlertNotification!
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(440b8b98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(423f93e8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 907 1000 WorkSource{10160}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4262bc78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43c17d78): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1199 10028 null
,D/PMS     (  907): acquireWL(44055190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/GoogleHttpClient( 4446): Falling back to old SSLCertificateSocketFactory
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/AlertService( 4484): No fired or scheduled alerts
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/HtcAlertUtils( 4484): -- cancelReminderNotification --
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/HtcAlertUtils( 4484): broadcastExistReminder!
D/PMS     (  907): acquireWL(426ea0d0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1199 10028 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/EventLogService( 1199): Aggregate from 1450100321773 (log), 1450098516968 (data)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/AlertReceiver( 4484): stopSelfResult true
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/PMS     (  907): releaseWL(43c17d78): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PMS     (  907): releaseWL(44059ea0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4504 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/libc    ( 4446): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4446): [NET] getaddrinfo-,err=8
D/libc    ( 4446): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4446): [NET] getaddrinfo-, 1
D/libc    ( 4446): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6672 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,W/WeatherRequest( 1109): request cur loc, but there is no sys cur
D/PMS     (  907): releaseWL(44055190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42fd8f40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(42fd8f40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(432a1f40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(432a1f40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  907): Start proc com.google.android.apps.cloudprint for content provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider: pid=4520 uid=10097 gids={50097, 3003, 5012, 1028}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11
D/libc    (  365): [NET]res_nsend:resplen=86
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4446): [NET] getaddrinfo_proxy-, success
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4535 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4504): can't get weather sync account
D/PMS     (  907): releaseWL(426ea0d0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,V/com.google.android.apps.common.multidex.Tracer( 4520): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4520): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4520): Package last updated: Mar 27, 2015 8:20:30.0
,V/com.google.android.apps.common.multidex.Tracer( 4520): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4520): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4520): Package last updated: Mar 27, 2015 8:20:30.0
V/com.google.android.apps.common.multidex.Tracer( 4520): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41b68dc0, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41b69b30, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41b69e88]
,V/com.google.android.apps.common.multidex.Tracer( 4520): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41b68dc0.
,V/com.google.android.apps.common.multidex.Tracer( 4520): Patching was successful.
,W/WeatherRequest( 4504): request cur loc, but there is no sys cur
,W/Settings( 4504): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/dalvikvm-heap( 4427): Grow heap (frag case) to 15.228MB for 1821008-byte allocation
,D/PMS     (  907): acquireWL(44225798): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4535 10070 null
,D/PMS     (  907): acquireWL(43417670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4535 10070 null
,D/PMS     (  907): releaseWL(44225798): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4550 uid=10090 gids={50090, 3003, 5012, 1028}
,D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
D/TodoTaskshortcut( 4535): update TASK shortcut>
,I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 2 13 17
,I/TodoTaskNotifyService( 4535): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/libc    ( 4446): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4446): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4266fcf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/WorldClock.Global( 4550): isHtcDevice = true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/PMS     (  907): releaseWL(423f93e8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): killProcessQuiet, pid=3944
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=6 [15][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Killing 3944:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/WorldClock.Global( 4550): isHtcDevice = true
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
I/ActivityManager(  907): Recipient 3944
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4403cee0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.magazines/com.google/***** 0x1 907 1000 WorkSource{10151}
D/PMS     (  907): acquireWL(424e81e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
I/ActivityManager(  907): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4565 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  907): releaseWL(424e81e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [7][0][0]
D/PMS     (  907): releaseWL(4266fcf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4407e690): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,D/PMS     (  907): releaseWL(4407e690): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/WorldClock.AlarmUtils( 4550): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/SyncAdapterService( 4363): Ignoring sync request for non-current account
,I/WorldClock.AlarmUtils( 4550): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4550): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/IntentController( 1109): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/TodoTaskNotifyService( 4535): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/PMS     (  907): acquireWL(442d8338): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4363/10151)
,D/PMS     (  907): releaseWL(4403cee0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.magazines/com.google/***** 0x1 WorkSource{10151}
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(43417670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 4535): stopSelfResult true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/TimeService( 4565): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450100322856
,D/Process (  907): killProcessQuiet, pid=3325
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): killProcessQuiet, pid=4110
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/ActivityManager(  907): Killing 3325:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  907): Killing 4110:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Recipient 4110
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
D/ProviderChangeReceiver( 4484): ---------------------------------------------------
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ProviderChangeReceiver( 4484): ProviderChangeReceiver onReceive, start to update notification!
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/AlertService( 4484): start to updateAlertNotification!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): killProcessQuiet, pid=4131
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/ActivityManager(  907): Delay finish: com.htc.calendar/.ProviderChangeReceiver
,I/ActivityManager(  907): Killing 4131:com.google.android.music:main/u0a154 (adj 15): empty #17
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(437231c0): PARTIAL_WAKE_LOCK  *sync*/com.htc.cloudstorage.drive.db/com.google/***** 0x1 907 1000 WorkSource{10068}
I/ActivityManager(  907): Recipient 4131
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 4345): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4345): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4345): DeviceClientResourceController: handleDirectives: []
W/dalvikvm( 4345): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 4345): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 4345): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4345): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 4345): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 4345): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4345): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4345): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4345): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4345): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 4345): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4345): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
,W/dalvikvm( 4345): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4345): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 4345): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 4345): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 4345): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
D/MediaRouterService(  907): Client com.google.android.music (pid 4131): Died!
I/ActivityManager(  907): Start proc com.htc.cloudstorage.drive for service com.htc.cloudstorage.drive/.SyncService: pid=4591 uid=10068 gids={50068, 3003, 5012, 1028, 1015}
,D/PMS     (  907): releaseWL(442d8338): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/System.out( 4345): isCompatible false
I/System.out( 4345): createObjectMapper
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/AlertService( 4484): No fired or scheduled alerts
,D/HtcAlertUtils( 4484): -- cancelReminderNotification --
,D/HtcAlertUtils( 4484): broadcastExistReminder!
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ec24e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4470): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4470): [NET] getaddrinfo-,err=8
D/libc    ( 4470): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    ( 4470): [NET] getaddrinfo-, 1
D/libc    ( 4470): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7e60 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 11 3 12
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 280
D/libc    (  365): [NET]res_nsend:resplen=48
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4470): [NET] getaddrinfo_proxy-, success
,D/CloudStorageManager( 4591): [getInstance] googledrive version: 6
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/ActivityManager(  907): Recipient 3325
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): acquireWL(42efa150): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42efa150): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/DeviceManagement( 4345): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEwLTE0VDEwOjI4OjM4LjU4Mlo
,I/DeviceManagement( 4345): DeviceClientResource: Active network...
I/DeviceManagement( 4345):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [8][0][0]
,W/MyGoogleDrive( 4591): [4605][GoogleDriveThreadedSyncAdapter] [onPerformSync]*Sync ABORT* Account not found(never cached)
D/libc    ( 4345): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4345): [NET] getaddrinfo-, 1
,D/libc    ( 4345): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  365): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4215b960): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/libc    ( 4345): [NET] getaddrinfo_proxy-, success
D/libc    ( 4345): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4345): [NET] getaddrinfo-,err=8
D/libc    ( 4345): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4345): [NET] getaddrinfo-, 1
D/libc    ( 4345): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =8f99 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4345): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): killProcessQuiet, pid=4217
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(437231c0): PARTIAL_WAKE_LOCK  *sync*/com.htc.cloudstorage.drive.db/com.google/***** 0x1 WorkSource{10068}
,I/ActivityManager(  907): Killing 4217:com.facebook.katana/u0a26 (adj 15): empty #17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(41fd38c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.games.background/com.google/***** 0x1 907 1000 WorkSource{10028}
D/PMS     (  907): releaseWL(4215b960): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42467100): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(42467100): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GamesSyncAdapter( 1199): User is not G+ enabled. Aborting sync
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43bd2820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(41fd38c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.games.background/com.google/***** 0x1 WorkSource{10028}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42c93160): PARTIAL_WAKE_LOCK  *sync*/com.google.android.music.MusicContent/com.google/***** 0x1 907 1000 WorkSource{10154}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Recipient 4217
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=4609 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/PMS     (  907): releaseWL(43bd2820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,I/MusicStore( 4609): Database version: 95
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41eeed38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 8 4 12
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/libc    ( 4470): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4470): [NET] getaddrinfo-,err=8
D/libc    ( 4470): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4470): [NET] getaddrinfo-, 1
,D/libc    ( 4470): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1190 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4470): [NET] getaddrinfo_proxy-, success
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ef5998 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 8 10 12
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4609, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4609): Registered
,I/MediaRouter( 4609): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43be04e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/NetworkMonitor( 4609): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4609/10154)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=25 [8][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(43be04e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 4609): getSelectedRoute
,I/NetworkMonitor( 4609): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4609/10154)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4609, uid=10154, userID:0
,I/DeviceManagement( 4345): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4345): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4345): DeviceClientResourceController: handleDirectives: []
I/System.out( 4345): isCompatible false
I/System.out( 4345): createObjectMapper
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
,I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
,I/System.out( 4345): isCompatible false
,I/ConfigStore( 4609): Config Database version: 1
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b77960 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 2 6 2 12
,I/DeviceManagement( 4345): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 4345): DeviceClientResource: Active network...
I/DeviceManagement( 4345):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [3][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
,D/libc    ( 4345): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4345): [NET] getaddrinfo-, 1
,D/libc    ( 4345): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  365): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4345): [NET] getaddrinfo_proxy-, success
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
D/libc    ( 4345): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4345): [NET] getaddrinfo-,err=8
D/libc    ( 4345): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4345): [NET] getaddrinfo-, 1
D/libc    ( 4345): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6c28 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4345): [NET] getaddrinfo_proxy-, success
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com sj
,I/Adreno-EGL( 4446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4446): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4446): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4446): Local Branch: 
I/Adreno-EGL( 4446): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4446): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4446):                  aa63bbd948f41d15fc72f585e
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1391): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1391): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1391): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1391): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41bd1c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/MusicSyncAdapter( 4609): Sync failed due to an authentication issue.
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 8 3 12
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 28540, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(426d39d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42c93160): PARTIAL_WAKE_LOCK  *sync*/com.google.android.music.MusicContent/com.google/***** 0x1 WorkSource{10154}
D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 115280, reason: Periodic
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=4171
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
,I/ActivityManager(  907): Killing 4171:com.htc.showme/u0a82 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4405a890): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 907 1000 WorkSource{10100}
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4171
I/ActivityManager(  907): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4640 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  907): releaseWL(426d39d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(426c0798): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(426c0798): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c79908 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 3 9 4 12
I/ActivityManager(  907): Resuming delayed broadcast
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4254
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Killing 4254:com.google.android.syncadapters.calendar/u0a108 (adj 15): empty #17
D/GCM     ( 1391): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
I/ActivityManager(  907): Recipient 4254
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4654 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4446/10028)
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Adreno-EGL( 4446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4446): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4446): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4446): Local Branch: 
I/Adreno-EGL( 4446): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4446): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4446):                  aa63bbd948f41d15fc72f585e
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ca0f10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/libc    ( 4470): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4470): [NET] getaddrinfo-,err=8
D/libc    ( 4470): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4470): [NET] getaddrinfo-, 1
D/libc    ( 4470): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d993 +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 6 3 12
,D/libc    ( 4470): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4446): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4446): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4446): Local Branch: 
I/Adreno-EGL( 4446): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4446): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4446):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4446): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Babel   ( 4654): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4654): MmsConfig.loadMmsSettings
,E/dalvikvm( 4654): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4654): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4654): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4654): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4654): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4678 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4654, uid=10111, userID:0
,W/Settings( 4654): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4678): onCreate
,V/GetPrviateResource( 4678): GetPrviateResource
V/GetPrviateResource( 4678): GetPrviateResource
,D/MmsCustomizationProvider( 4678): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4654, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4654, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4654, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4654, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4654, uid=10111, userID:0
,I/DeviceManagement( 4345): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4345): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4345): DeviceClientResourceController: handleDirectives: []
I/System.out( 4345): isCompatible false
I/System.out( 4345): createObjectMapper
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
,I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
,D/MmsCustomizationProvider( 4678): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4654): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4654): MmsConfig.loadFromDatabase
,I/ProviderInstaller( 4654): Installed default security provider GmsCore_OpenSSL
E/Babel   ( 4654): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4654): MmsConfig.loadFromResources
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
E/Babel   ( 4654): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4654): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Process (  907): killProcessQuiet, pid=4329
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  907): Killing 4329:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4329
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4654/10111)
,D/MessageCustFlag( 4678): sense_version=6.0
,D/BTAccessoryUtil( 4678): createReceiver
,D/BTAccessoryUtil( 4678): registerReceiver return intent = null
D/MessageCustFlag( 4678): sku_id=99
,W/SystemReader( 4678): Cannot find message_ambs_application_id, use default value instead
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,D/Messaging( 4678): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4678): networkCode: 
D/MessageCustFlag( 4678): sku_id=99
D/MmsConfig( 4678): SIE smsPri: null
,D/MmsConfig( 4678): networkCode: 
D/HtcTelephonyCapability( 4678): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4678): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4678): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4678): Cannot find qct_8960_interface, use default value instead
,I/DeviceManagement( 4345): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,W/GAV2    ( 4640): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(439a80a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4640/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4640/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4654/10111)
,I/DeviceManagement( 4345): DeviceClientResource: Active network...
I/DeviceManagement( 4345):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=8 [12][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
D/PMS     (  907): releaseWL(439a80a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4345/10098)
,D/libc    ( 4345): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4345): [NET] getaddrinfo-, 1
,D/libc    ( 4345): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  365): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4345): [NET] getaddrinfo_proxy-, success
D/libc    ( 4345): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4345): [NET] getaddrinfo-,err=8
D/libc    ( 4345): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4345): [NET] getaddrinfo-, 1
,D/libc    ( 4345): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6347 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4345): [NET] getaddrinfo_proxy-, success
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
D/PMS     (  907): acquireWL(43ff4948): PARTIAL_WAKE_LOCK  SyncManager 0x1 4640 10100 null
,D/WifiService(  907): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@44029c18}
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  907): acquireWL(42bc5708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10014}
V/AlarmManager(  907): sending alarm PendingIntent{4305fba0: PendingIntentRecord{42f23cb8 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=115742, Int=0
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ea02c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 0 6 2 12
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/PMS     (  907): releaseWL(43ffbce8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/GAV2    ( 4183): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425550f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
W/GLSUser ( 1391): GoogleAccountDataService.getToken()
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(425550f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4654): UserRecoverableAuthException.
,E/Babel   ( 4654): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4654): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4654): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4654): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4654): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4654): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4654): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4654): Error getting auth token
,E/Babel   ( 4654): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4654): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4654): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4654): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4654): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4654): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4654): Account registration failedRedacted-21
E/Babel   ( 4654): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4654): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4654): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4654): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4654): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4654): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4654): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4654): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4654/10111)
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,I/DeviceManagement( 4345): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4345): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4345): DeviceClientResourceController: handleDirectives: []
I/System.out( 4345): isCompatible false
I/System.out( 4345): createObjectMapper
I/System.out( 4345): isCompatible false
,I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
I/System.out( 4345): isCompatible false
,I/System.out( 4345): isCompatible false
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,D/libc    ( 4640): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 4
D/libc    ( 4640): [NET] getaddrinfo-,err=8
D/libc    ( 4640): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    ( 4640): [NET] getaddrinfo-, 1
,D/libc    ( 4640): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e406 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,I/CheckinTask( 1199): Sending checkin request (9041 bytes)
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ActivityThread( 1199): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 47
D/libc    (  365): [NET]res_nsend:resplen=49
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4640): [NET] getaddrinfo_proxy-, success
I/global  ( 4640): call createSocket() return a new socket.
D/libc    ( 4640): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4640): [NET] getaddrinfo-, SUCCESS
I/RemoteViews( 1109): com.google.android.gms (false,0)
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41efc210 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 2 7 2 12
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1199): [NET] getaddrinfo-,err=8
D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1199): [NET] getaddrinfo-, 1
D/libc    ( 1199): [NET] getaddrinfo_proxy+
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4204 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/Babel   ( 4654): Unexpected exception while authenticating.
,E/Babel   ( 4654): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4654): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4654): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4654): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4654): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4654): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4654): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4654): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4654): 	at java.lang.Thread.run(Thread.java:864)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41f11aa0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/DeviceManagement( 4345): ConfigCacheController: *** Update config cache: updating 4 entries...
,I/DeviceManagement( 4345): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, statusCode=0, authCode=0>
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 5 3 12
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 251
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1199): [NET] getaddrinfo_proxy-, success
,I/RemoteViews( 1109): com.google.android.gms (false,0)
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4470): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/libc    ( 4470): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4470): [NET] getaddrinfo-,err=8
D/libc    ( 4470): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4470): [NET] getaddrinfo-, 1
,D/libc    ( 4470): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =aba8 +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4470): [NET] getaddrinfo_proxy-, success
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41f3b010 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 8 2 12
,I/DeviceManagement( 4345): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 4345): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1199): [NET] getaddrinfo-,err=8
,I/DeviceManagement( 4345): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 4345): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4345): AlarmController: Scheduling TTL alarm for: 2015.12.15 at 14:38:44.608 CET (due to: com.htc.launcher)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4345, uid=10098, userID:0
,I/DeviceManagement( 4345): Perf: *** Config cache update - complete: 2681 ms
,I/DeviceManagement( 4345): Perf: *** Cache update - complete: 2684 ms
,I/DeviceManagement( 4345): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41b84a78]
,I/DeviceManagement( 4345): WorkflowService: Stopping workflow service
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42064a60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): releaseWL(43383d50): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 WorkSource{10097}
I/NewsWeather( 4278): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): killProcessQuiet, pid=4345
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Process (  907): killProcessQuiet, pid=4153
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=9 [44][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
I/ActivityManager(  907): Killing 4345:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Killing 4153:com.android.chrome/u0a96 (adj 15): empty #18
I/NewsWeather( 4278): onReceive com.google.android.apps.genie.intent.action.PROVIDER_CHANGED
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
D/Process (  907): killProcessQuiet, pid=4312
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Killing 4312:com.google.android.videos/u0a165 (adj 15): empty #17
,D/GCM     ( 1391): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Recipient 4153
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(42066938): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 907 1000 WorkSource{10067}
,I/ActivityManager(  907): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4727 uid=10067 gids={50067, 3003, 5012}
,D/PMS     (  907): releaseWL(42064a60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(424d33d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4535 10070 null
,D/PMS     (  907): acquireWL(4242a7a0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4535 10070 null
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4742 uid=10038 gids={50038}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(41f24010): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(41f24010): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): releaseWL(424d33d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4535): java.lang.NullPointerException
W/System.err( 4535): java.lang.NullPointerException
W/System.err( 4535): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4535): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4535): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4535): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4535): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4535): stopSelfResult true
D/PMS     (  907): releaseWL(4242a7a0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  907): Recipient 4312
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.videos (pid 4312): Died!
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4345
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4759 uid=10077 gids={50077}
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,D/SMSBackup( 4759): Got a database change event
W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com writely
,D/Process (  907): killProcessQuiet, pid=4504
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  907): Killing 4504:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/PMS     (  907): acquireWL(43ffcb08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4535 10070 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4258d8b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): acquireWL(426abae0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4535 10070 null
I/ActivityManager(  907): Recipient 4504
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): releaseWL(42066938): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 WorkSource{10067}
E/TodoTaskNotifyService( 4535): java.lang.NullPointerException
W/System.err( 4535): java.lang.NullPointerException
W/System.err( 4535): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4535): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4535): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4535): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4535): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(43ffcb08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  907): releaseWL(426abae0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=16 [12][2][0]
,W/NotifyReceiver( 4535): stopSelfResult true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Delay finish: com.google.android.music/.download.MusicCommunicator
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  907): acquireWL(4250e748): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 907 1000 WorkSource{10028}
,D/PMS     (  907): releaseWL(4258d8b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/GLSActivity( 1391): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1391): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1391): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1391): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1391): 	at dalvik.system.NativeStart.run(Native Method)
I/RemoteViews( 1109): com.google.android.gms (false,0)
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/HttpIssuerBase( 4640): Attempt to consume entity of HttpIssuer when no request is executing.
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41e02938 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/HttpIssuerBase( 4640): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 4640): java.io.IOException
E/HttpIssuerBase( 4640): 	at Er.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 4640): 	at DV.b(DefaultAuthenticatedHttpIssuer.java:148)
E/HttpIssuerBase( 4640): 	at Pq.a(AccountMetadataUpdater.java:226)
E/HttpIssuerBase( 4640): 	at Pq.a(AccountMetadataUpdater.java:139)
E/HttpIssuerBase( 4640): 	at Qv.a(LegacySyncManager.java:776)
E/HttpIssuerBase( 4640): 	at Qv.a(LegacySyncManager.java:541)
E/HttpIssuerBase( 4640): 	at Qv.a(LegacySyncManager.java:95)
E/HttpIssuerBase( 4640): 	at Qx.run(LegacySyncManager.java:396)
E/HttpIssuerBase( 4640): 	at Vz.a(NetworkUtilitiesImpl.java:30)
E/HttpIssuerBase( 4640): 	at Qw.run(LegacySyncManager.java:393)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 9 4 12
,D/PMS     (  907): acquireWL(424ba870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(440429f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/SyncManager( 4640): AuthenticatorException
E/SyncManager( 4640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 4640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/SyncManager( 4640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 4640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/SyncManager( 4640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 4640): 	at android.os.Binder.execTransact(Binder.java:412)
E/SyncManager( 4640): 	at dalvik.system.NativeStart.run(Native Method)
,W/GAV2    ( 4640): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  907): releaseWL(424ba870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiService(  907): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@44029c18}
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/PMS     (  907): releaseWL(43ff4948): PARTIAL_WAKE_LOCK  SyncManager 0x1 null
W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/Process (  907): killProcessQuiet, pid=4427
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4427:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4401d308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): acquireWL(4340cc10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
D/PMS     (  907): releaseWL(4405a890): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
,D/Process (  907): killProcessQuiet, pid=4550
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/CheckinResponseProcessor( 1199): From server: 1 gservices updates and 0 deletes
D/PMS     (  907): releaseWL(4340cc10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/ActivityManager(  907): Killing 4550:com.htc.android.worldclock/u0a90 (adj 15): empty #17
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/PMS     (  907): releaseWL(4401d308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  907): Recipient 4550
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ArtDownloadService( 4609): Setting cache size 0
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ArtDownloadService( 4609): Setting cache size 0
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4427
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/userlocation.reporting
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/CertBlacklister(  907): Certificate blacklist changed, updating...
,I/CertBlacklister(  907): Certificate blacklist updated
,I/GservicesProvider( 1391): main difference update completed
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [2][0][0]
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GCoreUlr( 1461): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService }, extras=null
,D/PMS     (  907): acquireWL(43453488): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1461 10028 null
E/GCoreUlr( 1461): 
E/GCoreUlr( 1461): arx: BadAuthentication
E/GCoreUlr( 1461): 	at arj.a(SourceFile:411)
E/GCoreUlr( 1461): 	at byt.b(SourceFile:91)
E/GCoreUlr( 1461): 	at bxr.b(SourceFile:334)
E/GCoreUlr( 1461): 	at byd.b(SourceFile:355)
E/GCoreUlr( 1461): 	at byd.a(SourceFile:325)
E/GCoreUlr( 1461): 	at byd.a(SourceFile:304)
E/GCoreUlr( 1461): 	at lwj.a(SourceFile:128)
E/GCoreUlr( 1461): 	at lye.b(SourceFile:190)
E/GCoreUlr( 1461): 	at lye.a(SourceFile:137)
E/GCoreUlr( 1461): 	at lyi.onPerformSync(SourceFile:156)
E/GCoreUlr( 1461): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1109): com.google.android.gms (false,0)
W/CheckinRequestBuilder( 1199): awaiting user notification for token
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41f1f7c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 2 8 4 12
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43b6af28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 28618, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 117102, reason: Periodic
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(4250e748): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 WorkSource{10028}
D/PMS     (  907): releaseWL(43b6af28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43bf6ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(43bf6ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,I/CheckinTask( 1199): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1199): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/GCoreUlr( 1461): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1461): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(4367f390): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
,I/GCoreUlr( 1461): Unbound from all location providers
D/PMS     (  907): releaseWL(4367f390): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  907): releaseWL(43453488): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  907): releaseWL(44394a38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1199): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d59590 that was originally bound here
E/ActivityThread( 1199): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d59590 that was originally bound here
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
,D/Messaging( 4678): mNeedToUpdateDate2 start
,D/MmsConfig( 4678): packageName: com.htc.vvm.att does not exist
,I/GAV4    ( 4278): Thread[GAThread,5,main]: No campaign data found.
D/ReportIndicatorCache( 4678): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4678): 
D/MmsAsyncWorkHandler( 4678): HM tk = 20001
,D/ReportIndicatorCache( 4678): MSG_QUERY_REPORTS >>
D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/SettingsManager( 4678): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b583f8
,I/Messaging( 4678): mccmnc> 
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/DraftCache( 4678): [DraftCache/1] DraftCache.constructor
D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4678): [DraftCache/1] refresh
,D/MmsConfig( 4678): networkCode: 
,D/Messaging( 4678): ViewCache CreatePreloadOnlyConversationList
,D/Messaging( 4678): mNeedToUpdateDate2: false
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4678): sense_version=6.0
,D/Jerry   ( 4678): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4678): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4678): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4678): createReceiver
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1220): sku_id=99
D/TelephUtils( 1220): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
V/MmsProvider( 1220): Update uri=content://mms, match=0
,V/MmsProvider( 1220): selection=st=129 AND m_type!=134
,D/Messaging( 4678): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4678): TransactionService is going to be woken up.
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/DraftCache( 4678): [DraftCache/487] rebuildCache
,D/MmsSmsV2Provider( 1220):  phoneType = -1
I/ActivityManager(  907): Delaying start of: ServiceRecord{43827ff0 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4678): ViewCache CreatePreload
,D/Messaging( 4678): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4678): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4678): def_index: 0
,D/MsgPreferenceUtils( 4678): globalIndex = 1
,D/Messaging( 4678): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/MsgPreferenceUtils( 4678): phone state: true
D/MsgPreferenceUtils( 4678): sd state: false
,D/MsgPreferenceUtils( 4678): vIndex = 0
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/Jerry   ( 1220): URI_DRAFT
,D/DraftCache( 4678): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4678): [DraftCache/487] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4678): 
D/MmsAsyncWorkHandler( 4678): HM tk = 20002
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1220): sku_id=99
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1220): sku_id=99
,I/GAV2    ( 4363): Thread[GAThread,5,main]: No campaign data found.
,W/GA-SERVICE( 1199): Thread[Thread-67,5,main]:  Using destination https://ssl.google-analytics.com
,W/GA-SERVICE( 1199): Thread[Thread-67,5,main]:  Using destination https://ssl.google-analytics.com
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Process (  907): killProcessQuiet, pid=4089
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4089:com.htc.bgp/u0a14 (adj 15): empty #17
,I/GAV2    ( 4640): Thread[GAThread,5,main]: No campaign data found.
I/ActivityManager(  907): Recipient 4089
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/TransactionService( 4678): 1-Creating TransactionService
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4654, uid=10111, userID:0
,V/TransactionService( 4678): onStartCommand: 1
,D/MmsSystemEventReceiver( 4678): unRegisterForConnectionStateChanges
V/TransactionService( 4678): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4678): Loading previous transactions.
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1220): device_type: 1
,D/TransactionService( 4678): Force set service start id to 1
,V/TransactionService( 4678): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4678): unRegisterForConnectionStateChanges
,D/TransactionService( 4678): stopSelfResult: true, mLastHandledServiceId: 1
,I/ActivityManager(  907): Resuming delayed broadcast
V/TransactionService( 4678): Destroying TransactionService
,D/Process (  907): killProcessQuiet, pid=4565
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/TransactionService( 4678): 4-Handling incoming message: { when=-9ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  907): Killing 4565:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/PMS     (  907): acquireWL(440c4438): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4609 10154 null
I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
I/ActivityManager(  907): Recipient 4565
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4609, uid=10154, userID:0
,I/MusicLeanback( 4609): Conditions not met for autocaching.
,I/MusicLeanback( 4609): Stop autocaching.
D/PMS     (  907): releaseWL(440c4438): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,W/ActivityManager(  907): Disable JIT of com.htc.bgp
,I/ActivityManager(  907): Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4826 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,I/CalendarProvider2( 4826): Created com.android.providers.calendar.CalendarAlarmManager@41b8b088(com.android.providers.calendar.HtcCalendarProvider@41b73400)
,D/CalendarProvider2( 4826): wait start:true
,D/PMS     (  907): acquireWL(43ffff80): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4826 10014 null
,D/CalendarProvider2( 4826): wait end:false
I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  907): releaseWL(43ffff80): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/CalendarProvider2( 4826): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4826): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(42bc5708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 4535): update TASK shortcut>
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4363
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4363:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  907): Delay finish: com.google.android.music/.download.MusicCommunicator
,I/ActivityManager(  907): Resuming delayed broadcast
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  907): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4844 uid=10016 gids={50016, 3003, 5012, 2001}
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4844): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4844): Update started
,E/UpdateRequestReceiver( 4844): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/cache
,W/ContextImpl( 4844): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4609): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/cache
,I/UpdateFetcherService( 4844): Update started
,D/Process (  907): killProcessQuiet, pid=4484
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Recipient 4363
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Killing 4484:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4484
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/UpdateRequestReceiver( 4844): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4844): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4844): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/Process (  907): killProcessQuiet, pid=4591
,I/ActivityManager(  907): Killing 4591:com.htc.cloudstorage.drive/u0a68 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  907): getAllNetworkInfo called by  (2520/10021)
,I/ActivityManager(  907): Recipient 4591,
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.analytics.internal.GServicesChangedReceiver
,V/GA-SERVICE( 1199): Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1199, uid=10028, userID:0
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(42690d28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/PMS     (  907): acquireWL(4255b3b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(42690d28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getAllNetworkInfo called by  (2520/10021)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/SystemUpdateService( 1199): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/GCM     ( 1391): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/PMS     (  907): acquireWL(4243b3b8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1199 10028 null
D/PMS     (  907): releaseWL(4255b3b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/PMS     (  907): acquireWL(41d90040): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2520 10021 WorkSource{10016}
,I/DownloadManager( 2520): Download 147 starting
D/ConnectivityService(  907): getAllNetworkInfo called by  (2520/10021)
I/ActivityManager(  907): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/DownloadManager( 2520): Download 148 starting
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
D/PMS     (  907): acquireWL(42125998): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2520 10021 WorkSource{10016}
D/PMS     (  907): acquireWL(425d57a8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
W/ActivityThread( 2520): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ConnectivityService(  907): getAllNetworkInfo called by  (2520/10021)
I/SystemUpdateService( 1199): cancelUpdate (empty URL)
,I/SystemUpdateService( 1199): active receiver: disabled
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1199, uid=10028, userID:0
D/PMS     (  907): releaseWL(425d57a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/GCM     ( 1391): GCM config loaded
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/ActivityManager(  907): Resuming delayed broadcast
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/SystemUpdateService( 1199): cancelUpdate (empty URL)
,I/SystemUpdateService( 1199): active receiver: disabled
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1199, uid=10028, userID:0
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/SystemEventReceiver( 1199): Received GSERVICES_CHANGED broadcast
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): releaseWL(4243b3b8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
,I/OcrUtils( 1199): Updating ocr activity enabled=false
,I/GCoreUlr( 1461): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
D/PMS     (  907): acquireWL(43f6eb38): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1461 10028 null
,I/GCoreUlr( 1461): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4884 uid=10031 gids={50031, 3003, 5012}
,D/libc    ( 2520): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2520): [NET] getaddrinfo-,err=8
D/libc    ( 2520): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2520): [NET] getaddrinfo-, 1
,D/libc    ( 2520): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f267 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/libc    ( 2520): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2520): [NET] getaddrinfo-,err=8
D/libc    ( 2520): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2520): [NET] getaddrinfo-, 1
,D/libc    ( 2520): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =657 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 172
D/libc    (  365): [NET]res_nsend:resplen=49
D/libc    (  365): [NET]res_nsend:resplen=49
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2520): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2520): [NET] getaddrinfo_proxy-, success
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4884, uid=10031, userID:0
,D/PMS     (  907): acquireWL(420e9658): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4884, uid=10031, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4884, uid=10031, userID:0
,D/PMS     (  907): releaseWL(420e9658): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=4884, uid=10031, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4884, uid=10031, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4884, uid=10031, userID:0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/DownloadManager( 2520): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  907): acquireWL(424314e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
D/PMS     (  907): releaseWL(424314e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  907): acquireWL(4269e078): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
,D/PMS     (  907): releaseWL(4269e078): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4909 uid=10078 gids={50078, 3003, 5012}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=8 [12][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
,D/PMS     (  907): acquireWL(44384430): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
,D/PMS     (  907): releaseWL(44384430): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  907): acquireWL(42650d70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
,I/GCoreUlr( 1461): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1461): Unknown pending intent to remove.
,I/GCoreUlr( 1461): Unbound from all location providers
D/PMS     (  907): releaseWL(42650d70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  907): acquireWL(44389208): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
D/PMS     (  907): releaseWL(44389208): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  907): releaseWL(43f6eb38): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,D/PMS     (  907): acquireWL(43beedf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
,I/DownloadManager( 2520): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  907): releaseWL(43beedf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
E/PhoneMonitor( 4909): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4909): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/DownloadManager( 2520): Download 148 finished with status SUCCESS
,D/Process (  907): killProcessQuiet, pid=3712
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
I/ActivityManager(  907): Killing 3712:com.android.settings:remote/1000 (adj 15): empty #17
D/PMS     (  907): releaseWL(42125998): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4909/10078)
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3712
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=4926 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/PMS     (  907): acquireWL(43bbdfb8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
,V/BluetoothSapService( 3900): onUnbind: android.bluetooth.IBluetoothSap
D/PMS     (  907): releaseWL(43bbdfb8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/Search.GservicesUpdateTask( 2655): Updating Gservices keys
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4909/10078)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=4654
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4909/10078)
I/ActivityManager(  907): Killing 4654:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,W/Search.LoginHelper( 2655): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,W/Search.LoginHelper( 2655): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2655): canRun() : Opted Out
,I/DownloadManager( 2520): Download 147 finished with status SUCCESS
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/ActivityManager(  907): Recipient 4654
,D/PMS     (  907): acquireWL(437a1e68): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(41d90040): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/ActivityManager(  907): Killing 4520:com.google.android.apps.cloudprint/u0a97 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=4520
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  907): acquireWL(442d2790): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4926 10160 null
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
,D/Process (  907): killProcessQuiet, pid=4470
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:13474 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:13550 
I/ActivityManager(  907): Recipient 4520
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Killing 4470:com.google.android.apps.cloudprint:sync/u0a97 (adj 15): depends on provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider in dying proc com.google.android.apps.cloudprint
D/PMS     (  907): acquireWL(441f3190): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4926 10160 null
D/PMS     (  907): releaseWL(442d2790): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Delay finish: com.google.android.gms/.ads.measurement.AdsMeasurementBroadcastReceiver
D/PMS     (  907): acquireWL(4418d1d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
D/PMS     (  907): releaseWL(437a1e68): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4926/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4926/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4926, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4926, uid=10160, userID:0
,D/GCM     ( 1391): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(4418d1d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/PMS     (  907): releaseWL(441f3190): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/GCM     ( 1391): GCM config loaded
,D/PMS     (  907): acquireWL(440ceaa0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4609 10154 null
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4957 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4609): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  907): Recipient 4470
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4609, uid=10154, userID:0
,I/MusicLeanback( 4609): Conditions not met for autocaching.
,I/MusicLeanback( 4609): Stop autocaching.
D/PMS     (  907): releaseWL(440ceaa0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/CalendarApplication( 4957): onCreate
D/ProviderChangeReceiver( 4957): ---------------------------------------------------
,D/ProviderChangeReceiver( 4957): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4957): start to updateAlertNotification!
,I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4973 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AlertService( 4957): No fired or scheduled alerts
,D/HtcAlertUtils( 4957): -- cancelReminderNotification --
,D/HtcAlertUtils( 4957): broadcastExistReminder!
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4973): [4973/4973] onCreate()
W/ContextImpl( 4973): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/GCM     ( 1391): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service,
,W/ContextImpl( 4844): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.htc.cs.dm
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1246): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/ConnectivityService(  907): getAllNetworkInfo called by  (2520/10021)
,W/ContextImpl( 4844): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.google.android.videos
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
D/PMS     (  907): acquireWL(438ff2f8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2520 10021 WorkSource{10016}
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/Launcher( 1246): Deferring update until onResume
D/Launcher( 1246): waitUntilResume // bindAppsUpdated
,I/DownloadManager( 2520): Download 149 starting
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
D/ConnectivityService(  907): getAllNetworkInfo called by  (2520/10021)
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1391): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  907): getAllNetworkInfo called by  (2520/10021)
D/Process (  907): killProcessQuiet, pid=4278
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/DownloadManager( 2520): Ignoring Content-Length since Transfer-Encoding is also defined
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/ActivityManager(  907): Killing 4278:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
D/PMS     (  907): acquireWL(4346c848): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2520 10021 WorkSource{10016}
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
,I/DownloadManager( 2520): Download 150 starting
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
I/PackageManager(  907):   Scheme: "mmsto"
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getAllNetworkInfo called by  (2520/10021)
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4278
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/[PluginManager]RegisterService( 1364): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
I/[PluginManager]RegisterService( 1364): handle notify Blinkfeed plugin client changed
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(442d9108): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
D/PMS     (  907): acquireWL(424ca568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  907): acquireWL(43673470): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,I/PeopleContactsSync( 1199): CP2 sync disabled
,I/DownloadManager( 2520): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  907): releaseWL(424ca568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/DownloadManager( 2520): Download 149 finished with status SUCCESS
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
D/PMS     (  907): releaseWL(43673470): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): releaseWL(442d9108): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
I/ActivityManager(  907): Resuming delayed broadcast
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,D/PMS     (  907): releaseWL(438ff2f8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4999 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2520/10021)
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=6 [32][2][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
,D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/DownloadManager( 2520): Download 150 finished with status SUCCESS
D/PMS     (  907): releaseWL(4346c848): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4999, uid=10073, userID:0
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Finsky  ( 4999): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4999/10073)
,W/PackageManager(  907): Unable to load service info ResolveInfo{4262b590 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4999/10073)
,D/Finsky  ( 4999): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4999): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4999): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4999, uid=10073, userID:0
,D/Finsky  ( 4999): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4999): [1] 2.run: Finished loading 1 libraries.
,D/Process (  907): killProcessQuiet, pid=4742
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4742:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4742
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2655): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/Finsky  ( 4999): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PMS     (  907): acquireWL(4343e038): PARTIAL_WAKE_LOCK  AsyncService 0x1 4926 10160 null
I/ActivityManager(  907): Delaying start of: ServiceRecord{43839d70 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
D/PMS     (  907): releaseWL(4343e038): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4999): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5036 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/IcingCorporaProvider( 2655): UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,W/PackageManager(  907): Unable to load service info ResolveInfo{42c85580 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43685858 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
W/PackageManager(  907): Unable to load service info ResolveInfo{4403ed30 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/HtcFingerPrintQuickLaunchProvider( 5036): -onCreate()
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,V/Settings:HtcSettingsApplication( 5036): [5036/5036] onCreate()
D/RemoteDisplayProvider(  907): start
,D/Process (  907): killProcessQuiet, pid=4759
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4759:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4759
,D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PeopleContactsSync( 1199): CP2 sync disabled
I/[PluginManager]RegisterService( 1364): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 1364): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(440d05d0): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(440d05d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/IcingCorporaProvider( 2655): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,D/PMS     (  907): acquireWL(440b4618): PARTIAL_WAKE_LOCK  AsyncService 0x1 4926 10160 null
,D/PMS     (  907): releaseWL(440b4618): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/Settings:HtcWirelessFeatureFlags( 5036): id/is att sku: 99/false
,I/PeopleContactsSync( 1199): CP2 sync disabled
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1364): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.videos
,I/[PluginManager]RegisterService( 1364): handle notify Blinkfeed plugin client changed
,W/SystemReader( 5036): Cannot find devicepolicy_lower_fp_quality, use default value instead
,I/IcingCorporaProvider( 2655): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(43b74c40): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,W/SystemReader( 5036): Cannot find support_harman, use default value instead
,W/SystemReader( 5036): Cannot find effect_manager_id, use default value instead
,I/IcingCorporaProvider( 2655): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,E/Settings:HtcWrapHeaderInfo( 5036): no such activity!
D/PMS     (  907): releaseWL(43b74c40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4377dc38): PARTIAL_WAKE_LOCK  AsyncService 0x1 4926 10160 null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5036): The wrap header doesn't exist in header list.
D/PMS     (  907): releaseWL(4377dc38): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,E/Settings:HtcWrapHeaderInfo( 5036): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5036): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]support         :false
,W/ContextImpl( 4844): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,W/FingerprintManager( 5036): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,I/UpdateFetcherService( 4844): Update downloaded, starting installation
,E/Settings:HtcVoWifiWidgetEnabler( 5036): isSupportVoWifi: null
,I/UpdateFetcherService( 4844): Started installation
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5036): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5036): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5036): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5036): isSupportMusicChannel(): false
,I/IcingCorporaProvider( 2655): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]support         :false
,W/FingerprintManager( 5036): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 5036): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5036): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5036): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5036): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5036): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]support         :false
,W/FingerprintManager( 5036): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 5036): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5036): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5036): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5036): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5036): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5036): [supportHomeButton]support         :false
,W/FingerprintManager( 5036): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 5036): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5036): Failed to find provider info for com.htc.vowifi
,W/ContextImpl( 4844): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4844): Update downloaded, starting installation
,I/UpdateFetcherService( 4844): Started installation
,I/ConfigUpdateInstallReceiver(  907): Not installing, new version is <= current version
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41be1018 +
,I/Prism.WidgetManager( 1246): onLoadItems() +
,D/PMS     (  907): acquireWL(425649e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10073}
,V/AlarmManager(  907): sending alarm PendingIntent{4367ea68: PendingIntentRecord{425ed738 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450100333733, Int=0
,D/PMS     (  907): releaseWL(425649e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4999): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4999): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/asset   ( 1246): Copying FileAsset 0x5fa400f0 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1246): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1246): onLoadItems() -
,I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41be1018 -
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4999): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4999): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4999): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/Finsky  ( 4999): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (4999/10073)
,D/Finsky  ( 4999): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/PhoneApp( 1220): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1220): -- N1 =0
,D/PhoneApp( 1220): -- N2 =0
,D/PhoneApp( 1220): -- N3 =0
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41be1018 +
,I/Prism.WidgetManager( 1246): onLoadItems() +
,E/Prism.WidgetManager( 1246): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1246): onLoadItems() -
,I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41be1018 -
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1246): AllAppsMgr addApps, already exist: ApplicationInfo(id=19, title=Play Movies & TV, componentNameComponentInfo{com.google.android.videos/com.google.android.youtube.videos.EntryPoint} appsContainer=<ALLAPPS>)
,I/Launcher( 1246): Deferring update until onResume
,D/Launcher( 1246): waitUntilResume // bindAppsUpdated
,I/GAV2    ( 4926): Thread[GAThread,5,main]: No campaign data found.
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41be1018 +
,I/Prism.WidgetManager( 1246): onLoadItems() +
,E/Prism.WidgetManager( 1246): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1246): onLoadItems() -
,I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41be1018 -
,D/PMS     (  907): acquireWL(43aa9650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=131687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43aa9650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4253d620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4253d620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/PackageSettings(  907): Skipping PackageSetting{422810c0 com.example.hello/10355} due to missing metadata
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(440b8f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10073}
,V/AlarmManager(  907): sending alarm PendingIntent{43fc9078: PendingIntentRecord{425f5038 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450100348899, Int=0
,D/PMS     (  907): releaseWL(440b8f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/PMS     (  907): acquireWL(43fb7cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10028}
,V/AlarmManager(  907): sending alarm PendingIntent{43bc57e8: PendingIntentRecord{42382598 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140054, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=140855, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
,D/PMS     (  907): acquireWL(433835a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(43fb7cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(434772a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,D/PMS     (  907): acquireWL(43aaaf00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(433835a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43aaaf00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): releaseWL(434772a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/Finsky  ( 4999): [1] 5.onFinished: Installation state replication succeeded.
,D/AutoSetting( 1364): service - mHandler: update timezone
,D/AutoSetting( 1364): service - handleMessage() stop self
,D/AutoSetting( 1364): service - handleMessage() quit looper
,D/AutoSetting( 1364): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4727
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4727:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4727
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4826): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4826): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4826): service - onCreate()
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4826): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4826): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4826): service - mHandler: update timezone
D/AutoSetting( 4826): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4826): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4826): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4826): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4826): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4826): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1109): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41f334e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.htc.htclocationservice 2 10 4 11
,D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(4399f198): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(4399f198): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4261fab8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42ed8bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(42ed8bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424ca630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=170879, Int=0
,D/PMS     (  907): acquireWL(43bdf948): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(424ca630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42670ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=6 [15][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43c02500): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=5094 uid=10106 gids={50106, 3003, 5012}
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42668220): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 907 1000 WorkSource{10100}
,D/PMS     (  907): releaseWL(43bdf948): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42670ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44042900): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(44042900): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4373b7b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42668220): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
,D/PMS     (  907): releaseWL(4373b7b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 5094): LocationClient connecting
,D/PMS     (  907): acquireWL(43c3e1e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
,D/PMS     (  907): releaseWL(43c3e1e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 5094): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 5094): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 5094): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 5094): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 5094): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 5094): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ProviderInstaller( 5094): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(432ca210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/NewsWeather( 5094): onConnected null
,D/PMS     (  907): releaseWL(432ca210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
I/NewsWeather( 5094): Last usage 0, idle 1450100379s, sync interval 2592000s
I/NewsWeather( 5094): setPeriodicSync in seconds 2592000
,D/PMS     (  907): acquireWL(42561478): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
,D/PMS     (  907): acquireWL(426bff18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1461 10028 null
W/GCoreFlp( 1461): No location to return for getLastLocation()
,I/NewsWeather( 5094): LocationClient onConnected: location null
D/PMS     (  907): releaseWL(42561478): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(426bff18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 5094): Skip sync for lookup editions
,I/NewsWeather( 5094): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 5094): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/NewsWeather( 5094): Unrecoverable authentication exception
E/NewsWeather( 5094): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 5094): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41f12c00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 8 3 12
,D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 5094): [NET] getaddrinfo-,err=8
D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 5094): [NET] getaddrinfo-, 1
,D/libc    ( 5094): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c5f9 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 5094): [NET] getaddrinfo_proxy-, success
,D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 5094): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(43794420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,D/PMS     (  907): releaseWL(43794420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 5094): Failed to syncNewsAppData
,E/NewsWeather( 5094): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4405d220): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 114109, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(43c02500): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
,D/PMS     (  907): releaseWL(4405d220): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43478000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  907): releaseWL(43478000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,D/AutoSetting( 4826): service - handleMessage() stop self
,D/AutoSetting( 4826): service - onDestroy() END
,D/AutoSetting( 4826): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4446
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4446:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4446
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 5094): Thread[GAThread,5,main]: No campaign data found.
,D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(43f570e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=191687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43f570e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43bfb418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43bfb418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43451ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b55868): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=200949, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{434530f0: PendingIntentRecord{43908bc8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450100355471, Int=563223000
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43fdbf38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): acquireWL(440badb8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(43b55868): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43fdbf38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): releaseWL(43451ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  907): acquireWL(430723a8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
,D/PMS     (  907): releaseWL(440badb8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/CheckinService( 1199): Preparing to send checkin request
,I/EventLogService( 1199): Accumulating logs since 1450100322517
,W/EventLogAggregator( 1199): Unknown tag: install_package_attempt
W/EventLogAggregator( 1199): Unknown tag: snet
,W/EventLogAggregator( 1199): Unknown tag: snet_gcore
,I/GoogleHttpClient( 1199): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1199): Using GMS GoogleHttpClient
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [18][0][0]
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1199): awaiting user notification for token
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ba7400 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 2 14 4 12
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5123 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 5123): install
,I/MultiDex( 5123): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 5123): loading existing secondary dex files
,I/MultiDex( 5123): load found 1 secondary dex files
,I/MultiDex( 5123): install done
,I/ProviderInstaller( 5123): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1391): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 5123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG (),
I/Adreno-EGL( 5123): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5123): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5123): Local Branch: 
I/Adreno-EGL( 5123): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5123): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5123):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (5123/10028)
,I/Adreno-EGL( 5123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 5123): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5123): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5123): Local Branch: 
I/Adreno-EGL( 5123): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5123): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5123):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 5123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 5123): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5123): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5123): Local Branch: 
I/Adreno-EGL( 5123): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5123): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5123):                  aa63bbd948f41d15fc72f585e
,W/Settings( 5123): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 1199): Sending checkin request (8886 bytes)
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1199): [NET] getaddrinfo-,err=8
D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1199): [NET] getaddrinfo-, 1
,D/libc    ( 1199): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =39d8 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1199): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1199): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(426592b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,D/PMS     (  907): releaseWL(426592b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=29 [17][5][0]
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1199): awaiting user notification for token
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41bd1c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 8 3 12
,I/CheckinTask( 1199): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1199): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  907): releaseWL(430723a8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1391): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/ActivityThread( 1199): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ca3c88 that was originally bound here
E/ActivityThread( 1199): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ca3c88 that was originally bound here
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
,I/GCM     ( 1391): GCM config loaded
,D/Process (  907): killProcessQuiet, pid=4678
,I/ActivityManager(  907): Killing 4678:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4678
,D/PMS     (  907): acquireWL(42821178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42821178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(44284ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(44230d20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=234818, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5146 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,V/AlarmManager(  907): sending alarm PendingIntent{4239f028: PendingIntentRecord{426b8ba0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450100420031, Int=10800000
,D/PMS     (  907): acquireWL(441f2b48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(44284ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10047}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43f99350): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,D/PMS     (  907): releaseWL(44230d20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(441f2b48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (5146/10047)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42f52bc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/NewsWeather( 5094): Last usage 0, idle 1450100443s, sync interval 2592000s
,I/NewsWeather( 5094): setPeriodicSync in seconds 2592000
D/PMS     (  907): releaseWL(42f52bc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 5094): Skip sync for lookup editions
,I/NewsWeather( 5094): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 5094): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,E/NewsWeather( 5094): Unrecoverable authentication exception
E/NewsWeather( 5094): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 5094): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41c79908 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 10 4 12
,E/NewsWeather( 5094): Failed to syncNewsAppData
,E/NewsWeather( 5094): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): acquireWL(4237dfe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42371b70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 172042, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(43f99350): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/PMS     (  907): releaseWL(4237dfe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/Process (  907): killProcessQuiet, pid=4183
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4183:com.google.android.gm/u0a107 (adj 15): empty #17
D/PMS     (  907): releaseWL(42371b70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(41e06b58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(41e06b58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  907): Recipient 4183
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,W/GA-SERVICE( 1199): Thread[Thread-67,5,main]: hit:_gmsv=1-5089038&ul=en-gb&sr=720x1184&ht=1450100322850&a=608586971&sc=start&AppUID=10151&aid=com.google.android.apps.magazines&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&cd16=Ignoring+sync+request+for+non-current+account&v=1&t=appview&an=Google+Play+Newsstand&cd11=false&tid=UA-32428711-6&_u=.nOQKSTB&_v=ma1b6&cd=Debug&qt=124282&z=79
,W/GA-SERVICE( 1199): Thread[Thread-67,5,main]: hit:_gmsv=1-5089038&ev=0&ul=en-gb&sr=720x1184&ht=1450100322850&a=168217736&AppUID=10151&aid=com.google.android.apps.magazines&ea=Sync+Skipped&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&ec=Debug&v=1&t=event&el=&an=Google+Play+Newsstand&tid=UA-32428711-6&_u=.C&_v=ma1b6&cd=Debug&qt=124282&z=80
,D/libc    ( 1199): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
D/libc    ( 1199): [NET] getaddrinfo-,err=8
D/libc    ( 1199): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    ( 1199): [NET] getaddrinfo-, 1
,D/libc    ( 1199): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =af2d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 49
D/libc    (  365): [NET]res_nsend:resplen=102
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1199): [NET] getaddrinfo_proxy-, success
I/global  ( 1199): call createSocket() return a new socket.
D/libc    ( 1199): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1199): [NET] getaddrinfo-, SUCCESS
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(41b50f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=251687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41b50f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42408e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42408e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(43fc6f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=264897, Int=0
,D/PMS     (  907): acquireWL(43bb9618): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(43fc6f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425fb458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43bb9618): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(425fb458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42c242c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42c242c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1109): closing low battery warning: level=100
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=5163 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/ContextImpl( 5163): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 5036): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5036): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5036): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5036): Cust_ConnectToPC   : spcsc>false
D/        ( 5036): Cust_ConnectToPC   : IPT>true
,D/        ( 5036): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5036): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 5036): Index of the first 1 = -1
,W/ContextImpl( 5036): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 5036): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 5036): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5036): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5036): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5036): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5036): [ACC]android_networking:tethering_guard_support=false
,D/Process (  907): killProcessQuiet, pid=4535
,I/ActivityManager(  907): Killing 4535:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  907): Recipient 4535
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(425125e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=311687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425125e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b9a018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43b9a018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(44040268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44040268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(424c40b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=360843, Int=0
,D/PMS     (  907): acquireWL(42484778): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(424c40b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42bb19c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=5 [56][3][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43ff4758): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,D/PMS     (  907): releaseWL(42484778): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42bb19c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43c0c458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43c0c458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 5094): Last usage 0, idle 1450100569s, sync interval 2592000s
,I/NewsWeather( 5094): setPeriodicSync in seconds 2592000
,I/NewsWeather( 5094): Skip sync for lookup editions
,I/NewsWeather( 5094): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 5094): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 5094): Unrecoverable authentication exception
E/NewsWeather( 5094): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 5094): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41ca1a18 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 11 5 12
,D/PMS     (  907): acquireWL(425bbe10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,E/NewsWeather( 5094): Failed to syncNewsAppData
,E/NewsWeather( 5094): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/PMS     (  907): releaseWL(425bbe10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43b784c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 235292, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(43ff4758): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
,D/PMS     (  907): releaseWL(43b784c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(442d6d60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(442d6d60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(43ab2a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=371686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43ab2a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4407dcd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4407dcd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(42670140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=390898, Int=0
,D/PMS     (  907): acquireWL(430b5e20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4435c898): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42670140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): releaseWL(430b5e20): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(4435c898): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/GLSActivity( 1391): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1391): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1391): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1391): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1391): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1391): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/PlayEventLogger( 4999): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4999): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4999): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41e0e830 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 14 4 12
,D/libc    ( 4999): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4999): [NET] getaddrinfo-,err=8
D/libc    ( 4999): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4999): [NET] getaddrinfo-, 1
,D/libc    ( 4999): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ee2f +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4999): [NET] getaddrinfo_proxy-, success
I/global  ( 4999): call createSocket() return a new socket.
D/libc    ( 4999): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4999): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4999): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4999): [NET] getaddrinfo-,err=8
,I/jxcore-log( 3841): Connected to the server!
I/jxcore-log( 3841): 
,I/chromium( 3841): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  907): acquireWL(4409c1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=431687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4409c1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c0fb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c0fb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43f997b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=491687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43f997b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4345c308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4345c308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1109): closing low battery warning: level=100
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(438c44a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(438c44a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(442d74f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=551687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(442d74f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4262bcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4262bcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b7bd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b7bd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42f544e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=611687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42f544e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43fc3ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=612507, Int=0
,D/PMS     (  907): acquireWL(4421a720): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(43fc3ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42f04b28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): acquireWL(426b3448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(426b3448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
,D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3958): environment dirty rate=7 [101][8][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43701d30): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106},
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PMS     (  907): releaseWL(4421a720): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42f04b28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
I/NewsWeather( 5094): Last usage 0, idle 1450100820s, sync interval 2592000s
,I/NewsWeather( 5094): setPeriodicSync in seconds 2592000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(424b7bd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(424b7bd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,I/NewsWeather( 5094): Skip sync for lookup editions
,I/NewsWeather( 5094): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 5094): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 5094): Unrecoverable authentication exception
E/NewsWeather( 5094): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 5094): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41b5b660 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1109): com.google.android.gms 1 10 5 12
D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 5094): [NET] getaddrinfo-,err=8
D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 5094): [NET] getaddrinfo-, 1
,D/libc    ( 5094): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =adb1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 5094): [NET] getaddrinfo_proxy-, success
,D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 5094): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(4215a600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,E/NewsWeather( 5094): Failed to syncNewsAppData
,E/NewsWeather( 5094): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(4215a600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 361403, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): acquireWL(43b77cb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(43701d30): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
D/PMS     (  907): releaseWL(43b77cb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4305a870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(4305a870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1220): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1220): sku_id=99
D/ContactMessageStore( 1220): start background delete task...
,D/ContactMessageStore( 1220): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1220): size: 0 , 0
,D/ContactMessageStore( 1220): Background delete complete
,D/PMS     (  907): acquireWL(42f863d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42f863d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4406c9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(43469a80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=642555, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(4406c9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(437e7300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43469a80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(437e7300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(426234e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=671686, Int=0
I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426234e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43fdca18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43fdca18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43bd79f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=731686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43bd79f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42fd8f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42fd8f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  907): killProcessQuiet, pid=4884
,I/ActivityManager(  907): Killing 4884:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4884
,D/PMS     (  907): acquireWL(42ee88d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=791687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42ee88d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4404c6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4404c6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43ff0830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=851686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43ff0830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43aa8620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43aa8620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(425a9410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=911686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425a9410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440c43f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440c43f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(41fdd658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=971686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41fdd658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44025e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44025e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4262b600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41e356b0: PendingIntentRecord{42484638 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=780653, Int=0
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{4251de28: PendingIntentRecord{4254bbb0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450101140611, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{41e60738: PendingIntentRecord{42f16b88 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450101218699, Int=0
,W/ContextImpl( 5163): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  907): Done.
,D/PowerUsageService( 5163): call getInstance()
D/ConnectivityService(  907): Setting timer for 720seconds
,D/PowerUsageList:PowerUsageHelper( 5163): MY_DEBUG = false
,D/PMS     (  907): acquireWL(42615170): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5163 1000 null
,D/SmartSyncUtils( 5163): isEpsOn(), nState = 0
D/PMS     (  907): releaseWL(4262b600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): releaseWL(42615170): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  907): acquireWL(43fdb550): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5163 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5163): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5163): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5163): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 7
,I/FeedHostManager( 1246): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
D/SmartSyncScreenOnOffTimeReceiver( 5163): AlarmOnTime = -1
,I/FeedHostManager( 1246): NightMode begin at 0, end at 7
,D/SmartSyncScreenOnOffTimeReceiver( 5163): SettingOnTime = 1450159200000, randomSettingOnTime = 1450158727000
,D/SmartSyncScreenOnOffTimeReceiver( 5163): SettingOffTime = 1450137600000, randomSettingOffTime = 1450143560000
W/ContextImpl( 5163): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,D/PMS     (  907): acquireWL(42588078): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1246 10075 null
D/SmartSyncScreenOnOffTimeReceiver( 5163): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 5163): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5163): bNightModeTurnOffOnce = false
,I/FeedHostManager( 1246): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1450101218890, BeginTime: 1450134000000, EndTime: 1450159200000
D/PMS     (  907): releaseWL(43fdb550): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  907): releaseWL(42588078): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(4403e6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10028}
,V/AlarmManager(  907): sending alarm PendingIntent{42c747b8: PendingIntentRecord{4239ed80 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1013602, Int=0
,D/PMS     (  907): acquireWL(43bcfb80): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1391 10028 null
,D/PMS     (  907): releaseWL(43bcfb80): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  907): releaseWL(4403e6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  907): acquireWL(440afa10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,D/PMS     (  907): releaseWL(440afa10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  907): acquireWL(43a9d780): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1391 10028 null
,D/GCM     ( 1391): Message class mow
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1391/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1391/10028)
,D/PMS     (  907): releaseWL(43a9d780): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  907): acquireWL(442acbe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,D/PMS     (  907): releaseWL(442acbe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  907): acquireWL(434983c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1031687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(434983c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b841e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b841e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4255d7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1091687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4255d7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(429aa4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(429aa4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43a296b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1115313, Int=0
,D/PMS     (  907): acquireWL(426236b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(43a296b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4257d858): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=4 [170][8][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3958): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42f05a90): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3958): nl80211: survey data missing!
E/wpa_supplicant( 3958): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3958): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(426236b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  907): releaseWL(4257d858): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(432def78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/NewsWeather( 5094): Last usage 0, idle 1450101323s, sync interval 2592000s
,I/NewsWeather( 5094): setPeriodicSync in seconds 2592000
D/PMS     (  907): releaseWL(432def78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 5094): Skip sync for lookup editions
,I/NewsWeather( 5094): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 5094): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1391): GoogleAccountDataService.getToken()
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1391): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1391): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1527): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1109): com.google.android.gms (false,0)
,E/NewsWeather( 5094): Unrecoverable authentication exception
E/NewsWeather( 5094): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 5094): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 5094): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{41cde2f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 5094): [NET] getaddrinfo-,err=8
D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 5094): [NET] getaddrinfo-, 1
,D/libc    ( 5094): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a4ac +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 5094): [NET] getaddrinfo_proxy-, success
,I/RemoteViews.Performance( 1109): com.google.android.gms 2 13 6 12
,D/libc    ( 5094): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 5094): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(43fb96b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1391 10028 null
,E/NewsWeather( 5094): Failed to syncNewsAppData
,D/PMS     (  907): releaseWL(43fb96b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 5094): Down sync of news app Failed, error code: SYNC_IO_ERROR,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43bfb0c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 613106, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(42f05a90): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1461/10028)
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(43bfb0c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4402b300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(4402b300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(43c3c560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e01288: PendingIntentRecord{424d8ec8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1145375, Int=0
,D/PMS     (  907): acquireWL(43469ab8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43c3c560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426a5618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43469ab8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(426a5618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(4383b070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1151687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4383b070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43467b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43467b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(439a8370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1211686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(439a8370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(433f62a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(433f62a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(43105d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1271686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43105d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44080390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44080390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c33060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1331687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c33060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43804ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43804ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4257f1a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1391686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4257f1a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425b0e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425b0e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4267dfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1451686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4267dfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42604338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42604338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(425f9a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1511686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425f9a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43bb1b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43bb1b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43fd9d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1571686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43fd9d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43057c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43057c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43163178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1631686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43163178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425aad18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425aad18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c181f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1691687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c181f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b6db28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b6db28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4341baf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1751687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4341baf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440baa28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440baa28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(43667e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1811687, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43667e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42632328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42632328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(44198878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41de3cd8: PendingIntentRecord{41de38f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1871686, Int=0
,I/IntentController( 1109): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  907): Prepared write state in 47ms
,I/ProcessStatsService(  907): Prepared write state in 19ms
,D/PMS     (  907): releaseWL(44198878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2015-12-13-11-56-47.bin
,D/PMS     (  907): acquireWL(430f8498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1527): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1527): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1109): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(430f8498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1109): closing low battery warning: level=100
D/PowerUI ( 1109): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1109): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5218): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5218): ====startRecUseTime====
D/htc.customization.log.level( 5218):  is 
W/CustomizationLogLevel( 5218): Level value is invalid, use default level 2
D/CustomizationManager( 5218):  Read ACC file spent 0.093 (s)
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5218): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5218): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5218): Parsing tag category name = system
I/CustomizationCIDLoader( 5218): Parsing tag category name = application
I/CustomizationCIDLoader( 5218): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5218): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5218): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5218): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5218): Parsing tag category name = Settings
D/CustomizationManager( 5218):  Read CID file spent 0.144 (s)
D/CustomizationManager( 5218):  All configurations done spent 0.144 (s)
W/HtcNativeFlag( 5218): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5218): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5218): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5218): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=5218, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=3841
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907): Killing 3841:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  907):   Force finishing activity ActivityRecord{4430a0e0 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  907): Copying FileAsset 0x63db1a58 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  907): Skipping PackageSetting{422810c0 com.example.hello/10355} due to missing metadata
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1185): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3841 uid 10348
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1527): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1527): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1527): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1774): Unregistering com.test.thalitest
E/acms    ( 1774): Could not unregister removed application com.test.thalitest
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1461): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(43441ef0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1461 10028 null
D/PMS     (  907): releaseWL(43441ef0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1274): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  907): WIN DEATH: Window{44192090 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  907): Client connection lost with reason: 4
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/Launcher( 1246): Deferring update until onResume
D/Launcher( 1246): waitUntilResume // bindAppsRemoved
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/ExternalAccountType( 1307): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5233 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 5233): install
I/MultiDex( 5233): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5233): loading existing secondary dex files
I/MultiDex( 5233): load found 1 secondary dex files
I/MultiDex( 5233): install done
I/ActivityManager(  907): Delaying start of: ServiceRecord{441d4b10 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 1199): CP2 sync disabled
I/Icing   ( 1199): doRemovePackageData com.test.thalitest
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
D/PMS     (  907): acquireWL(4230c100): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
I/ProviderInstaller( 5233): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(4230c100): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5251 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 5251): install
I/MultiDex( 5251): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5251): loading existing secondary dex files
I/MultiDex( 5251): load found 1 secondary dex files
I/MultiDex( 5251): install done
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ProviderInstaller( 5251): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1364): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1364): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
D/Process (  907): killProcessQuiet, pid=4909
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4909:com.google.android.setupwizard/u0a78 (adj 15): empty #17
D/Prism.PackageStateRece_( 1246): action: android.intent.action.PACKAGE_REMOVED
W/PackageManager(  907): Unable to load service info ResolveInfo{42628468 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
I/IcingCorporaProvider( 2655): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5274 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteDBG( 2655): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca929d8
W/dalvikvm( 2655): threadid=14: thread exiting with uncaught exception (group=0x4171ee30)
E/AndroidRuntime( 2655): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2655): Process: com.google.android.googlequicksearchbox:search, PID: 2655
E/AndroidRuntime( 2655): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 2655): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2655): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2655): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 2655): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 2655): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
E/AndroidRuntime( 2655): 	at cid.d(PG:192)
E/AndroidRuntime( 2655): 	at clo.g(PG:594)
E/AndroidRuntime( 2655): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2655): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2655): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2655): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2655): 	at clr.tL(PG:827)
E/AndroidRuntime( 2655): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2655): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2655): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2655): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2655): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2655): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  907): Recipient 4909
D/Process ( 2655): killProcess, pid=2655
D/Process ( 2655): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
W/ContextImpl( 5274): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 5274): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5274): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5274): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5274): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5274): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5274): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5274): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5274): threadid=10: thread exiting with uncaught exception (group=0x4171ee30)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5274): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5274): Process: com.android.keychain, PID: 5274
E/AndroidRuntime( 5274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5274): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5274): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5274): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5274): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5274): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5274): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5274): killProcess, pid=5274
D/Process ( 5274): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450102120213.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
I/ActivityManager(  907): Recipient 5274
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 5274) has died.
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5290 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2655): Died!
I/ActivityManager(  907): Recipient 2655
I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 2655) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
E/SQLiteLog( 5233): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 5233): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca5b888
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/DriveAsyncService( 5233): disk I/O error (code 3850)
E/DriveAsyncService( 5233): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 5233): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 5233): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 5233): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 5233): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 5233): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 5233): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 5233): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 5233): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 5233): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 5233): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 5233): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 5233): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 5233): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 5233): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/AppTag  ( 5290): getInstance(Context context)
D/AppTag  ( 5290): getInstance(Context context)
E/SQLiteLog( 5233): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
D/AppTag  ( 5290): onCreate()
E/SQLiteDBG( 5233): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca5b888
E/DocListDatabase( 5233): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 5233): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 5233): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 5233): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 5233): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 5233): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 5233): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 5233): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 5233): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 5233): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 5233): 	at chr.a(SourceFile:75)
E/DocListDatabase( 5233): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 5233): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 5233): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 5233): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 5233): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 5233): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 5233): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 5233): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 5233): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 5233): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 5233): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 5233): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5233): threadid=1: thread exiting with uncaught exception (group=0x4171ee30)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 5233): FATAL EXCEPTION: main
E/AndroidRuntime( 5233): Process: com.google.android.gms.drive, PID: 5233
E/AndroidRuntime( 5233): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5233): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 5233): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 5233): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 5233): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5233): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5233): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5233): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5233): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5233): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5233): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5233): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5233): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5233): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5233): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 5233): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5233): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5233): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 5233): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 5233): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 5233): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 5233): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 5233): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 5233): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 5233): 	... 10 more
D/Process ( 5233): killProcess, pid=5233
D/Process ( 5233): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
D/PMS     (  907): acquireWL(43468788): PARTIAL_WAKE_LOCK  AsyncService 0x1 4926 10160 null
D/PMS     (  907): releaseWL(43468788): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5308 uid=10098 gids={50098, 3003, 5012}
D/Process (  907): killProcessQuiet, pid=4609
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4609:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  907): Recipient 5233
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 5233) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 10861ms
I/ActivityManager(  907): Recipient 4609
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 4609): Died!
I/DeviceManagement( 5308): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5308 dbg=false s=true
I/DeviceManagement( 5308): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5308): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5308): WorkflowService: Starting workflow service
I/DeviceManagement( 5308): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b7d038] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5308): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5308): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5308): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5308): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5322 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5308): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5308): SessionStateController: Checking invariants...
D/Documents( 5322): Loading roots for com.android.providers.downloads.documents
D/Documents( 5322): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5322): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5322): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5322): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5322): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5322): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5322): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5322): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5322): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5322): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5322): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5322): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5322): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5322): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5322): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5322): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5322): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5322): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5322): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5322): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5322): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5322): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5322): threadid=1: thread exiting with uncaught exception (group=0x4171ee30)
D/Process (  907): killProcessQuiet, pid=4957
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5336 uid=10023 gids={50023, 1028, 1015, 1023}
E/AndroidRuntime( 5322): FATAL EXCEPTION: main
E/AndroidRuntime( 5322): Process: com.android.documentsui, PID: 5322
E/AndroidRuntime( 5322): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5322): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5322): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5322): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5322): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5322): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5322): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5322): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5322): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5322): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5322): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5322): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5322): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5322): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5322): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5322): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5322): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5322): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5322): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5322): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5322): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5322): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5322): 	... 10 more
I/ActivityManager(  907): Killing 4957:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
D/GCM     ( 1391): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  907): Recipient 4957
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450102120566.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
D/Process ( 5322): killProcess, pid=5322
D/Process ( 5322): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 5322
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  907): killProcessQuiet, pid=4973
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4973:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  907): Process com.android.documentsui (pid 5322) has died.
D/GCM     ( 1391): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ExternalStorage( 5336): After updating volumes, found 1 active roots
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4973
E/SQLiteDatabase( 5308): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5308): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5308): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5308): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5308): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5308): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5308): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5308): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5308): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 5308): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5308): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5308): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5308): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5308): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5308): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 5308): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5308): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5308): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5352 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5308): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5308): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5308): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5308): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5308): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5308): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5308): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5308): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5308): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 5308): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b7d038]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 5308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5308): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5308): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5308): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5308): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5308): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5308): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5308): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5308): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 5308): WorkflowService: Stopping workflow service
D/PMS     (  907): acquireWL(440031e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  907): sending alarm PendingIntent{41e356b0: PendingIntentRecord{42484638 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1730413, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{4260c1d0: PendingIntentRecord{426ba710 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1851376, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{4251de28: PendingIntentRecord{4254bbb0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450102040611, Int=900000
D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
E/SQLiteDatabase( 5352): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 5352): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5352): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5352): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5352): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5352): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 5352): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 5352): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 5352): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 5352): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5352): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5352): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5352): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 5352): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 5352): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5352): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5352): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5352): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5352): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 5352): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 5352): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 5352): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 5352): 	at android.app.IntentService$,ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 5352): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5352): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5352): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
