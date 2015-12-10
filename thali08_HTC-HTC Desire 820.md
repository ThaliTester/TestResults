#### Test 50650278c17c777_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main,
I/SensorManager(  900): mEventCount = 1200
E/cutils-trace( 3856): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3856): ====startRecUseTime====
D/htc.customization.log.level( 3856):  is 
W/CustomizationLogLevel( 3856): Level value is invalid, use default level 2
--------- beginning of /dev/log/system
D/PMS     (  900): acquireWL(444ac4f8): PARTIAL_WAKE_LOCK  Icing 0x1 1193 10028 null
D/CustomizationManager( 3856):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3856): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3856): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3856): Parsing tag category name = system
I/CustomizationCIDLoader( 3856): Parsing tag category name = application
I/CustomizationCIDLoader( 3856): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3856): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3856): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3856): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3856): Parsing tag category name = Settings
D/CustomizationManager( 3856):  Read CID file spent 0.106 (s)
D/CustomizationManager( 3856):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 3856): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3856): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3856): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3856): Fail to get flag for type 'language', use default value: -1
D/PMS     (  900): releaseWL(444ac4f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  900): acquireWL(4442fb08): PARTIAL_WAKE_LOCK  Icing 0x1 1193 10028 null
D/PMS     (  900): releaseWL(4442fb08): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  900): acquireWL(443cd4f8): PARTIAL_WAKE_LOCK  Icing 0x1 1193 10028 null
W/CpuWake (  900): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  900): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  900): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  900): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  900): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  900): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  900): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3856
D/PMS     (  900): acquireHCC(443bbec0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 900 1000 null
D/PMS     (  900): acquireHCC(442aa8a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 900 1000 null
D/PMS     (  900): releaseWL(443cd4f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
W/asset   (  900): Copying FileAsset 0x6f30cb98 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  900): @test_code: getHtcIntentFlag: 0 obj: 1116979016
D/PMS     (  900): acquireWL(441ed0b8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 900 1000 null
I/FeedHostManager( 1242): [onPause]
I/FeedProviderManager( 1242): onPause
I/FeedHostManager( 1242): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d94590
I/SocialFeedProvider( 1242): +onPause
I/SocialFeedProvider( 1242): -onPause
I/ActivityManager(  900): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3871 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
D/PMS     (  900): acquireWL(43fd0700): PARTIAL_WAKE_LOCK  Icing 0x1 1193 10028 null
I/TrimMemoryManager( 1242): [trimMemory] 20
W/asset   ( 3871): Copying FileAsset 0x5c892428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  900): releaseWL(43fd0700): PARTIAL_WAKE_LOCK  Icing 0x1 null
V/WebViewChromiumFactoryProvider( 3871): Binding Chromium to main looper Looper (main, tid 1) {41b3dea0}
I/LibraryLoader( 3871): Expected native library version number "",actual native library version number ""
I/chromium( 3871): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3871): Initializing chromium process, renderers=0
D/PMS     (  900): acquireWL(43a3b7b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  900): acquireWL(439f91d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
W/System.err(  900): java.lang.Throwable: stack dump
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42448528:true
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3871): 1102396688: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  900): releaseWL(43a3b7b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3871): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3871): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3871): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3871): Local Branch: 
I/Adreno-EGL( 3871): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3871): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3871):                  aa63bbd948f41d15fc72f585e
W/chromium( 3871): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3871): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3871): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3871): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3871): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3871): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3871): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3871): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3871): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3871): CordovaWebView is running on device made by: HTC
,W/AwContents( 3871): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  900): Displayed com.test.thalitest/.MainActivity: +279ms
I/InputMethodManagerService(  900): Disable input method client, pid=1242
I/InputMethodManagerService(  900): Enable input method client, pid=3871
W/ResourceType( 3871): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3871): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b85298, mServedView=org.apache.cordova.engine.SystemWebView{41b4b028 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 3871): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1178): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1178): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1178): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1178): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  900): releaseWL(441ed0b8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 3871): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3871): JniHelper::setJavaVM(0x41614048), pthread_self() = 1662795520
D/JX-Cordova( 3871): jxcore cordova android initializing
W/dalvikvm( 3871): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 11.630MB for 143930-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 11.745MB for 215890-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 11.919MB for 323830-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 12.192MB for 485740-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 12.595MB for 728606-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 14.031MB for 1639352-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 15.434MB for 2459024-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 17.427MB for 3688532-byte allocation
W/CpuWake (  900): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  900): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  900): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  900): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  900): >>release mCpuPerf_Freq wakelock
W/CpuWake (  900): <<release mCpuPerf_Freq wakelock
D/PMS     (  900): releaseHCC(443bbec0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  900): releaseHCC(442aa8a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3871): Initializing JXcore engine
,W/jxcore-log( 3871): JXcore engine is ready
,W/jxcore-log( 3871): Starting JXcore engine
,W/jxcore-log( 3871): Platform android
W/jxcore-log( 3871): 
,W/jxcore-log( 3871): Process ARCH arm
W/jxcore-log( 3871): 
,I/jxcore-log( 3871): JXcore Cordova bridge is ready!
I/jxcore-log( 3871): 
,W/jxcore-log( 3871): JXcore engine is started
,I/chromium( 3871): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3871): Toggling radios to true
I/jxcore-log( 3871): 
,D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  900): checking for enable restriction...
,D/BluetoothManagerService(  900): checkBTEasState, ret=true
I/BluetoothManagerService(  900): isBluetoothRestricted(): false
,D/BluetoothManagerService(  900): enable(): region ID = 6
D/BluetoothManagerService(  900): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  900): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  900): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  900): Settings:Agentvalue: 1
,W/Settings:Agent(  900): >> traceCallingStack()
W/Settings:Agent(  900): Process.myPid(): 900
W/Settings:Agent(  900): Process.myTid(): 911
,W/Settings:Agent(  900): Process.myUid(): 1000
W/Settings:Agent(  900): 
W/Settings:Agent(  900): 
,W/System.err(  900): java.lang.Throwable: stack dump
,W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  900): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  900): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  900): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  900): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  900): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  900): 
,W/Settings:Agent(  900): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  900): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  900): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3871): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  900): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  900): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  900): Settings:Agentvalue: 2
W/Settings:Agent(  900): >> traceCallingStack()
W/Settings:Agent(  900): Process.myPid(): 900
W/Settings:Agent(  900): Process.myTid(): 1237
W/Settings:Agent(  900): Process.myUid(): 1000
W/Settings:Agent(  900): 
W/Settings:Agent(  900): 
W/System.err(  900): java.lang.Throwable: stack dump
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  900): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  900): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  900): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  900): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  900): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  900): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  900): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  900): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  900): 
,W/Settings:Agent(  900): << traceCallingStack(): 1(ms)
D/WifiService(  900): setWifiEnabled: true pid=3871, uid=10348
E/WifiService(  900): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  900): New client listening to asynchronous messages
I/WifiService(  900): isSprintWifiRestricted(): false
I/WifiService(  900): isMdmWifiRestricted(): false
D/WifiSettingsStore(  900): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,I/ActivityManager(  900): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3917 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3871): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 3871): reconnect: Base Package Name=com.test.thalitest, uid=10348
,I/jxcore-log( 3871): Radios toggled
I/jxcore-log( 3871): 
D/PMS     (  900): acquireWL(423fbfb0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 900 1000 null
,D/AdapterServiceConfig( 3917): Adding HeadsetService
D/AdapterServiceConfig( 3917): Adding A2dpService
D/AdapterServiceConfig( 3917): Adding HidService
D/AdapterServiceConfig( 3917): Adding HealthService
D/AdapterServiceConfig( 3917): Adding PanService
,D/AdapterServiceConfig( 3917): Adding GattService
,W/linker  ( 3917): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3917): REFCOUNT: CREATED. INSTANCE_COUNT1
W/System.err(  900): java.lang.Throwable: stack dump
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42316328:true
,W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3917): make
,I/BluetoothAdapterState( 3917): Entering OffState
D/PMS     (  900): releaseWL(439f91d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3917): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  900): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  900): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  900): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  900): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  900): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapter( 3917): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b56bf0
,D/BluetoothAdapter( 3917): onBluetoothServiceUp done
,D/BluetoothAdapter( 3871): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41b57198
,D/BluetoothAdapter( 3871): onBluetoothServiceUp done
,D/BluetoothAdapter( 1402): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41dbcd08
,D/BluetoothAdapter( 1402): onBluetoothServiceUp done
D/BluetoothAdapter(  900): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@423d7cd0
D/BluetoothAdapter(  900): onBluetoothServiceUp done
D/BluetoothAdapter( 1103): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f96a20
,D/BluetoothAdapter( 1103): onBluetoothServiceUp done
D/BluetoothAdapter( 1225): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c78400
,D/BluetoothAdapter( 1225): onBluetoothServiceUp done
,D/BluetoothAdapter( 1214): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41dabda8
D/BluetoothAdapter( 1214): onBluetoothServiceUp done
D/BluetoothAdapter( 1736): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@421515a8
,D/BluetoothAdapter( 1736): onBluetoothServiceUp done
,D/BluetoothManagerService(  900): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3917): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3917): Setting state to 11
I/BluetoothAdapterState( 3917): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3917): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  900): +onBluetoothStateChange prev=10 new=11
,D/BluetoothManagerService(  900): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothBondStateMachine( 3917): make
,D/BluetoothManagerService(  900): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  900): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1103): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3917): StableState(): Entering Off State
,I/ActivityManager(  900): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3942 uid=10037 gids={50037, 3002, 3001}
,D/HeadsetService( 3917): Received start request. Starting profile...
D/HeadsetStateMachine( 3917): Version 1.6
,D/HeadsetStateMachine( 3917): make
,I/BluetoothAdapterState( 3917): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 3917): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3917): Received start request. Starting profile...
V/Avrcp   ( 3917): make
,D/Avrcp   ( 3917): fillIntentFilter()
,D/A2dpStateMachine( 3917): make
,I/QuickSettingBluetooth( 1103): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 3917): Enter Disconnected: -2
,D/HidService( 3917): Received start request. Starting profile...
,D/HealthService( 3917): Received start request. Starting profile...
,D/HtcBtWidget_BTWidgetProvider( 3942): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3942): updateWidget(context) for widget: 
,D/PanService( 3917): Received start request. Starting profile...
,D/BluetoothTethering(  900): supplyMessenger
,D/BluetoothTethering(  900): supplyMessenger mAsyncChannel is null
,D/BluetoothTethering(  900): got MESSAGE_CONNECT_PANSERVICE, call connect
D/Process (  900): killProcessQuiet, pid=3012
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/BluetoothTethering(  900): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 3917): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BtGatt.DebugUtils( 3917): handleDebugAction() action=null
D/BtGatt.GattService( 3917): Received start request. Starting profile...
,D/BtGatt.GattService( 3917): start()
V/BluetoothPbapService( 3917): Pbap Service onCreate
,V/BluetoothPbapService( 3917): Starting PBAP service
,D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 11
I/ActivityManager(  900): Killing 3012:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  900): Recipient 3012
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 11
E/BluetoothMasService( 3917): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3917): Add permission for SmsProvider.
V/BluetoothMasService( 3917): Starting MAS instances
D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 11
I/MailMessageReceiver( 3917): reg:com.android.bluetooth.btservice.AdapterApp@41b4a158 with com.htc.util.mail.MailMessageReceiver@41b8a088
I/MailManager( 3917): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b8a088
V/EmailUtils( 3917): Manager Instance is not NULL
,I/ActivityManager(  900): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3962 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  900): interfaceAdded wlan0
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/Tethering(  900): wlan0 is not a tetherable iface, ignoring
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
,D/Tethering(  900): interfaceStatusChanged wlan0, false
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/Tethering(  900): interfaceAdded p2p0
D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/Tethering(  900): p2p0 is not a tetherable iface, ignoring
,D/Tethering(  900): interfaceLinkStateChanged p2p0, false
,D/Tethering(  900): interfaceStatusChanged p2p0, false
,D/PMS     (  900): releaseWL(423fbfb0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/libc    (  900): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 3917): ============NULL aList========
,V/EmailUtils( 3917): <-getEmailAccountIdList
,V/BluetoothMasService( 3917): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 11
V/BluetoothMasService( 3917): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3917): Manager Instance is not NULL
,D/EmailUtils( 3917): ============NULL aList========
,V/EmailUtils( 3917): <-getEmailAccountIdList
,V/BluetoothSapService( 3917): Sap Service onCreate
,V/BluetoothSapService( 3917): initBinder
V/BluetoothSapService( 3917): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b8f478
,V/BluetoothSapReceiver( 3917): BluetoothSapReceiver init
,D/BluetoothSapService( 3917): setSapService()
V/BluetoothSapService( 3917): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3917): state: 12
,D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 11
,D/BluetoothAdapterService( 3917): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3917): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3917): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3917): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 3917): CMD_CHANNEL_FULL_CONNECTION
D/HeadsetPhoneState( 3917): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothTethering(  900): got CMD_CHANNEL_FULLY_CONNECTED
,D/BluetoothAdapterService( 3917): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3917): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/Process (  900): killProcessQuiet, pid=3702
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/BluetoothMasReceiver( 3917): Bluetooth STATE CHANGED to 11
I/ActivityManager(  900): Killing 3702:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Recipient 3702
,D/WifiService(  900): Client connection lost with reason: 4
,I/ActivityManager(  900): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3980 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
I/qcom-bluetooth( 3984): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,I/qcom-bluetooth( 3998): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3980): Received state change = 11
,I/qcom-bluetooth( 3999): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** ,
,I/qcom-bluetooth( 4001): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4002): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,D/WifiService(  900): New client listening to asynchronous messages,
I/qcom-bluetooth( 4004): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 4005): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/Process (  900): killProcessQuiet, pid=3391
,I/ActivityManager(  900): Killing 3391:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Recipient 3391
,D/MediaRouterService(  900): Client com.google.android.music (pid 3391): Died!
,I/wpa_supplicant( 4009): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4009): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4009): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4009): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4009): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4009): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4009): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4009): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4009): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4009): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4009): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4009): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4009): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4009): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4009): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4009): update_config=1
D/wpa_supplicant( 4009): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4009): device_name='Android_63cc'
D/wpa_supplicant( 4009): manufacturer='HTC'
D/wpa_supplicant( 4009): model_name='HTC_PHONE'
D/wpa_supplicant( 4009): model_number='1234'
D/wpa_supplicant( 4009): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4009): p2p_oper_reg_class=126
D/wpa_supplicant( 4009): p2p_oper_channel=36
D/wpa_supplicant( 4009): p2p_ssid_postfix='-Android_63cc'
,D/wpa_supplicant( 4009): persistent_reconnect=1
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 3
,I/wpa_supplicant( 4009): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4009): nl80211: RFKILL status not available
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4009): nl80211: Using driver-based roaming
D/wpa_supplicant( 4009): nl80211: TDLS supported
D/wpa_supplicant( 4009): nl80211: TDLS external setup,
D/wpa_supplicant( 4009): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4009): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4009): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4009): nl80211: Enable multi-channel concurrent (driver advertised support),
D/wpa_supplicant( 4009): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4009): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4009): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4009): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8a44758
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758,
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a44758
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4009): htc_wext_command_init +
E/wpa_supplicant( 4009): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4009): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4009): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4009): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4009): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4009): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4009): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4009): nl80211: 5170-5250 @ 80 MHz,
D/wpa_supplicant( 4009): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4009): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  900): interfaceLinkStateChanged p2p0, false
D/Tethering(  900): interfaceStatusChanged p2p0, false
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/Tethering(  900): interfaceLinkStateChanged p2p0, false
D/Tethering(  900): interfaceStatusChanged p2p0, false
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  900): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  900): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1103): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1103): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  900): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4010 uid=10048 gids={50048}
D/HtcWiFiWidget_WiFiWidgetProvider( 4010): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 4010): updateWidget(context) for widget: 
,D/Process (  900): killProcessQuiet, pid=3373
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  900): Killing 3373:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/QuickSettingWifi( 1103): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,I/wpa_supplicant( 4009): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4009):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4009):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4009):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): nl80211: Flush PMKIDs
E/wpa_supplicant( 4009): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4009): State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 4022): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/qcom-bluetooth( 4023): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 4009): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4009): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4009): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4009): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4009): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4009): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4009): Using existing control interface directory.
D/wpa_supplicant( 4009): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4009): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
D/wpa_supplicant( 4009): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4009): P2P: Own listen channel: 6
D/wpa_supplicant( 4009): P2P: Configured operating channel: 126:36
D/wpa_supplicant( 4009): P2P: Add operating class 81
I/ActivityManager(  900): Recipient 3373
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/wpa_supplicant( 4009): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4009): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4009): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4009): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4009): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4009): disable_scan_offload=1
D/wpa_supplicant( 4009): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4009): update_config=1
D/wpa_supplicant( 4009): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4009): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4009): manufacturer='HTC'
D/wpa_supplicant( 4009): model_name='HTC Desire 820'
D/wpa_supplicant( 4009): model_number='HTC Desire 820'
D/wpa_supplicant( 4009): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4009): persistent_reconnect=1
D/wpa_supplicant( 4009): p2p_disabled=1
D/wpa_supplicant( 4009): hs20=1
D/wpa_supplicant( 4009): interworking=1
D/wpa_supplicant( 4009): Line: 18 - start of a new network block
D/wpa_supplicant( 4009): key_mgmt: 0x2
D/wpa_supplicant( 4009): priority=1 (0x1)
D/wpa_supplicant( 4009): signinfail=0 (0x0)
I/bt-btu  ( 3917): btu_task pending for preload complete event
,I/ActivityManager(  900): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4027 uid=10077 gids={50077}
,D/PMS     (  900): acquireWL(425ab7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10077}
V/AlarmManager(  900): sending alarm PendingIntent{42571698: PendingIntentRecord{42566230 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449746247762, Int=60000
,D/PMS     (  900): releaseWL(425ab7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/wpa_supplicant( 4009): Priority group 1
D/wpa_supplicant( 4009):    id=0 ssid='NG700'
I/wpa_supplicant( 4009): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4009): nl80211: RFKILL status not available
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 95
,D/wpa_supplicant( 4009): nl80211: Using driver-based roaming
D/wpa_supplicant( 4009): nl80211: TDLS supported
D/wpa_supplicant( 4009): nl80211: TDLS external setup
D/wpa_supplicant( 4009): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4009): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4009): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4009): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4009): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4009): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4009): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4009): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8a54718
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4009): htc_wext_command_init +
I/wpa_supplicant( 4009): htc_wext_command_init -
I/wpa_supplicant( 4009): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4009): Don't set 00 to countryID.conf
D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4009): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4009): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4009): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4009): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4009): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4009): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4009): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5735-5835 @ 80 MHz
,D/wpa_supplicant( 4009): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4009): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/SMSBackup( 4027): SMSBackupAgentService started
D/SMSBackup( 4027): Checking restore status
D/SMSBackup( 4027): Restore complete
D/SMSBackup( 4027): cancelCheckAlarm
D/SMSBackup( 4027): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  900): killProcessQuiet, pid=3731
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3731:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  900): Recipient 3731
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 4009): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4009):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4009):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4009):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4009): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4009): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4009): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4009): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4009): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4009): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4009): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4009): Using existing control interface directory.
,I/wpa_supplicant( 4009): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4009): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4009): Auto country group 1: ch36
I/wpa_supplicant( 4009): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4009): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 4009): Get randomness: len=20 entropy=0
V/RegulatoryObserver(  900): uevent:
V/RegulatoryObserver(  900): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
,V/RegulatoryObserver(  900): Regulatory Country Code:DE
D/wpa_supplicant( 4009): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4009): wpa_supplicant_scan enter
I/wpa_supplicant( 4009): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4009): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4009): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4009): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 4009): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_900-2
D/wpa_supplicant( 4009): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4009): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4009): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4009): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4009): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4009): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4009): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4009): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4009): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4009): nl80211: Event message available
D/wpa_supplicant( 4009): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4009): nl80211: Regulatory domain change
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4009): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4009): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4009): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4009): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4009): P2P: Add operating class 81
D/wpa_supplicant( 4009): P2P: Add operating class 115
D/wpa_supplicant( 4009): P2P: Add operating class 116
D/wpa_supplicant( 4009): P2P: Add operating class 117
D/wpa_supplicant( 4009): P2P: Update channel list
D/wpa_supplicant( 4009): p2p0: Updating hw mode
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 95
D/WifiNative-wlan0(  900): doBoolean: SET_WIFI_ON 1
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4009): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4009): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4009): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4009): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4009): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4009): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4009): set wifi ON
,D/WifiNative-wlan0(  900):    returned true,
D/WifiNative-wlan0(  900): doString: DRIVER MACADDR
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED,
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  900): Loading config and enabling all networks
D/WifiNative-wlan0(  900): doString: LIST_NETWORKS
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): list_network_info: ret=0x1, pos=0xb8a57117 buf=0xb8a570e8
I/wpa_supplicant( 4009): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4009): 0	NG700	any	
,D/WirelessDisplayService(  900): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
V/RegulatoryObserver(  900): Start wifi-crda service to run crda.
V/RegulatoryObserver(  900): Country Code is DE
V/RegulatoryObserver(  900): Send broadcast country code message.
I/RegulatoryObserver(  900): Broadcast intent for crda country code: DE
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiNative-wlan0(  900):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  900): 0	NG700	any	
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 ssid
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 bssid
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 priority
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/Wi,fiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 psk
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4009): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 proto
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  900): Failed to look-up a string: W
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  900): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 group
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  900): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  900): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  900): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  900): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  900): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  900): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 limited
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 eap
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'eap'
D/WIFI_ICON( 1103): updateWifiState: WIFI_STATE_CHANGED enabled
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 phase2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 identity
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 password
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
I/IntentController( 1103): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 engine
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 key_id
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  900): doString: GET_NETWORK 0 private_key
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4009): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  900): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  900): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4009): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4009): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SET manufacturer HTC
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4009): manufacturer='HTC'
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4009): model_name='HTC Desire 820'
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4009): model_number='HTC Desire 820'
D/WifiNative-wlan0(  900):    returned true
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SET config_methods physical_display virtual_push_button
D/HtcWiFiWidget_WiFiWidgetProvider( 4010): onWiFiStateChanged() for widget: 
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4009): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  900):    returned true
D/HtcWiFiWidget_WiFiWidgetProvider( 4010): updateWidget(context) for widget: 
D/WifiNative-wlan0(  900): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SET auto_interworking 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4009): auto_interworking=0
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: RECONNECT
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doString: STATUS
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  900): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): SET_SCREEN_ON:On
I/wpa_supplicant( 4009): htc_wext_set_keepalive +
I/wpa_supplicant( 4009): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4009): getPrivFuncNum +	
I/wpa_supplicant( 4009): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4009): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4009): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SET ps 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4009): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  900):    returned true
,W/Settings(  900): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  900): doBoolean: CTRL-DAT-AIR_MODE-0:1
D/WifiP2pService(  900): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): SETBAND: 0
D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4009): P2P: Add operating class 81
D/wpa_supplicant( 4009): P2P: Add operating class 115
D/wpa_supplicant( 4009): P2P: Add operating class 116
D/wpa_supplicant( 4009): P2P: Add operating class 117
D/wpa_supplicant( 4009): P2P: Update channel list
I/wpa_supplicant( 4009): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4009): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4009): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4009): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4009): p2p_oper_reg_class=126
D/wpa_supplicant( 4009): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4009): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 4009): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4009): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4009): p2p_oper_channel=36
E/wpa_supplicant( 4009): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4009): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4009): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4009): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4009): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: BSS_FLUSH 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doBoolean: SCAN
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  900):    returned false
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  900): doBoolean: SET pno 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4009): wpa_supplicant_scan enter
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): Wifi band: 0, ScanBroadCastCounter: 0
D/libc    (  900): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/WifiMonitor(  900): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  900): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4009): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4009): persistent_reconnect=1
I/wpa_supplicant( 4009): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doBoolean: SET device_name Android_63cc
W/WifiHW  (  900): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 4009): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 4009): device_name='Android_63cc'
I/wpa_supplicant( 4009): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  900): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 4009): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 4009): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4009): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 4009): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  900): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4009): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4009): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  900): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4009): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4009): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4009): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  900): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4009): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4009): Single channel concurrency preference: sta
I/wpa_supplicant( 4009): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doString: STATUS
W/WifiHW  (  900): QCOM Debug wifi_send_command "STATUS"
D/WifiP2pService(  900): P2pEnablingState
D/WifiP2pService(  900): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2p socket connection successful
D/WifiP2pService(  900): P2pEnabledState
D/WifiP2pService(  900): sending p2p connection changed broadcast
D/WifiDisplayController(  900): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  900): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  900): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  900): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiNative-p2p0(  900): doBoolean: P2P_FLUSH
W/WifiHW  (  900): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4009): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4009): P2P: Stopping find
D/wpa_supplicant( 4009): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4009): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4009): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  900): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4009): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4009): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doString: LIST_NETWORKS
W/WifiHW  (  900): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4009): list_network_info: ret=0x22, pos=0xb8a5710a buf=0xb8a570e8
I/wpa_supplicant( 4009): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4009): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  900):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  900): doBoolean: AP_SCAN 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  900):    returned false
D/WifiNative-p2p0(  900): doBoolean: SET wifi_display 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4009): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4009): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4009): WFD: Update WFD IE
I/wpa_supplicant( 4009): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4009): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  900):    returned true
D/WifiNative-p2p0(  900): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  900): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4009): WFD: Set subelement 0
D/wpa_supplicant( 4009): WFD: Update WFD IE
I/wpa_supplicant( 4009): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4009): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  900):    returned true
V/AudioService(  900): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  900):     Client/Owner: Client
V/AudioService(  900):     GroupId: 
V/AudioService(  900):     Passphrase: 
V/AudioService(  900):     SessionId: 0
V/AudioService(  900):     IP Address: }
D/HtcEffectManagerBase(  900): onEventChanged id=5 status=false
D/HtcEffectManager(  900): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  900): convertEffect before=902
D/WifiP2pService(  900): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  900): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  900):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  900):  primary type: 10-0050F204-5
D/WifiDisplayController(  900):  secondary type: null
D/WifiDisplayController(  900):  wps: 0
D/WifiDisplayController(  900):  grpcapab: 0
D/WifiDisplayController(  900):  devcapab: 0
D/WifiDisplayController(  900):  status: 3
D/WifiDisplayController(  900):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  900):  WFD CtrlPort: 0
D/WifiDisplayController(  900):  WFD MaxThroughput: 0
D/WifiP2pService(  900): sending p2p persistent groups changed broadcast
D/WifiP2pService(  900): InactiveState
D/WifiP2pService(  900): InactiveState{ when=-9ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  900):  WFD CtrlPort: 7236
D/WifiP2pService(  900):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): P2pEnabledState{ when=-9ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  900):  WFD CtrlPort: 7236
D/WifiP2pService(  900):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  900): Successfully set WFD info.
I/WifiDisplayController(  900): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  900): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  900):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  900):  primary type: 10-0050F204-5
D/WifiDisplayController(  900):  secondary type: null
D/WifiDisplayController(  900):  wps: 0
D/WifiDisplayController(  900):  grpcapab: 0
D/WifiDisplayController(  900):  devcapab: 0
D/WifiDisplayController(  900):  status: 3
D/WifiDisplayController(  900):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  900):  WFD CtrlPort: 7236
D/WifiDisplayController(  900):  WFD MaxThroughput: 50
D/WifiDisplayAdapter(  900): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  900):     Client/Owner: Client
D/WifiDisplayAdapter(  900):     GroupId: 
D/WifiDisplayAdapter(  900):     Passphrase: 
D/WifiDisplayAdapter(  900):     SessionId: 0
D/WifiDisplayAdapter(  900):     IP Address: }
D/HtcEffectManager(  900): convertEffect after=902
I/QuickSettingWifi( 1103): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
,D/wpa_supplicant( 4009): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4009): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4009): nl80211: if_removed already cleared - ignore event
D/Tethering(  900): interfaceLinkStateChanged p2p0, false
D/Tethering(  900): interfaceStatusChanged p2p0, false
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4009): nl80211: Event message available
D/wpa_supplicant( 4009): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4009): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4009): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 4009): nl80211: Survey data missing
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4009): Sorted scan results
I/wpa_supplicant( 4009): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 4009): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 4009): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 4009): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 4009): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-89
D/wpa_supplicant( 4009): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 4009): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4009): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4009): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4009): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4009): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 4009): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4009): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4009): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4009): wpa_supplicant_pick_network+
I/wpa_supplicant( 4009): Selecting BSS from priority group 1
I/wpa_supplicant( 4009): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4009): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4009): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4009): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4009): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4009):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4009):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 4009): Start print parameters
I/wpa_supplicant( 4009): wpa_s->wpa_state is 3
I/wpa_supplicant( 4009): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4009): isConcurrentMode() is 0
I/wpa_supplicant( 4009): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4009): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4009): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4009): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4009): wpa_s->reassociate is 0
I/wpa_supplicant( 4009): wpa_s->is_screen_on 1
I/wpa_supplicant( 4009): wpa_s->ifname wlan0
I/wpa_supplicant( 4009): End print parameters
I/wpa_supplicant( 4009): selected network = 2
D/wpa_supplicant( 4009): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8a554e8  current_ssid=0x0
D/wpa_supplicant( 4009): w,lan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4009): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4009): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4009): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4009): check if in concurrent case
,I/wpa_supplicant( 4009): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4009): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4009): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4009): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4009): RSN: PMKSA cache search - network_ctx=0xb8a554e8 try_opportunistic=0
D/wpa_supplicant( 4009): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4009): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4009): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4009): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4009): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4009): nl80211: Unsubscribe mgmt frames handle 0xb8a54718 (mode change)
D/wpa_supplicant( 4009): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8a54718
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Register frame type=0xd0 nl_handle=0xb8a54718
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4009): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4009):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4009):   * freq=2412
D/wpa_supplicant( 4009):   * Auth Type 0
D/wpa_supplicant( 4009):   * WPA Versions 0x2
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 46,
D/wpa_supplicant( 4009): nl80211: Connect request send successfully
D/wpa_supplicant( 4009): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  900): doString: LIST_DONGLES
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  900): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4009): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4009): reply (636) for get BSS: id=0
I/wpa_supplicant( 4009): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4009): freq=5220
I/wpa_supplicant( 4009): level=-48
I/wpa_supplicant( 4009): tsf=0000000104411237
I/wpa_supplicant( 4009): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4009): ssid=NG7005g
I/wpa_supplicant( 4009): ====
I/wpa_supplicant( 4009): id=1
I/wpa_supplicant( 4009): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4009): freq=2412
I/wpa_supplicant( 4009): level=-47
I/wpa_supplicant( 4009): tsf=0000000104411247
I/wpa_supplicant( 4009): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4009): ssid=01ABC
I/wpa_supplicant( 4009): ====
I/wpa_supplicant( 4009): id=2
I/wpa_supplicant( 4009): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4009): freq=2412
I/wpa_supplicant( 4009): level=-47
I/wpa_supplicant( 4009): tsf=0000000104411250
I/wpa_supplicant( 4009): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4009): ssid=NG700
I/wpa_supplicant( 4009): ====
I/wpa_supplicant( 4009): id=3
I/wpa_supplicant( 4009): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4009): freq=2427
I/wpa_supplicant( 4009): level=-76
I/wpa_supplicant( 4009): tsf=0000000104411257
I/wpa_supplicant( 4009): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4009): ssid=Gonzos
I/wpa_supplicant( 4009): ====
I/wpa_supplicant( 4009): id=4
I/wpa_supplicant( 4009): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 4009): freq=2437
I/wpa_supplicant( 4009): level=-89
I/wpa_supplicant( 4009): tsf=0000000104411260
I/wpa_supplicant( 4009): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4009): ssid=UPC4688432
I/wpa_supplicant( 4009): ####
,D/WirelessDisplayService(  900): getDiscoveryDongleList
D/WifiStateMachine(  900): == begin of scan result ==
,D/WifiStateMachine(  900): == (5) end of scan result ==
,D/WirelessDisplayService(  900): getDiscoveryDongleList
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  900): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 104411237, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -47, frequency: 2412, timestamp: 104411247, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 104411250, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 104411257, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  900): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 104411260, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/WifiStateMachine(  900): add 5 to mScanResults
D/WifiNotificationController(  900): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/wpa_supplicant( 4009): EAPOL: disable timer tick
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
,I/bt-btu  ( 3917): btu_task received preload complete event
,D/bt-btm  ( 3917): btm_acl_device_down
D/bt-btm  ( 3917): btm_acl_reset_paging
,D/bt-btm  ( 3917): btm_acl_set_discing
,I/bt-btm  ( 3917): btm_reset_complete
,I/bt-btm  ( 3917): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3917): Start reading local supported commands
,D/bt-btm  ( 3917): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3917): BTM reads next extended features page (1)
D/bt-btm  ( 3917): BTM reads next extended features page (2)
D/bt-btm  ( 3917): BTM reached last extended features page (2)
,D/bt-btm  ( 3917): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3917): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3917): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3917): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3917): btm_read_ble_wl_size 
D/bt-btm  ( 3917): btm_read_white_list_size_complete 
,D/bt-btm  ( 3917): btm_get_ble_buffer_size 
,D/bt-btm  ( 3917): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3917): btm_read_ble_local_supported_features 
D/bt-btm  ( 3917): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3917): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3917): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3917): Local supported ACL packet types: 0xcc18
,D/bt-btm  ( 3917): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3917): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3917): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3917):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3917): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3917): BTM_SetInquiryMode
,I/bt-btm  ( 3917): BTM_SetPageScanType
I/bt-btm  ( 3917): BTM_SetInquiryScanType
D/bt-btm  ( 3917): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3917): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3917): BTM_BleLoadLocalKeys
D/bt-btm  ( 3917): BTM_BleLoadLocalKeys
I/bt-btm  ( 3917): BTM_Sec: application registered
E/bt-btm  ( 3917): BTM_SecRegister:p_cb_info->p_le_callback == 0x62003941 
,I/bt-btm  ( 3917): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3917): SMP_Register state=0
E/bt-btm  ( 3917): BTM_SecRegister: btm_cb.api.p_le_callback = 0x62003941 
I/bt-btm  ( 3917): BTM_Sec: application registered
,D/bt-btm  ( 3917): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3917): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3917): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3917): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3917): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3917): BTM_RegBusyLevelNotif
I/bt-att  ( 3917): GATT_Register
,D/bt-att  ( 3917): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3917): allocated gatt_if=3
I/bt-att  ( 3917): GATT_StartIf gatt_if=3
D/bt-att  ( 3917): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3917): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btm  ( 3917): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
E/bt-btif ( 3917): Calling BTA_HhEnable
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3917): BTM_AllocateSCN
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3917): BTM_AllocateSCN
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btm  ( 3917): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3917):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3917):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3917):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3917):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3917):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3917):                : sec: 0x3092, service name [] (up to 21 chars saved)
E/bt-btif ( 3917): btif_storage_]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3917): btif_storage_]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3917): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 3917): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3917): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3917):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3917):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3917):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3917):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3917):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3917): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3917): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
D/bt-avp  ( 3917): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3917): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:2 len:6
I/bt-btm  ( 3917): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3917):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3917):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3917):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3917):               , : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3917):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3917):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3917): BTM_GetHCIConnHandle
I/bt-btm  ( 3917): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3917): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3917): BTM_GetHCIConnHandle
I/bt-btm  ( 3917): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3917): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3917): BTM_GetHCIConnHandle
I/bt-btm  ( 3917): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3917): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3917): BTM_GetHCIConnHandle
I/bt-btm  ( 3917): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3917): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3917): BTM_GetHCIConnHandle
I/bt-btm  ( 3917): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3917): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3917): GATT_Register
D/bt-att  ( 3917): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3917): allocated gatt_if=4
I/bt-att  ( 3917): GATT_StartIf gatt_if=4
D/bt-att  ( 3917): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3917): gatt_find_the_connected_bda found=0 found_idx=7
D/BluetoothAdapterProperties( 3917): Address is:80:01:84:8A:B3:68
I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:1 len:14
,I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3917): Scan Mode:20
I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3917): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:8 len:30
,D/BluetoothAdapter( 3917): getBluetoothService(): entry
D/BluetoothAdapter( 3917): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3917): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b9a770
,D/BluetoothDevice( 3917): getService : Register callback
,D/BluetoothAdapterProperties( 3917): Adding bonded device:B4:CE:F6:AB:A4:6A
,D/BluetoothAdapterProperties( 3917): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 3917): Adding bonded device:34:FC:EF:9D:93:0B
,D/BluetoothAdapterProperties( 3917): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3917): Adding bonded device:58:2A:F7:ED:96:BE
,I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3917): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3917): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3917): Remote class is:5898764
,I/bt-btif ( 3917): HAL bt_hal_cbacks->remote_device_properties_cb
D/wpa_supplicant( 4009): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4009): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4009): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4009): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4009): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4009): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4009): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4009): nl80211: Event message available
D/wpa_supplicant( 4009): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4009): nl80211: Connect event
E/BluetoothRemoteDevices( 3917): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/wpa_supplicant( 4009): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4009): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4009): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4009): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4009): Add randomness: count=7 entropy=5
I/wpa_supplicant( 4009): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4009): TDLS: Remove peers on association
D/wpa_supplicant( 4009): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4009): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4009): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4009): htc_wext_set_keepalive +
I/wpa_supplicant( 4009): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4009): getPrivFuncNum +	
I/wpa_supplicant( 4009): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4009): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 4009): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4009): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 4009): Get randomness: len=32 entropy=6
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/BluetoothRemoteDevices( 3917): Remote class is:5898764
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  900): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  900): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  900): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  900): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
D/WifiMonitor(  900): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
,D/WifiMonitor(  900): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  900): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  900): Enter handleAssociatedWithEvent
D/WifiStateMachine(  900): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  900): Associated
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  900): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  900): Exit handleAssociatedWithEvent
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  900): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,I/bt-btif ( 3917): HAL bt_hal_cbacks->remote_device_properties_cb
,D/Tethering(  900): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 4009): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8a549f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4009):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4009): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4009): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f17b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4009):    broadcast key
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4009): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4009): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4009): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4009): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4009): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/Tethering(  900): interfaceStatusChanged wlan0, true
E/BluetoothRemoteDevices( 3917): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
E/wpa_supplicant( 4009): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4009): set send_ind_to_ndc = 0
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4009): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4009): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4009): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4009): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4009): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4009): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4009): EAPOL authentication completed successfully
I/wpa_supplicant( 4009): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 79
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 4009): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4009): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4009): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  900): interfaceLinkStateChanged wlan0, true
D/Tethering(  900): interfaceStatusChanged wlan0, true
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/BluetoothRemoteDevices( 3917): Remote class is:5898764
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,I/bt-btif ( 3917): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,E/BluetoothRemoteDevices( 3917): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 3917): Remote class is:5898764
,D/WifiStateMachine(  900): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/bt-btif ( 3917): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3917): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
D/WifiApDatabaseHandler(  900): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  900): This record is existed, only update it...
D/BluetoothRemoteDevices( 3917): Remote class is:5898764
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
,I/bt-btif ( 3917): BTA_JvEnable
I/bt-btm  ( 3917): BTM_ReadConnectability
I/bt-btm  ( 3917): BTM_ReadDiscoverability
I/bt-btm  ( 3917): BTM_SetDiscoverability
I/bt-btm  ( 3917): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3917): br_edr_supported=0x2
I/bt-btm  ( 3917): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3917): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3917): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3917): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3917): BTM_SetConnectability
I/bt-btm  ( 3917): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3917): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3917): BTM_SetDiscoverability
I/bt-btm  ( 3917): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3917): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3917): br_edr_supported=0x0
I/bt-btm  ( 3917): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3917): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3917): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3917): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3917): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3917): BTM_SetConnectability
I/bt-btm  ( 3917): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3917): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3917): bta_pan_co_init
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3917): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3917):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3917):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3917): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3917):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3917): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3917):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
E/bt_mct  ( 3917): hci lib postload completed
,D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btif ( 3917): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3917): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3917): ScanMode =  20
,D/BluetoothAdapterProperties( 3917): State =  11
I/bt-btm  ( 3917): BTM_SetDiscoverability
I/bt-btm  ( 3917): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3917): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3917): br_edr_supported=0x0
I/bt-btm  ( 3917): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3917): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3917): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3917): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3917): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3917): BTM_SetConnectability
I/bt-btm  ( 3917): btm_ble_set_connectability mode=0x0 combined_mode=0x1
,I/bt-btm  ( 3917): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3917): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3917): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3917): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3917): Setting state to 12
I/BluetoothAdapterState( 3917): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3917): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btif ( 3917): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService(  900): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  900): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  900): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  900): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan(  900): onBluetoothStateChange(on) call bindService
,I/BluetoothAdapterState( 3917): Entering On State
D/BluetoothAdapterProperties( 3917): Scan Mode:21
I/bt-btif ( 3917): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 3917): Discoverable Timeout:120
,D/BluetoothHeadset( 1103): onBluetoothStateChange: up=true
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothPan(  900): BluetoothPAN Proxy object connected
D/BluetoothAdapterService(1102397568)( 3917): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3917): getBondedDevices: length=5
D/BluetoothHeadset( 1103): Proxy object connected
D/BluetoothHeadset( 1214): onBluetoothStateChange: up=true
I/QuickSettingMiniLite( 1103): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e4dde0
D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  900): updateConnectedAP...
D/BluetoothHeadset( 1214): Proxy object connected
D/BluetoothHeadset( 1214): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1102397568)( 3917): Get Bonded Devices being called
D/BluetoothHeadset( 1214): Proxy object connected
D/BluetoothPhoneService( 1214): BluetoothHeadset onServiceConnected
D/BluetoothAdapterProperties( 3917): getBondedDevices: length=5
D/BluetoothAdapter( 1214): 1103713136: getState(). Returning 12
,D/BluetoothHeadset(  900): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  900): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  900): Proxy object connected
D/BluetoothManagerService(  900): Bluetooth State Change Intent: 11 -> 12
,D/WifiStateMachine(  900): fetchFrequency(), freq = 2412
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
I/IntentController( 1103): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  900): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/BluetoothAdapter(  900): 1111882664: getState(). Returning 12
D/WifiApDatabaseHandler(  900): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  900): This record is existed, only update it...
D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  900): updateConnectedAP...
D/PMS     (  900): acquireWL(431187c8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3327 1000 null
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/BluetoothPbapReceiver( 3917): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3917): ***********state = 12
,D/BluetoothMasReceiver( 3917): Bluetooth STATE CHANGED to 12
,D/BluetoothA2dp(  900): Proxy object connected
,D/BluetoothAdapter(  900): 1111882664: getState(). Returning 12
,D/HtcBtWidget_BTWidgetProvider( 3942): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3942): updateWidget(context) for widget: 
D/PMS     (  900): releaseWL(431187c8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
,D/PMS     (  900): acquireWL(43fa6660): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3327 1000 null
W/System.err(  900): java.lang.Throwable: stack dump
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
V/BluetoothSapReceiver( 3917): SapReceiver onReceive 
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
V/BluetoothSapReceiver( 3917): action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43fa68e8:true
V/BluetoothSapReceiver( 3917):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3917): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/BluetoothManagerService(  900): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  900): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
I/LocationAgent( 3327): new LocationAgent instance!!
,D/BluetoothManagerService(  900): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/HtcTagManager( 3327): HtcTagManager construction complete
,D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 12
D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 12
,D/WifiStateMachine(  900): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/BluetoothMasService( 3917): parseIntent 1: mIsEmailEnabled: true
D/WifiApDatabaseHandler(  900): updateConnectedAP...
,V/EmailUtils( 3917): Manager Instance is not NULL
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  900): Provision feature enable=false
,D/ConnectivityService(  900): mActiveDefaultNetwork: -1
D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
D/BluetoothInputDevice( 3327): BluetoothInputDevice()
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/EmailUtils( 3917): ============NULL aList========
V/EmailUtils( 3917): <-getEmailAccountIdList
D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
D/BluetoothInputDevice( 3327): BluetoothInputDevice(): Binding service...
,D/BluetoothManagerService(  900): Registered receivers: 7
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 3327): BluetoothPan()
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 8
V/BluetoothPbapService( 3917): Handler(): got msg=1
D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
D/BluetoothPan( 3327): BluetoothPan(): Binding service...
D/DhcpStateMachine(  900): [StoppedState] Start DHCP
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,V/BluetoothPbapService( 3917): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3917): Pbap Service initSocket
V/BluetoothSapService( 3917): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3917): state: 12
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [2][0][0]
D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 12
W/ContextImpl( 3917): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/BluetoothMap( 3327): Create BluetoothMap proxy object
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/BluetoothManagerService(  900): registerStateChangeCallback+
,V/BluetoothSapService( 3917): Starting SAP server process
D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
D/BluetoothAdapter( 1103): 1105110128: getState(). Returning 12
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 9
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4009): WiFioffload: SignalStrength: =97
E/BluetoothMap( 3327): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,V/BluetoothMasService( 3917): handleMessage: mIsEmailEnabledtrue
,V/BtMns   ( 3917): BluetoothMns: isEmailEnabled: true
D/BluetoothAdapter( 1103): 1105110128: getState(). Returning 12
D/BluetoothAdapter( 3917): getBluetoothService(): entry
W/BluetoothAdapter( 3917): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiNative-wlan0(  900):    returned true
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothSap( 3327): BluetoothSap() call bindService
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  900): Registered receivers: 10
D/WifiStateMachine(  900): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  900): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4009): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  900):    returned true
,I/QuickSettingBluetooth( 1103): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
E/BluetoothServiceJni( 3917): SOCK FLAG = 1 ***********************
D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 1
I/QuickSettingWifi( 1103): receive.wifiConnect:false wifiAPname:null elapse:0
I/bt-btif ( 3917): BTA_JvCreateRecordByUser
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
,D/PhoneStatusBar( 1103): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
I/bt-btif ( 3917): BTA_JvRfcommStartServer
I/bt-btm  ( 3917): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3917):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3917): Succeed to create listening socket 
V/BluetoothPbapService( 3917): Accepting socket connection...
,D/BluetoothMasService( 3917): Map_prev 1
D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): Power_Mode_Type mode = 1
I/wpa_supplicant( 4009): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 61
D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  900):    returned null
E/WifiStateMachine(  900): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  900):    returned null
,D/BluetoothPbap( 3327): BluetoothPbap()
D/WifiStateMachine(  900): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  900): acquireWL(43431f50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 900 1000 null
D/WifiStateMachine(  900): handlePreDhcpSetup mBluetoothConnectionActive: false
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/WifiP2pService(  900): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42f941a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  900): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42f941a0 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 11
D/BluetoothAdapter( 3917): getBluetoothService(): entry
W/BluetoothAdapter( 3917): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
D/BluetoothPbap( 3327): BluetoothPbap(): Binding service...
E/BluetoothServiceJni( 3917): SOCK FLAG = 3 ***********************
I/bt-btif ( 3917): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btif ( 3917): BTA_JvRfcommStartServer
I/bt-btm  ( 3917): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3917):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3917): getBluetoothService(): entry
,W/BluetoothAdapter( 3917): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothA2dp( 3327): BluetoothA2dp()
E/BluetoothServiceJni( 3917): SOCK FLAG = 3 ***********************
D/BluetoothManagerService(  900): registerStateChangeCallback+
,D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 12
I/bt-btif ( 3917): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
,I/bt-btif ( 3917): BTA_JvRfcommStartServer
I/bt-btm  ( 3917): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3917):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
,D/BluetoothA2dp( 3327): BluetoothA2dp(): Binding service...
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/BluetoothHeadset( 3327): BluetoothHeadset()
,D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 13
D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
D/BluetoothHeadset( 3327): BluetoothHeadset(): Binding service...
D/BluetoothAdapter( 1103): 1105110128: getState(). Returning 12
I/QuickSettingMiniLite( 1103): updateLiteState:no connect device!
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/WIFI_ICON( 1103): updateWifiState: RSSI_CHANGED -1 -> 3
,D/HtcTagManager( 3327): startProxy
,W/ContextImpl( 3327): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3327): LocalBluetoothProfileManager construction complete
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
,D/DockEventReceiver( 3327): finishStartingService: stopping service
,D/BluetoothSapService( 3917): Sap_prev 1
,V/BluetoothSapService( 3917): SAP Service startRfcommListenerThread
D/BluetoothPan( 3327): BluetoothPAN Proxy object connected
D/WISPrService( 3327): >>>>>WISPrService start isConnected = false<<<<<
,D/PanProfile( 3327): Bluetooth service connected
D/BluetoothA2dp( 3327): Proxy object connected
,D/A2dpProfile( 3327): Bluetooth service connected
V/TAG     ( 3917): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 3917): Sap Service initRfcommSocket
,D/WifiStateMachine(  900): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothSapService( 3917): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b90bb8
,D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
,D/WISPrService( 3327): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -47, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/BluetoothAdapter( 3917): getBluetoothService(): entry
V/BluetoothPbapService( 3917): Pbap Service onBind
,W/BluetoothAdapter( 3917): getBluetoothService() called with no BluetoothManagerCallback
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3980): onCreate: going to find gatt base service first.
D/BluetoothHeadset( 3327): Proxy object connected
E/BluetoothServiceJni( 3917): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3917): BTA_JvCreateRecordByUser
D/HeadsetProfile( 3327): Bluetooth service connected
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btif ( 3917): BTA_JvRfcommStartServer
I/bt-btm  ( 3917): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3917):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3917): Succeed to create listening socket 
,V/BluetoothSapService( 3917): Accepting socket connection...
,D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
,D/BluetoothInputDevice( 3327): Proxy object connected
,D/WifiService(  900): New client listening to asynchronous messages
D/HidProfile( 3327): Bluetooth service connected
D/BluetoothAdapter( 3327): 1103978880: getState(). Returning 12
D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/BluetoothFtpService( 3917): Ftp Service onCreate
D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 12
W/System.err(  900): java.lang.Throwable: stack dump
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4256efd0:true
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothMasReceiver( 3917): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3917): getBluetoothService(): entry
,W/BluetoothAdapter( 3917): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3917): SOCK FLAG = 0 ***********************
I/bt-btif ( 3917): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:15
,I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btif ( 3917): BTA_JvRfcommStartServer
I/bt-btm  ( 3917): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3917):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothFtpService( 3917): Ftp_prev 1
,I/BtOppRfcommListener( 3917): Accept thread started.
,D/PMS     (  900): releaseWL(43fa6660): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/[HTC_BLE][Constants]( 3980):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3980):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3980):  + discoverServicesOnBonded = false
D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3917): getBluetoothService(): entry
W/BluetoothAdapter( 3917): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3917): SOCK FLAG = 1 ***********************
I/bt-btif ( 3917): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3917): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btif ( 3917): BTA_JvRfcommStartServer
I/bt-btm  ( 3917): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3917):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3917): Run Accept thread
D/SapServerProfile( 3327): Bluetooth service connected
D/BluetoothPbap( 3327): Proxy object connected
D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 12
V/BluetoothMasService( 3917): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3917): Manager Instance is not NULL
D/PbapServerProfile( 3327): Bluetooth service connected
,D/EmailUtils( 3917): ============NULL aList========
,V/EmailUtils( 3917): <-getEmailAccountIdList
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3980):  + Google LE service found. Using BaseLeProfilesGoogle.
,D/BluetoothMasService( 3917): Map_prev 1
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b59fd0
D/[HTC_BLE][Constants]( 3980): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3980): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3980): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3980): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3980): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 3980): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3980): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3327): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3980): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3980): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b59fd0
D/HtcTagProfile( 3327): setup proxy
D/HtcPxpProfile( 3327): setup proxy
D/HtcFmpProfile( 3327): setup proxy
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3980): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b59fd0
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3980): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b59fd0, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b64fb8
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3980): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b59fd0
,D/wpa_supplicant( 4009): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4009): EAPOL: disable timer tick
,W/System.err(  900): java.lang.Throwable: stack dump
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@444965f8:true
,I/LocationAgent( 3745): new LocationAgent instance!!
,D/HtcTagManager( 3745): HtcTagManager construction complete
,D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/RingtoneManager( 3980): getExternalStorageState=mounted
,D/BluetoothInputDevice( 3745): BluetoothInputDevice()
D/BluetoothManagerService(  900): registerStateChangeCallback+
,D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 14
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/BluetoothInputDevice( 3745): BluetoothInputDevice(): Binding service...
,D/BluetoothPan( 3745): BluetoothPan()
,D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  900): Registered receivers: 15
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/BluetoothPan( 3745): BluetoothPan(): Binding service...
W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[-1]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[2]: Feverfew
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[5]: Hangouts Message
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[7]: Licorice
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[9]: Rose
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[12]: Tulip
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3980):  + mAlertUri: content://settings/system/alarm_alert
,D/BluetoothMap( 3745): Create BluetoothMap proxy object
,D/BluetoothManagerService(  900): registerStateChangeCallback+
,D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  900): Registered receivers: 16
,W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
E/BluetoothMap( 3745): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3980): BleProfilesStateMachine is initialized...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3980): Enter IdleState
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3980): initLeServices_platform
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): initScanModeInterface: true
D/BluetoothSap( 3745): BluetoothSap() call bindService
W/System.err(  900): java.lang.Throwable: stack dump
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  900): Registered receivers: 17
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3980): loadDeviceConfiguration() init =true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3980):  + mTag.getPrimaryDeviceList() = []
,D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@439f3e20:true
,D/[HTC_BLE][Constants]( 3980):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3980):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 3980):  + discoverServicesOnBonded = false
,D/BluetoothPbap( 3745): BluetoothPbap()
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  900): Registered receivers: 18
,W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/BluetoothPbap( 3745): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 3745): BluetoothA2dp()
D/BluetoothManagerService(  900): registerStateChangeCallback+
,D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  900): Registered receivers: 19
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/BluetoothA2dp( 3745): BluetoothA2dp(): Binding service...
W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3980): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b64fb8
D/BluetoothHeadset( 3745): BluetoothHeadset()
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 20
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/BluetoothHeadset( 3745): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3745): startProxy
,W/ContextImpl( 3745): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3745): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
D/LocalBluetoothProfileManager( 3745): setBluetoothStateOn
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
D/HtcTagManager( 3745): startProxy
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
D/BluetoothAdapterService(1102397568)( 3917): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3917): getBondedDevices: length=5
D/BluetoothAdapter( 3745): getBluetoothService(): entry
D/BluetoothAdapter( 3745): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3745): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b9b5f8
D/BluetoothDevice( 3745): getService : Register callback
E/BluetoothDevice( 3745): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
D/HtcTagManager( 3745): addHtcTagProfiles
,E/BluetoothDevice( 3745): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/HtcTagManager( 3745): addHtcTagProfiles
,E/BluetoothDevice( 3745): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/HtcTagManager( 3745): addHtcTagProfiles
,E/BluetoothDevice( 3745): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/HtcTagManager( 3745): addHtcTagProfiles
,E/BluetoothDevice( 3745): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/HtcTagManager( 3745): addHtcTagProfiles
,D/BluetoothInputDevice( 3745): Proxy object connected
,D/HidProfile( 3745): Bluetooth service connected
,D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/BluetoothPan( 3745): BluetoothPAN Proxy object connected
D/PanProfile( 3745): Bluetooth service connected
D/SapServerProfile( 3745): Bluetooth service connected
D/BluetoothPbap( 3745): Proxy object connected
D/PbapServerProfile( 3745): Bluetooth service connected
D/BluetoothA2dp( 3745): Proxy object connected
,D/A2dpProfile( 3745): Bluetooth service connected
,D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/BluetoothHeadset( 3745): Proxy object connected
D/HeadsetProfile( 3745): Bluetooth service connected
,D/BluetoothAdapter( 3745): 1102454528: getState(). Returning 12
,D/HtcTagManager( 3745): onServiceConnected
D/HtcTagProfile( 3745): setup proxy
D/HtcPxpProfile( 3745): setup proxy
,D/HtcFmpProfile( 3745): setup proxy
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4009): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiP2pService(  900): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  900): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  900): releaseWL(43431f50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  900):    returned true
,D/WifiStateMachine(  900): gateway: /192.168.1.1
D/WifiNative-wlan0(  900): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4009): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  900):    returned true
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  900): VerifyingLinkState enter
D/WifiStateMachine(  900): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  900): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  900): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -46, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1103): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  900): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WifiDataStallTracker(  900): startDataStallAlarm: tag=19830 delay=15s
,D/WifiWatchdogStateMachine(  900): WAN detection
,D/WISPrService( 3327): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  900): Provision feature enable=false
D/ConnectivityService(  900): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false,
V/ConnectivityService(  900): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  900): default: teardown()
D/MDST    (  900): default: setTeardownRequested(true)
D/MDST    (  900): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
D/MDST    (  900): default: setTeardownRequested(true),
D/ConnectivityService(  900): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS,
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
E/ConnectivityService(  900): Unexpected mtu value: android.net.wifi.WifiStateTracker@424657a8
D/ConnectivityService(  900): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  900): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  900): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  900): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  900): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  900): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  900): handleConnectivityChange: resetting
D/Nat464Xlat(  900): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  900): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  900): sendGeneralBroadcastDelayed, restrictEnable=false
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  900): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  900):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1103): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/PMS     (  900): acquireWL(426271b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
D/ConnectivityService(  900): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  900): releaseWL(426271b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  900): mActiveDefaultNetwork: WIFI
,V/Tethering(  900): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  900): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  900): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4110 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,V/Tethering(  900): bSetPropertyMultiRAB:false
,D/Tethering(  900): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/GpsLocationProvider(  900): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  900): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1242): [onReceive] WIFI(1): CONNECTED
,I/Tethering(  900): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  900): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  900): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  900): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,D/CaptivePortalTracker(  900): NoActiveNetworkState
I/Tethering(  900): Found interface wlan0
,D/Tethering(  900): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
D/libc    (  900): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/libc    (  900): [NET] getaddrinfo-,err=8
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/libc    (  900): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
D/PMS     (  900): acquireWL(4238b1e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1402/10028)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.htc.launcher (1242/10075)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1754/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.docs (3793/10100)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.musicenhancer (3414/10051)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =88d3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.docs (3793/10100)
,D/GpsLocationProvider(  900): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  900): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/PMS     (  900): acquireWL(4243c2e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=33 [3][1][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  900): acquireWL(41ec5dd8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 900 1000 WorkSource{10096}
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
I/ActivityManager(  900): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4128 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  900): releaseWL(41ec5dd8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 67
D/libc    (  364): [NET]res_nsend:resplen=104
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo_proxy-, success
,I/MusicStore( 4110): Database version: 95
,D/PMS     (  900): acquireWL(43fe20c8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 900 1000 WorkSource{10096}
,W/ContextImpl( 4110): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  900): acquireWL(42632ef8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 900 1000 WorkSource{10160}
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
D/GpsLocationProvider(  900): [handleMessage] INJECT_NTP_TIME
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [1][0][0]
D/GpsLocationProvider(  900): NTP server returned: 1449746252242 (Thu Dec 10 12:17:32 CET 2015) reference: 107687 certainty: 12 system time offset: -1
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  900): BroadcastRSSIForIMS, newrssi =-47 , oldRssi= -200
,D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4009): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  900): releaseWL(4243c2e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(42b54eb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
D/WIFI_ICON( 1103): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
D/GpsLocationProvider(  900): [handleMessage] INJECT_NTP_TIME_FINISHED
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,I/IntentController( 1103): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1523): [EventService] EVENT_RESET_THEME_TIMESTAMP
D/PMS     (  900): releaseWL(42b54eb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  900): releaseWL(4238b1e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(4428be60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/PMS     (  900): releaseWL(4428be60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/FeedActionBar( 1242): updateLastUpdatedTime(in String) LAST UPDATED 12:16
W/ContextImpl( 4110): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/DotMatrix( 1523): [EventService] isTheSameDay:false,timestamp is early than today:true
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4110): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(43fca238): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/PMS     (  900): releaseWL(42632ef8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/PMS     (  900): releaseWL(43fca238): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/PMS     (  900): acquireWL(43fc9f50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/DelayedSyncController( 4128): Delaying sync.
D/PMS     (  900): releaseWL(43fc9f50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(42500b20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  900): releaseWL(43fe20c8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4110): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4110): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4110, uid=10154, userID:0
D/PMS     (  900): acquireWL(42dd4d50): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 900 1000 WorkSource{10096}
D/PMS     (  900): releaseWL(42500b20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(43bd73a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/DelayedSyncController( 4128): Delaying sync.
D/PMS     (  900): releaseWL(43bd73a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/PMS     (  900): acquireWL(425b70a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/PMS     (  900): releaseWL(42dd4d50): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  900): releaseWL(425b70a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiDisplayAdapter(  900): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  900):     Client/Owner: Client
D/WifiDisplayAdapter(  900):     GroupId: 
D/WifiDisplayAdapter(  900):     Passphrase: 
D/WifiDisplayAdapter(  900):     SessionId: 0
D/WifiDisplayAdapter(  900):     IP Address: }
,D/MediaRouterService(  900): Client com.google.android.music (pid 4110): Registered
,I/MediaRouter( 4110): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  900): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  900):     Client/Owner: Client
D/WifiDisplayAdapter(  900):     GroupId: 
D/WifiDisplayAdapter(  900):     Passphrase: 
D/WifiDisplayAdapter(  900):     SessionId: 0
D/WifiDisplayAdapter(  900):     IP Address: }
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.music (4110/10154)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
,I/NetworkMonitor( 4110): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  900): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4156 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 4110): getSelectedRoute
,I/NetworkMonitor( 4110): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.google.android.music (4110/10154)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,D/Process (  900): killProcessQuiet, pid=3763
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4110, uid=10154, userID:0
I/ActivityManager(  900): Killing 3763:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 3763
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 4156): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4156): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4156): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4156): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4156): Preparing secondary program dexes.
,V/DexLibLoader( 4156): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4156): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4156): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4156): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4156): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4156): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4156): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4156): Dex already copied
D/OdexVerifier( 4156): Odex verification is skipped.
,V/DexLibLoader( 4156): Creating class loader,
,V/DexLibLoader( 4156): Finished creating class loader,
V/DexLibLoader( 4156): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4156): Dex already copied
D/OdexVerifier( 4156): Odex verification is skipped.
,V/DexLibLoader( 4156): Creating class loader,
,V/DexLibLoader( 4156): Finished creating class loader,
V/DexLibLoader( 4156): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4156): Dex already copied
D/OdexVerifier( 4156): Odex verification is skipped.,
,V/DexLibLoader( 4156): Creating class loader,
,V/DexLibLoader( 4156): Finished creating class loader,
V/DexLibLoader( 4156): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4156): Dex already copied
D/OdexVerifier( 4156): Odex verification is skipped.
,V/DexLibLoader( 4156): Creating class loader,
,V/DexLibLoader( 4156): Finished creating class loader
,V/DexLibLoader( 4156): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4156): DexLibLoader.ensureDexLoaded took 92 ms
,D/WIFI_ICON( 1103): WifiActivity: 3
,D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/BTIF_CORE( 3917): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3917): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3917): Wake lock released
,I/SensorManager(  900): mEventCount = 1350
,W/dalvikvm( 4156): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4156): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4156): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4156): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4156): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4156): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4156): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4156): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4156): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4156): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4156): Verify
,D/libc    (  900): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-,err=8
D/libc    (  900): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =52d0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/WifiService(  900): New client listening to asynchronous messages
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
,D/WifiStateMachine(  900): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  900): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,W/fb4a(:<default>):BaseAnalyticsConfig( 4156): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4156): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  900): Find DNS Address www.htc.com/23.59.123.86
,I/dalvikvm-heap( 4156): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  900): Disable JIT of com.htc.bgp
,I/ActivityManager(  900): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4176 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  900): killProcessQuiet, pid=1359
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  900): Killing 1359:com.htc.sense.hsp/u0a53 (adj 15): empty #17
,I/CalendarProvider2( 4176): Created com.android.providers.calendar.CalendarAlarmManager@41b76ac0(com.android.providers.calendar.HtcCalendarProvider@41b5ee48)
,D/CalendarProvider2( 4176): wait start:true
,D/CalendarProvider2( 4176): wait end:false
D/PMS     (  900): acquireWL(425ff410): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1193 10028 null
,I/ActivityManager(  900): Recipient 1359
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  900): acquireWL(42cf48f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1193 10028 null
,W/fb4a(:<default>):UserScope( 4156): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  900): releaseWL(425ff410): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4156): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,W/fb4a(:<default>):UserScope( 4156): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  900): releaseWL(42cf48f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1335): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
,W/ContextImpl( 4156): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/PMS     (  900): acquireWL(432d3738): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1335 10028 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1335): [NET] getaddrinfo-, 1
,D/libc    ( 1335): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4645 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/SensorManager(  900): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42203e30
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  900): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 2
W/SensorService(  900): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  900): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42203e30, eanble = 0, strlen(mName) = 59
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  900): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42384450
W/SensorService(  900): Listener[1] = com.htc.smartdim.sensor_eye@426104e8
,W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  900): Going to sleep due to screen timeout...
W/BatSI   (  900): Couldn't get kernel wake lock stats
V/LightsService(  900): setLight #2: color=#0
D/qdlights(  900): set_light_buttons_func: on=0 brightness=0
V/LightsService(  900): setLight #0: color=#0
,I/ActivityManager(  900): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4203 uid=10053 gids={50053, 1023, 3003, 5012}
,I/ActivityManager(  900): mThumbnailWidth=360, mThumbnailHeight=640
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 249
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1335): [NET] getaddrinfo_proxy-, success
,W/PMS     (  900): mWirelessDisplayManager is null
D/WirelessDisplayService(  900): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  900): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,E/dalvikvm( 4156): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4156): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4156): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4156): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4156): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4156): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4156): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4156): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4156): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4156): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4156): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4156): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4156): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4156): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4156): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4156): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4156): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4156): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4156): Grow heap (frag case) to 9.920MB for 39954-byte allocation
W/ActivityThread( 1335): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
,D/PMS     (  900): acquireWL(43b1ac48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
,D/PMS     (  900): releaseWL(43b1ac48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/dalvikvm-heap( 4156): Grow heap (frag case) to 9.997MB for 79892-byte allocation
,I/dalvikvm-heap( 4156): Grow heap (frag case) to 10.067MB for 84664-byte allocation
,I/dalvikvm-heap( 4156): Grow heap (frag case) to 10.093MB for 28144-byte allocation
,D/GCM     ( 1335): Connected
D/PMS     (  900): acquireWL(42b3de08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1335 10028 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/PMS     (  900): releaseWL(432d3738): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1335/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: starting a change hold
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/PMS     (  900): releaseWL(42b3de08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  900): acquireWL(425a27f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1335 10028 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
,D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1335/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1335): Message class mpf
D/ConnectivityService(  900): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  900): reportInetCondition for net 1, percentage: 100 by  (1335/10028)
D/ConnectivityService(  900): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  900): handleInetConditionChange: currently in hold - not setting new end evt,
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/PMS     (  900): releaseWL(425a27f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  900): acquireWL(430e4bb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
D/PMS     (  900): releaseWL(430e4bb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/dalvikvm-heap( 4156): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
,W/BroadcastQueue(  900): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43314e38 u0 ReceiverList{43314d18 4156 com.facebook.katana/10026/u0 remote:439b2de0}}
,W/BroadcastQueue(  900): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43f71758 u0 ReceiverList{43f716f8 4156 com.facebook.katana/10026/u0 remote:42b16678}}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [12][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
,D/PMS     (  900): acquireWL(4263c9f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
,D/PMS     (  900): releaseWL(4263c9f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1402): Unknown pending intent to remove.
D/PMS     (  900): acquireWL(43d96b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
D/PMS     (  900): releaseWL(43d96b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/SurfaceControl(  900): Excessive delay in blankDisplay() while turning screen off: 410ms
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  900): nativeSetInteractive:false
D/PMS     (  900): nativeSetInteractive:false done
D/PMS     (  900): nativeSetAutoSuspend:true
D/PMS     (  900): nativeSetAutoSuspend:true done
D/HABCtrl (  900): TPE algorithm. remove timeout.
D/PMS     (  900): OOBE c monitor 11
I/InputManager(  900): Cancel all due to getting PMS screen off broadcast
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/NfcService( 1225): ScreenObserver: OFF
D/NfcService( 1225): applyRouting - 0
D/NfcService( 1225): applyRouting -2
V/KeyguardServiceDelegate(  900): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43af2360)
,I/IntentController( 1103): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  900): acquireWL(439ba6e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
D/PMS     (  900): releaseWL(439ba6e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  900): wakingUp
I/InputMethodManagerService(  900): screenObserver, isScreenOn=false
I/InputMethodManagerService(  900): Disable input method client, pid=3871
,W/ContextImpl( 4156): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,V/KeyguardServiceDelegate(  900): **** SHOWN CALLED ****
I/WindowManager(  900): No lock screen! windowToken=null
D/PMS     (  900): acquireWL(4299c308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/WirelessDisplayService(  900): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  900): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  900): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4156): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  900): n_update end
D/PMS     (  900): releaseWL(4299c308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  900): onScreenOn
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
,D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2204): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2204): [MTP][onReceive]-
,D/NfcService( 1225): applyRouting - 0
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,D/PMS     (  900): acquireWL(43a21c70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1225 1027 null
,D/NfcService( 1225): applyRouting -2
D/PMS     (  900): releaseWL(43a21c70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  900): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  900): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  900): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1103): stop update clock
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,D/AlarmManager(  900): ACTION_SCREEN_ON
I/AlarmManager(  900): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  900): [AlarmQueuing] done recovering
I/AlarmManager(  900): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WifiDataStallTracker(  900): onReceive: action=android.intent.action.SCREEN_ON
,I/AlarmManager(  900): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  900): startDataStallAlarm: tag=19831 delay=15s
D/WifiNative-wlan0(  900): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): SET_SCREEN_ON:On
I/wpa_supplicant( 4009): htc_wext_set_keepalive +
I/wpa_supplicant( 4009): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4009): getPrivFuncNum +	
I/wpa_supplicant( 4009): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4009): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4009): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  900):    returned true
I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  900): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  900): updateScreenOn: false
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  900): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  900): doBoolean: SignalStrength 97
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4009): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,D/ContactMessageStore( 1214): notify MmsSms
,D/AccFlag ( 1214): sense_version=6.0
,D/AccFlag ( 1214): sku_id=99
,D/WIFI_ICON( 1103): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3980): onScreenOn: 1449746255031
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3980): onScreenOn: 1449746255031
D/PMS     (  900): acquireWL(42b23b40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
D/PMS     (  900): releaseWL(42b23b40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  900): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42384450
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  900): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 2
W/SensorService(  900): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  900): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42384450, eanble = 0, strlen(mName) = 91
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  900): Listener[0] = com.htc.smartdim.sensor_eye@426104e8
,W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  900): goingToSleep
D/PMS     (  900): acquireWL(43921570): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 900 1000 null
,D/AlarmManager(  900): ACTION_SCREEN_OFF
,I/AlarmManager(  900): [AlarmQueuing] screen off now: 
I/AlarmManager(  900): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  900): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  900): stopDataStallAlarm: current tag=19831 mDataStallAlarmIntent=PendingIntent{42b3bc80: PendingIntentRecord{4252dd80 android broadcastIntent}}
I/AlarmManager(  900): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  900): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  900): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): SET_SCREEN_ON:Off
I/wpa_supplicant( 4009): htc_wext_set_keepalive +
I/wpa_supplicant( 4009): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4009): getPrivFuncNum +	
I/wpa_supplicant( 4009): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4009): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4009): get_ip_address source addr = c0a80176
I/wpa_supplicant( 4009): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4009): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  900):    returned true
,D/PMS     (  900): acquireWL(43cc2b28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 900 1000 null
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/PluginProvider( 4203): PluginProvider onCreate
,D/NetworkPolicy(  900): updateScreenOn: false
D/PluginProvider( 4203): current plugin count: 19
D/HtcAppUPService( 4203): HtcUPDataProvider onCreate()
D/ContactMessageStore( 1214): start background delete task...
D/ContactMessageStore( 1214): size: 0 , 0
D/ContactMessageStore( 1214): Background delete complete
D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  900):    returned true
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  900): releaseWL(43cc2b28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/AutoSetting( 4203): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/DotMatrix( 1523): [EventService] getTotalRam: 1873 Mb
,I/ActivityManager(  900): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4232 uid=10078 gids={50078, 3003, 5012}
,D/Process (  900): killProcessQuiet, pid=3793
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  900): Killing 3793:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (4203/10053)
D/PMS     (  900): acquireWL(4262e650): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
D/PMS     (  900): releaseWL(4262e650): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 4203): service - onCreate()
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3980): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3980): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3980): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3980): onScreenOff
I/ActivityManager(  900): Recipient 3793,
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4203): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  900): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  900): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 4203): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/LocationManagerService(  900): request 42579560 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  900): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 4203): service - onStartCommand() screen is off, don't request location
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 4203): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4203): service - onStartCommand() check timezone in 30000
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (4203/10053)
,D/MobileConnectivityChangeReceiver( 4232): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4232): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4232): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4232): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4232/10078)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4232/10078)
D/PMS     (  900): acquireWL(42fd3ca0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1193 10028 null
,I/ActivityManager(  900): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4248 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/PMS     (  900): acquireWL(42c0e198): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1193 10028 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4232/10078)
,D/PMS     (  900): releaseWL(42fd3ca0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
I/CheckinService( 1193): Preparing to send checkin request
I/EventLogService( 1193): Accumulating logs since 1449745200075
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4248): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4248): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/EventLogAggregator( 1193): Unknown tag: install_package_attempt
W/EventLogAggregator( 1193): Unknown tag: snet
,W/EventLogAggregator( 1193): Unknown tag: snet_gcore
,W/GAV2    ( 4248): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4248): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4248): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/CalendarProvider2( 4176): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4176): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  900): killProcessQuiet, pid=3813
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  900): Killing 3813:com.htc.backup/1000 (adj 15): empty #17
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  900): Recipient 3813
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GoogleHttpClient( 1193): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1193): Using GMS GoogleHttpClient
,D/WifiService(  900): New client listening to asynchronous messages
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (1193/10028)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (1193/10028)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4248/10151)
,V/WebViewChromiumFactoryProvider( 4248): Binding Chromium to main looper Looper (main, tid 1) {41b400f0}
,I/LibraryLoader( 4248): Expected native library version number "",actual native library version number ""
,I/chromium( 4248): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4248): Initializing chromium process, renderers=0
,D/PMS     (  900): acquireWL(42bac640): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  900): acquireWL(426aab38): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  900): releaseWL(42bac640): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 4248): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4248): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4248): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4248): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4248): Local Branch: 
I/Adreno-EGL( 4248): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4248): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4248):                  aa63bbd948f41d15fc72f585e
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NSApplication( 4248): Starting up...
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4248/10151)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4248/10151)
,W/CheckinRequestBuilder( 1193): awaiting user notification for token
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41b99978 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.google.android.gms 2 9 2 12
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (3654/10160)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (3654/10160)
,D/Process (  900): killProcessQuiet, pid=3830
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  900): Killing 3830:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
W/ActivityManager(  900): Activity pause timeout for ActivityRecord{41b33418 u0 com.test.thalitest/.MainActivity t2}
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Recipient 3830
,I/ActivityManager(  900): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=4289 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  900): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4301 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/CalendarApplication( 4289): onCreate
,I/MultiDex( 4301): install
,D/AlertReceiver( 4289): beginStartingService
,I/MultiDex( 4301): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4301): loading existing secondary dex files
,I/MultiDex( 4301): load found 1 secondary dex files
,D/Process (  900): killProcessQuiet, pid=3536
,I/MultiDex( 4301): install done
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  900): acquireWL(4446d260): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4289 10013 null
I/ActivityManager(  900): Killing 3536:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PMS     (  900): acquireWL(44342d18): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1193 10028 null
,I/ProviderInstaller( 4301): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  900): releaseWL(44342d18): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/AlertService( 4289): start to updateAlertNotification!
,D/AlertService( 4289): No fired or scheduled alerts
,D/HtcAlertUtils( 4289): -- cancelReminderNotification --
,D/HtcAlertUtils( 4289): broadcastExistReminder!
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 4289): stopSelfResult true
D/PMS     (  900): releaseWL(4446d260): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  900): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4321 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  900): Recipient 3536
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GoogleHttpClient( 4301): Falling back to old SSLCertificateSocketFactory
,I/ActivityManager(  900): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4337 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4321): can't get weather sync account
,W/WeatherRequest( 1103): request cur loc, but there is no sys cur
,W/WeatherRequest( 4321): request cur loc, but there is no sys cur
,W/Settings( 4321): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,D/PMS     (  900): acquireWL(43de3840): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4337 10070 null
,D/PMS     (  900): acquireWL(43de3538): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4337 10070 null
,D/PMS     (  900): releaseWL(43de3840): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/libc    ( 4301): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4301): [NET] getaddrinfo-,err=8
D/libc    ( 4301): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4301): [NET] getaddrinfo-, 1
,D/libc    ( 4301): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5ef6 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/TodoTaskshortcut( 4337): update TASK shortcut>
,I/TodoTaskNotifyService( 4337): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/ActivityManager(  900): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4354 uid=10090 gids={50090, 3003, 5012, 1028}
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/AppWidgetHostView( 1242): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1242): com.htc.widget.weatherclock (true,33751552)
,I/TodoTaskNotifyService( 4337): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/RemoteViews.Performance( 1242): com.htc.widget.weatherclock 1 11 17
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 81
D/libc    (  364): [NET]res_nsend:resplen=86
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4301): [NET] getaddrinfo_proxy-, success
,W/NotifyReceiver( 4337): stopSelfResult true
,D/Process (  900): killProcessQuiet, pid=3780
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  900): releaseWL(43de3538): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  900): Killing 3780:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 3780
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.Global( 4354): isHtcDevice = true
,I/WorldClock.Global( 4354): isHtcDevice = true
W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4354): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  900): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4369 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 4354): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4354): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1103): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/libc    ( 4301): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4301): [NET] getaddrinfo-,err=8
,D/PMS     (  900): acquireWL(439b2420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/PMS     (  900): releaseWL(439b2420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/Process (  900): killProcessQuiet, pid=3619
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3619:com.android.vending/u0a73 (adj 15): empty #17
,D/TimeService( 4369): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449746256112
,D/Process (  900): killProcessQuiet, pid=4027
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  900): Killing 4027:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  900): Recipient 4027
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4384 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Recipient 3619
,I/Babel   ( 4384): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4384): MmsConfig.loadMmsSettings
,E/dalvikvm( 4384): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4384): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4384): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4384): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4384): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  900): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4407 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/jxcore-log( 3871): Test app app.js loaded
I/jxcore-log( 3871): 
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4384, uid=10111, userID:0
,D/MessageFrequencyProvider( 4407): onCreate
,I/Choreographer( 3871): Skipped 543 frames!  The application may be doing too much work on its main thread.
,V/GetPrviateResource( 4407): GetPrviateResource
,V/GetPrviateResource( 4407): GetPrviateResource
,D/MmsCustomizationProvider( 4407): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/Settings( 4384): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 4407): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4384): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4384): MmsConfig.loadFromDatabase
,I/ProviderInstaller( 4384): Installed default security provider GmsCore_OpenSSL
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4384, uid=10111, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4384, uid=10111, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4384, uid=10111, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4384, uid=10111, userID:0
,I/chromium( 3871): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 3871): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3871): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b4b028 VFEDH.C. .F....ID 0,0-720,1134 #64}
E/Babel   ( 4384): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4384): MmsConfig.loadFromResources
,E/Babel   ( 4384): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4384): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4384, uid=10111, userID:0
D/PMS     (  900): releaseWL(43921570): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/ActivityManager(  900): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,D/Process (  900): killProcessQuiet, pid=4010
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  900): Killing 4010:com.htc.widget.process2/u0a48 (adj 15): empty #17
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.talk (4384/10111),
,I/ActivityManager(  900): Recipient 4010
,D/MessageCustFlag( 4407): sense_version=6.0
,D/BTAccessoryUtil( 4407): createReceiver
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (4301/10028)
D/BTAccessoryUtil( 4407): registerReceiver return intent = null
D/MessageCustFlag( 4407): sku_id=99
W/SystemReader( 4407): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4407): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4407): networkCode: 
,D/MessageCustFlag( 4407): sku_id=99
D/MmsConfig( 4407): SIE smsPri: null
,D/MmsConfig( 4407): networkCode: 
D/HtcTelephonyCapability( 4407): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4407): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4407): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4407): Cannot find qct_8960_interface, use default value instead
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.talk (4384/10111)
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4384): UserRecoverableAuthException.
,E/Babel   ( 4384): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4384): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4384): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4384): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4384): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4384): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4384): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4384): Error getting auth token
,E/Babel   ( 4384): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4384): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4384): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4384): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4384): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4384): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4384): Account registration failedRedacted-21
,E/Babel   ( 4384): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4384): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4384): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4384): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4384): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4384): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4384): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4384): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.talk (4384/10111)
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4384): Unexpected exception while authenticating.
,E/Babel   ( 4384): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4384): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4384): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4384): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4384): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4384): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4384): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4384): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4384): 	at java.lang.Thread.run(Thread.java:864)
D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41c7b568 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.google.android.gms 1 8 2 12
,W/Settings( 4301): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  900): Resuming delayed broadcast
,D/AutoSetting( 4203): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  900): killProcessQuiet, pid=3942
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3942:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
,D/TetherSettings( 3327): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3327): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3327): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3327): Cust_ConnectToPC   : spcsc>false
D/        ( 3327): Cust_ConnectToPC   : IPT>true
D/        ( 3327): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3327): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3327): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3327): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 4203): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3327): onReceive:android.intent.action.USER_PRESENT
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  900): Recipient 3942
I/SmartNS_PSService( 3327): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3327):  defaultType:0
I/ActivityManager(  900): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4430 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  900): acquireWL(41f16718): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4430 1000 null
D/SmartSyncUtils( 4430): isEpsOn(), nState = 0
,D/PMS     (  900): releaseWL(41f16718): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4430): getMobilePolicyEnabled, result = true
,D/Process (  900): killProcessQuiet, pid=3962
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3962:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  900): Recipient 3962
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
,I/Adreno-EGL( 4301): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4301): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4301): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4301): Local Branch: 
I/Adreno-EGL( 4301): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4301): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4301):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
W/ContextImpl( 4430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4430): isEpsOn(), nState = 0
D/SmartSyncUtils( 4430): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4430): getMobilePolicyEnabled, result = true
D/WifiService(  900): New client listening to asynchronous messages
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/ProviderChangeReceiver( 4289): ---------------------------------------------------
,D/ProviderChangeReceiver( 4289): ProviderChangeReceiver onReceive, start to update notification!
,I/SensorManager(  900): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426104e8
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  900): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 1
W/SensorService(  900): CM36282 Proximity sensor (handle=0x00000001, connections=1)
D/AlertService( 4289): start to updateAlertNotification!
W/SensorService(  900): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426104e8, eanble = 0, strlen(mName) = 36
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  900): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  900): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  900): pid=900, uid=1000
W/SensorService(  900): Active sensors: size = 0
W/SensorService(  900): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426104e8, eanble = 0, strlen(mName) = 36
W/SensorService(  900): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  900): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  900): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426104e8
W/ContextImpl( 3745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  900): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42610a60 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  900): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42610a60 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  900): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  900): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  900): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  900): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  900): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  900): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  900): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  900): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  900): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  900): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  900): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  900): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  900): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  900): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  900): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  900): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  900): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  900): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
W/fb4a(:<default>):UserScope( 4156): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4156): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/AlertService( 4289): No fired or scheduled alerts
D/HtcAlertUtils( 4289): -- cancelReminderNotification --
D/HtcAlertUtils( 4289): broadcastExistReminder!
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  900): Resuming delayed broadcast
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=3 [29][1][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  900): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  900): Resuming delayed broadcast
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/PMS     (  900): acquireWL(426111c0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4337 10070 null
D/PMS     (  900): acquireWL(425a1670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4337 10070 null
D/PMS     (  900): acquireWL(42425230): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4337 10070 null
I/ActivityManager(  900): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  900): releaseWL(426111c0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4337): java.lang.NullPointerException
,W/System.err( 4337): java.lang.NullPointerException
W/System.err( 4337): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4337): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4337): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4337): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4337): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4337): stopSelfResult true
D/PMS     (  900): acquireWL(425a1670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4337 10070 null
D/PMS     (  900): releaseWL(42425230): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  900): releaseWL(425a1670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4459 uid=10038 gids={50038}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4156/10026)
,I/Adreno-EGL( 4301): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4301): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4301): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4301): Local Branch: 
I/Adreno-EGL( 4301): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4301): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4301):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4301): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4301): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4301): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4301): Local Branch: 
I/Adreno-EGL( 4301): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4301): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4301):                  aa63bbd948f41d15fc72f585e
,D/Process (  900): killProcessQuiet, pid=4110
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  900): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4472 uid=10077 gids={50077}
I/ActivityManager(  900): Killing 4110:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  900): Recipient 4110
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  900): Client com.google.android.music (pid 4110): Died!
,D/SMSBackup( 4472): Got a database change event
D/Process (  900): killProcessQuiet, pid=4156
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  900): Killing 4156:com.facebook.katana/u0a26 (adj 15): empty #17
,I/CheckinTask( 1193): Sending checkin request (9005 bytes)
W/ActivityThread( 1193): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  900): Client connection lost with reason: 4
,I/ActivityManager(  900): Recipient 4156
,D/PMS     (  900): acquireWL(42631200): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
,D/PMS     (  900): acquireWL(43f3fa80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
,D/PMS     (  900): releaseWL(42631200): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  900): releaseWL(43f3fa80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/libc    ( 1193): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1193): [NET] getaddrinfo-,err=8
D/libc    ( 1193): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1193): [NET] getaddrinfo-, 1
,D/libc    ( 1193): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c533 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 105
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1193): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1193): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1193): [NET] getaddrinfo-,err=8
,D/PMS     (  900): acquireWL(441e0430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/PMS     (  900): releaseWL(441e0430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CheckinResponseProcessor( 1193): From server: 1 gservices updates and 1 deletes
,I/CertBlacklister(  900): Certificate blacklist changed, updating...
,I/CertBlacklister(  900): Certificate blacklist updated
,I/GservicesProvider( 1335): main difference update completed
,I/ActivityManager(  900): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4489 uid=10016 gids={50016, 3003, 5012, 2001}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4232/10078)
,D/Messaging( 4407): mNeedToUpdateDate2 start
,D/MmsConfig( 4407): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4407): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4407): 
D/MmsAsyncWorkHandler( 4407): HM tk = 20001
,D/ReportIndicatorCache( 4407): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4407): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b46730
,I/Messaging( 4407): mccmnc> 
D/DraftCache( 4407): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4407): [DraftCache/1] refresh
,D/MmsConfig( 4407): networkCode: 
,D/Messaging( 4407): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 4407): sense_version=6.0
,D/PMS     (  900): releaseWL(426aab38): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/Jerry   ( 4407): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 4407): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4407): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4407): createReceiver
D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1214):  phoneType = -1
,D/MmsSmsV2Provider( 1214): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1214): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
V/MmsProvider( 1214): Update uri=content://mms, match=0
,V/MmsProvider( 1214): selection=st=129 AND m_type!=134
,D/Messaging( 4407): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4407): TransactionService is going to be woken up.
D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1214):  phoneType = -1
,D/MmsSmsV2Provider( 1214): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4407): 1-Creating TransactionService
D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (1193/10028)
W/ContextImpl( 4489): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
V/TransactionService( 4407): onStartCommand: 1
,D/MmsSystemEventReceiver( 4407): unRegisterForConnectionStateChanges
V/TransactionService( 4407): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4407): Loading previous transactions.
,D/Messaging( 4407): mNeedToUpdateDate2: false
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (1193/10028)
D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1214):  phoneType = -1
I/UpdateFetcherService( 4489): Update started
D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/AccFlag ( 1214): device_type: 1
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=12 [24][3][0]
D/TransactionService( 4407): Force set service start id to 1
V/TransactionService( 4407): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4407): unRegisterForConnectionStateChanges
,D/TransactionService( 4407): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4407): Destroying TransactionService
,I/ActivityManager(  900): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
D/Messaging( 4407): ViewCache CreatePreload
D/Messaging( 4407): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 4407): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Cust_MMSMS( 4407): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4407): def_index: 0
,D/MsgPreferenceUtils( 4407): globalIndex = 1
D/MsgPreferenceUtils( 4407): phone state: true
D/MsgPreferenceUtils( 4407): sd state: false
,D/MsgPreferenceUtils( 4407): vIndex = 0
,I/ActivityManager(  900): Resuming delayed broadcast
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,E/UpdateRequestReceiver( 4489): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  900): getAllNetworkInfo called by  (2204/10021)
,W/ContextImpl( 4489): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,I/UpdateFetcherService( 4489): Update started
,D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1214):  phoneType = -1
,D/MmsSmsV2Provider( 1214): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1214): sku_id=99
,I/DownloadManager( 2204): Download 131 starting
I/ActivityManager(  900): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
D/PMS     (  900): acquireWL(41fabf58): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2204 10021 WorkSource{10016}
,D/DraftCache( 4407): [DraftCache/454] rebuildCache
D/ConnectivityService(  900): getAllNetworkInfo called by  (2204/10021)
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1214):  phoneType = -1
,D/MmsSmsV2Provider( 1214): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1193): awaiting user notification for token
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41c819d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/Messaging( 4407): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/Jerry   ( 1214): URI_DRAFT
D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
,W/ActivityThread( 2204): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/RemoteViews.Performance( 1103): com.google.android.gms 1 10 4 12
D/DraftCache( 4407): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4407): [DraftCache/454] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4407): 
D/MmsAsyncWorkHandler( 4407): HM tk = 20002
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AccFlag ( 1214): sku_id=99
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/TelephUtils( 1214): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/AccFlag ( 1214): sku_id=99
I/ActivityManager(  900): Resuming delayed broadcast
D/ConnectivityService(  900): getAllNetworkInfo called by  (2204/10021)
E/UpdateRequestReceiver( 4489): Received malformed URL while handling Gservices.CHANGED_ACTION
I/CheckinTask( 1193): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
W/GoogleHttpClient( 1193): Unable to close GMS GoogleHttpClient
E/UpdateRequestReceiver( 4489): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4489): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/Process (  900): killProcessQuiet, pid=4232
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
I/ActivityManager(  900): Killing 4232:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,D/PMS     (  900): acquireWL(42017bc8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2204 10021 WorkSource{10016}
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/DownloadManager( 2204): Download 132 starting
I/ActivityManager(  900): Recipient 4232
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  900): getAllNetworkInfo called by  (2204/10021)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
,I/ActivityManager(  900): Delay finish: com.google.android.gms/.analytics.internal.GServicesChangedReceiver
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,V/GA-SERVICE( 1193): Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1193, uid=10028, userID:0
D/libc    ( 2204): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2204): [NET] getaddrinfo-,err=8
D/libc    ( 2204): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2204): [NET] getaddrinfo-, 1
D/libc    ( 2204): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2fad +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    ( 2204): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2204): [NET] getaddrinfo-,err=8
D/libc    ( 2204): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2204): [NET] getaddrinfo-, 1
,D/libc    ( 2204): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3e34 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
I/ActivityManager(  900): Resuming delayed broadcast
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
D/PMS     (  900): acquireWL(431a0088): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1193 10028 null
D/PMS     (  900): releaseWL(431a0088): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/SystemUpdateService( 1193): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 197
D/libc    (  364): [NET]res_nsend:resplen=49
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2204): [NET] getaddrinfo_proxy-, success
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2204): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
D/PMS     (  900): acquireWL(42dc9848): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1193 10028 null
I/ActivityManager(  900): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,D/PMS     (  900): releaseWL(42c0e198): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/SystemUpdateService( 1193): cancelUpdate (empty URL)
,I/SystemUpdateService( 1193): active receiver: disabled
E/ActivityThread( 1193): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e1d3f0 that was originally bound here
E/ActivityThread( 1193): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e1d3f0 that was originally bound here
E/ActivityThread( 1193): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1193): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1193): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1193): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1193): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1193): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1193): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1193): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1193): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1193): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1193): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1193): 	at bks.a(SourceFile:298)
E/ActivityThread( 1193): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1193): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1193): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1193): 	at java.lang.Thread.run(Thread.java:864)
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1193, uid=10028, userID:0
I/SystemUpdateService( 1193): cancelUpdate (empty URL)
I/SystemUpdateService( 1193): active receiver: disabled
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1193, uid=10028, userID:0
D/GCM     ( 1335): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  900): Resuming delayed broadcast
D/PMS     (  900): releaseWL(42dc9848): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
I/ActivityManager(  900): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
D/PMS     (  900): acquireWL(4264aa98): PARTIAL_WAKE_LOCK  Icing 0x1 1193 10028 null
D/PMS     (  900): releaseWL(4264aa98): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  900): Resuming delayed broadcast
,I/GCM     ( 1335): GCM config loaded
,I/ActivityManager(  900): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/DownloadManager( 2204): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager(  900): Resuming delayed broadcast
D/SystemEventReceiver( 1193): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1193): Updating ocr activity enabled=false
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1193, uid=10028, userID:0
,I/GCoreUlr( 1402): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
D/PMS     (  900): acquireWL(425a11a0): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1402 10028 null
,I/GCoreUlr( 1402): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,I/ActivityManager(  900): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4559 uid=10031 gids={50031, 3003, 5012}
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [13][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  900): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,I/DownloadManager( 2204): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2204): Download 132 finished with status SUCCESS
D/PMS     (  900): releaseWL(42017bc8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/PMS     (  900): acquireWL(43b82b18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
D/PMS     (  900): releaseWL(43b82b18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4559, uid=10031, userID:0
D/PMS     (  900): acquireWL(423c0628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4559, uid=10031, userID:0
D/PMS     (  900): releaseWL(423c0628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4559, uid=10031, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=4559, uid=10031, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4559, uid=10031, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4559, uid=10031, userID:0
,D/PMS     (  900): acquireWL(42996600): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
,D/PMS     (  900): releaseWL(42996600): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  900): acquireWL(429f4e08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
,D/PMS     (  900): releaseWL(429f4e08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  900): acquireWL(42c8dc28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
,D/PMS     (  900): releaseWL(42c8dc28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/DownloadManager( 2204): Download 131 finished with status SUCCESS
D/PMS     (  900): releaseWL(41fabf58): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/GCoreUlr( 1402): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1402): Unknown pending intent to remove.
D/PMS     (  900): acquireWL(42c6a620): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
D/PMS     (  900): acquireWL(423c9bd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
D/PMS     (  900): releaseWL(42c6a620): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/GCoreUlr( 1402): Unbound from all location providers
D/PMS     (  900): releaseWL(423c9bd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  900): releaseWL(425a11a0): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,D/PMS     (  900): acquireWL(41f7ac28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
,D/PMS     (  900): releaseWL(41f7ac28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  900): Resuming delayed broadcast
,D/Process (  900): killProcessQuiet, pid=4128
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4128:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4128
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4581 uid=10078 gids={50078, 3003, 5012}
,E/PhoneMonitor( 4581): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4581): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  900): killProcessQuiet, pid=4248
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  900): Killing 4248:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ContactAccountLoggerTas( 2658): canRun() : Opted Out
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10078)
,I/Search.GservicesUpdateTask( 2658): Updating Gservices keys
D/PMS     (  900): acquireWL(42406ae8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1193 10028 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10078)
,D/PMS     (  900): acquireWL(42df2f58): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1193 10028 null
,D/PMS     (  900): releaseWL(42406ae8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10078)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,D/PMS     (  900): releaseWL(42df2f58): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/ContactAccountLoggerTas( 2658): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2658): canRun() : Opted Out
,W/Search.LoginHelper( 2658): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2658): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2658): canRun() : Opted Out
I/ActivityManager(  900): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
,I/ContactAccountLoggerTas( 2658): canRun() : Opted Out
,I/ActivityManager(  900): Resuming delayed broadcast
D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCM     ( 1335): GCM config loaded
,I/dalvikvm-heap( 3654): Grow heap (frag case) to 13.620MB for 1821008-byte allocation
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3654, uid=10160, userID:0
,I/dalvikvm-heap( 3654): Grow heap (frag case) to 15.317MB for 1821008-byte allocation
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3654, uid=10160, userID:0
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Recipient 4248
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3654, uid=10160, userID:0
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3654, uid=10160, userID:0
,W/ContextImpl( 4489): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  900): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,D/ConnectivityService(  900): getAllNetworkInfo called by  (2204/10021)
,I/DownloadManager( 2204): Download 133 starting
D/PMS     (  900): acquireWL(4446d0a0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2204 10021 WorkSource{10016}
D/ConnectivityService(  900): getAllNetworkInfo called by  (2204/10021)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
,W/ContextImpl( 4489): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  900): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2204): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager(  900): Resuming delayed broadcast
,D/ConnectivityService(  900): getAllNetworkInfo called by  (2204/10021)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
I/AdsMeasurementBroadcastReceiver( 1193): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1193): Unauthorized to start the main service
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DownloadManager( 2204): Download 134 starting
D/PMS     (  900): acquireWL(4220ad18): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2204 10021 WorkSource{10016}
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  900): getAllNetworkInfo called by  (2204/10021)
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2204): Ignoring Content-Length since Transfer-Encoding is also defined
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=3 [30][1][0]
D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
,I/DownloadManager( 2204): Download 133 finished with status SUCCESS
D/PMS     (  900): releaseWL(4446d0a0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4489): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/DownloadManager( 2204): Download 134 finished with status SUCCESS
,I/UpdateFetcherService( 4489): Update downloaded, starting installation
,I/ActivityManager(  900): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/UpdateFetcherService( 4489): Started installation
D/PMS     (  900): releaseWL(4220ad18): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/ActivityManager(  900): Resuming delayed broadcast
,W/ContextImpl( 4489): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4489): Update downloaded, starting installation
,I/UpdateFetcherService( 4489): Started installation
I/ActivityManager(  900): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ConfigUpdateInstallReceiver(  900): Not installing, new version is <= current version
,D/Process (  900): killProcessQuiet, pid=3414
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 3414:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Recipient 3414
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4384, uid=10111, userID:0
,D/Process (  900): killProcessQuiet, pid=4321
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4321:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4321
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
,D/ConnectivityService(  900): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  900): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/Process (  900): killProcessQuiet, pid=4354
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4354:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4354
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3654): Grow heap (frag case) to 17.065MB for 1821008-byte allocation
,I/GAV2    ( 3654): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 4203): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4203): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4203): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/PackageSettings(  900): Skipping PackageSetting{42282e38 com.example.hello/10355} due to missing metadata
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{42e73fd0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1300): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1300): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PackageBroadcastService( 1193): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  900):   Scheme: "sms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1242): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  900):   Scheme: "smsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/Launcher( 1242): Deferring update until onResume
,D/Launcher( 1242): waitUntilResume // bindAppsUpdated
,I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  900):   Scheme: "mms"
,D/AccTypeManager( 1300): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  900):   Scheme: "mmsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/ActivityManager(  900): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/PMS     (  900): acquireWL(42dda7b8): PARTIAL_WAKE_LOCK  Icing 0x1 1193 10028 null
I/PeopleContactsSync( 1193): CP2 sync disabled
,I/[PluginManager]RegisterService( 4203): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 4203): handle notify Blinkfeed plugin client changed
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1193, uid=10028, userID:0
I/ActivityManager(  900): Resuming delayed broadcast
,I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  900):   Scheme: "sms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/ActivityManager(  900): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4624 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/PMS     (  900): releaseWL(42dda7b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  900):   Scheme: "smsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  900):   Scheme: "mms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,E/ExternalAccountType( 1300): Unsupported attribute readOnly
,I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  900):   Scheme: "mmsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,D/PhoneApp( 1214): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4624, uid=10073, userID:0
,D/Finsky  ( 4624): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  900): getAllNetworkInfo called by com.android.vending (4624/10073)
,D/ConnectivityService(  900): getAllNetworkInfo called by com.android.vending (4624/10073)
,D/Finsky  ( 4624): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4624): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4624): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4624, uid=10073, userID:0
,D/Finsky  ( 4624): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4624): [1] 2.run: Finished loading 1 libraries.
,D/Process (  900): killProcessQuiet, pid=4369
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  900): Killing 4369:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4369
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2658): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,D/PMS     (  900): acquireWL(4261aa48): PARTIAL_WAKE_LOCK  AsyncService 0x1 3654 10160 null
,D/Finsky  ( 4624): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PMS     (  900): releaseWL(4261aa48): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4624): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/IcingCorporaProvider( 2658): UpdateCorporaTask done [took 168 ms] updated apps [took 168 ms] 
,I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1242): loadItems() com.htc.launcher.pageview.WidgetManager@41bceed0 +
,I/Prism.WidgetManager( 1242): onLoadItems() +
,D/PMS     (  900): acquireWL(42568738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10073}
,V/AlarmManager(  900): sending alarm PendingIntent{42399468: PendingIntentRecord{42390e88 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449746273294, Int=0
,D/PhoneApp( 1214): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1214): -- N1 =0
,D/PhoneApp( 1214): -- N2 =0
,D/PhoneApp( 1214): -- N3 =0
,W/asset   ( 1242): Copying FileAsset 0x666033b0 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1242): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1242): onLoadItems() -
,I/Prism.ItemManager( 1242): loadItems() com.htc.launcher.pageview.WidgetManager@41bceed0 -
,W/PackageManager(  900): Unable to load service info ResolveInfo{43b96548 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  900): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  900): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  900): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  900): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  900): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  900): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  900): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  900): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  900): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  900): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  900): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  900): start
,D/PMS     (  900): releaseWL(42568738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4624): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4624): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4624): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4624): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4624): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/PMS     (  900): acquireWL(43904788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): releaseWL(43904788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  900): acquireWL(43b884d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=135446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43b884d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43dd59a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41e38b30: PendingIntentRecord{424c47b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=137688, Int=0
,V/AlarmManager(  900): sending alarm PendingIntent{42de8448: PendingIntentRecord{425b3810 com.htc.checkinprovider broadcastIntent}}, i=com.htc.checkin.HTC_CHECKIN, t=0, cnt=1, w=1449746251887, Int=1209600000
,D/PMS     (  900): acquireWL(4312bfa0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 900 1000 null
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/PMS     (  900): acquireWL(42b3b380): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/PMS     (  900): releaseWL(4312bfa0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  900): releaseWL(42b3b380): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/HtcTelephonyCapability(  900): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability(  900): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils(  900): getRATByHtcTelephonyCapability:1
,W/SystemReader(  900): Cannot find qct_8960_interface, use default value instead
,D/htcCheckinService(  900): Roaming is :false
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,I/htcCheckinService(  900): == Checkin triggered == A6.1(KK)
,E/htcCheckinService(  900): can't get the url information = 
E/htcCheckinService(  900): java.lang.NullPointerException
E/htcCheckinService(  900): 	at com.htc.checkinprovider.htcCheckinService$CheckinThread.run(htcCheckinService.java:3740)
D/PMS     (  900): releaseWL(43dd59a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42a663c8): PARTIAL_WAKE_LOCK  htcCheckinService_300 0x1 900 1000 null
,D/LocationManagerService(  900): request 427bdee0 network Request[POWER_LOW network requested=0 fastest=0 num=1] from com.htc.checkinprovider(1000)
I/LocationManagerService(  900): remove com.htc.checkinprovider 427bdee0
D/LocationManagerService(  900): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  900): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
D/PMS     (  900): acquireWL(42b25888): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 900 1000 WorkSource{1000 com.htc.checkinprovider}
,D/PMS     (  900): releaseWL(42b25888): PARTIAL_WAKE_LOCK  LocationManagerService 0x1 WorkSource{1000 com.htc.checkinprovider}
D/htcCheckinService.CheckinProtocol(  900): getIMEI()
,V/HtcTelephonyInternal( 1214): CMD_GET_IMEI xxxxxxxxxxxxxxx
,W/SystemReader(  900): Cannot find device_type, use default value instead
,D/ConnectivityService(  900): getNetworkInfo networkType=55 called by  (900/1000)
,I/htcCheckinService(  900): Dump Checkin info:
,I/htcCheckinService(  900): Sending checkin request, times: 1, (842 bytes)...
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
,D/libc    (  900): [NET] getaddrinfo+,hn 17(0x616e646368696e),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-,err=8
D/libc    (  900): [NET] getaddrinfo+,hn 17(0x616e646368696e),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x616e646368696e),sn(),family 0,flags 1024,
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fd92 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 1230
D/libc    (  364): [NET]res_nsend:resplen=51
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo_proxy-, success
I/global  (  900): call createSocket() return a new socket.
D/libc    (  900): [NET] getaddrinfo+,hn 13(0x36302e3139392e),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS,
,D/libc    (  900): [NET] getaddrinfo+,hn 17(0x616e646368696e),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-,err=8
W/ActivityThread(  900): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/htcCheckinService(  900): (from server)bUpdateAction:true
,I/htcCheckinService(  900): Download request accepted.
D/libc    (  900): [NET] getaddrinfo+,hn 17(0x666f7461646c2d),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-,err=8
D/libc    (  900): [NET] getaddrinfo+,hn 17(0x666f7461646c2d),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x666f7461646c2d),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =290 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 1625
D/libc    (  364): [NET]res_nsend:resplen=116
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo_proxy-, success
I/global  (  900): call createSocket() return a new socket.
D/libc    (  900): [NET] getaddrinfo+,hn 13(0x36382e3233322e),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/htcCheckinService(  900): fota confirm intent waits app update response result
,D/htcCheckinService.appUpdateExecuter(  900): setFotaConfirmIntent()
,I/htcCheckinService.appUpdateExecuter(  900): === FOTA AppUpdate Client 6.0 ===
,D/htcCheckinService.CheckinProtocol(  900): getIMEI()
,V/HtcTelephonyInternal( 1214): CMD_GET_IMEI xxxxxxxxxxxxxxx
,W/SystemReader(  900): Cannot find device_type, use default value instead
,D/ConnectivityService(  900): getNetworkInfo networkType=55 called by  (900/1000)
,D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
,D/libc    (  900): [NET] getaddrinfo+,hn 17(0x6170752d636869),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-,err=8
,D/libc    (  900): [NET] getaddrinfo+,hn 17(0x6170752d636869),sn(),family 0,flags 1024
,D/libc    (  900): [NET] getaddrinfo-, 1
D/libc    (  900): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x6170752d636869),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8ce5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 12084
D/libc    (  364): [NET]res_nsend:resplen=51
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo_proxy-, success
I/global  (  900): call createSocket() return a new socket.
D/libc    (  900): [NET] getaddrinfo+,hn 13(0x36302e3139392e),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/AutoSetting( 4203): service - mHandler: update timezone
,D/AutoSetting( 4176): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4176): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4176): service - onCreate()
W/ActivityManager(  900): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  900): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4176): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate,
,D/AutoSetting( 4176): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4176): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 4176): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4176): service - mHandler: update timezone
,D/AutoSetting( 4176): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4176): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4176): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4176): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1103): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41c8f008 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.htc.htclocationservice 1 8 2 11
,D/libc    (  900): [NET] getaddrinfo+,hn 17(0x6170752d636869),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-,err=8
,D/htcCheckinService.appUpdateExecuter(  900): notifyFotaConfirmIntent()
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 com.htc.checkinprovider.appUpdateExecuter.notifyFotaConfirmIntent:152 com.htc.checkinprovider.appUpdateExecuter.doAppCheckin:259 com.htc.checkinprovider.htcCheckinService.notifyIntent:2283 
W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1399 android.content.ContextWrapper.sendBroadcast:377 com.htc.checkinprovider.appUpdateExecuter.doAppCheckin:298 com.htc.checkinprovider.htcCheckinService.notifyIntent:2283 com.htc.checkinprovider.htcCheckinService.doCheckin:2823 
,I/htcCheckinService(  900): Checkin success
,I/ActivityManager(  900): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4682 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,E/htcCheckinService.RunAppUpdateReceiver(  900): Err in mRunUpdateReceiver.onReceive(). Err:java.lang.NullPointerException, [Ljava.lang.StackTraceElement;@42da32f0
,I/htcCheckinService.RunAppUpdateReceiver(  900): == Run AppUpdate Receiver Finished ==
,I/htcCheckinService(  900): == Checkin finished ==
D/PMS     (  900): releaseWL(42a663c8): PARTIAL_WAKE_LOCK  htcCheckinService_300 0x1 null
,V/NotificationService(  900): batLight: Full, plugged
,V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
,D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/DotMatrix( 1523): [NotificationService] onNotificationRemoved, pkgName: com.htc.updater, id: 2130837512
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.htc.updater does not support DotMatrix
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,D/AutoSetting( 4203): service - handleMessage() stop self
,D/AutoSetting( 4203): service - handleMessage() quit looper
,D/AutoSetting( 4203): service - onDestroy() END
,D/NotificationService(  900): notification sound not played, stream=5 volume=0 always=false
D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1103): com.htc.updater (true,33751552)
,D/Process (  900): killProcessQuiet, pid=4384
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  900): Killing 4384:com.google.android.talk/u0a111 (adj 15): empty #17
D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41cfb0c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1103): com.htc.updater 2 7 1 10
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/ActivityManager(  900): Recipient 4384
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1214): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1214): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  900): acquireWL(425fe118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10028}
,V/AlarmManager(  900): sending alarm PendingIntent{42009738: PendingIntentRecord{42566f60 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140605, Int=0
V/AlarmManager(  900): sending alarm PendingIntent{421fda68: PendingIntentRecord{425085e8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141265, Int=0
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
,V/AlarmManager(  900): sending alarm PendingIntent{42c0e070: PendingIntentRecord{43317230 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449746288799, Int=563223000
,V/AlarmManager(  900): sending alarm PendingIntent{422eed50: PendingIntentRecord{43dfa220 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449746289845, Int=0
,D/PMS     (  900): acquireWL(4221ddd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/PMS     (  900): releaseWL(4221ddd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  900): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  900): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  900): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/libc    (  900): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-,err=8
D/libc    (  900): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  900): [NET] getaddrinfo-, 1
,D/libc    (  900): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9b87 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  900): acquireWL(42647758): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/PMS     (  900): acquireWL(42618270): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1193 10028 null
D/PMS     (  900): releaseWL(425fe118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  900): acquireWL(43fd0428): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1193 10028 null
D/PMS     (  900): releaseWL(42618270): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,I/CheckinService( 1193): Preparing to send checkin request
,I/EventLogService( 1193): Accumulating logs since 1449746255306
,W/EventLogAggregator( 1193): Unknown tag: install_package_attempt
W/EventLogAggregator( 1193): Unknown tag: snet
,W/EventLogAggregator( 1193): Unknown tag: snet_gcore
,I/GoogleHttpClient( 1193): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1193): Using GMS GoogleHttpClient
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  900): [NET] getaddrinfo_proxy-, success
I/global  (  900): call createSocket() return a new socket.
D/libc    (  900): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (1193/10028)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4009): environment dirty rate=10 [91][10][0]
D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (1193/10028)
,D/GpsLocationProvider(  900): [handleDownloadXtraData] calling native_inject_xtra_data
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Finsky  ( 4624): [1] 5.onFinished: Installation state replication succeeded.
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1193): awaiting user notification for token
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41ebb610 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.google.android.gms 1 8 3 12
,D/GpsLocationProvider(  900): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  900): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  900):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  900): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (4301/10028)
,W/Settings( 4301): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4301): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4301): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4301): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4301): Local Branch: 
I/Adreno-EGL( 4301): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4301): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4301):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4301): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4301): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4301): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4301): Local Branch: 
I/Adreno-EGL( 4301): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4301): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4301):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4301): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4301): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4301): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4301): Local Branch: 
I/Adreno-EGL( 4301): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4301): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4301):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 1193): Sending checkin request (9001 bytes)
,D/libc    ( 1193): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1193): [NET] getaddrinfo-,err=8
D/libc    ( 1193): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1193): [NET] getaddrinfo-, 1
,D/libc    ( 1193): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6645 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1193): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1193): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1193): [NET] getaddrinfo-,err=8
,W/ContextImpl(  900): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  900): acquireWL(42dc71f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/PMS     (  900): releaseWL(42dc71f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  900): getNetworkInfo networkType=9 called by com.google.android.gms (1193/10028)
,D/WifiNative-wlan0(  900): doString: SIGNAL_POLL
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  900): getNetworkInfo networkType=0 called by com.google.android.gms (1193/10028)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: survey data missing!
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4009): environment dirty rate=11 [44][5][0]
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1193): awaiting user notification for token
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41fa5980 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.google.android.gms 0 9 3 12
,I/CheckinTask( 1193): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1193): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  900): releaseWL(43fd0428): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1193): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41de1ec8 that was originally bound here
E/ActivityThread( 1193): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41de1ec8 that was originally bound here
E/ActivityThread( 1193): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1193): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1193): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1193): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1193): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1193): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1193): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1193): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1193): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1193): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1193): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1193): 	at bks.a(SourceFile:298)
E/ActivityThread( 1193): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1193): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1193): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1193): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1335): GCM config loaded
,D/PMS     (  900): releaseWL(42647758): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{43315078 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,D/PMS     (  900): acquireWL(42646cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): releaseWL(42646cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 4176): service - handleMessage() stop self
,D/AutoSetting( 4176): service - onDestroy() END
,D/AutoSetting( 4176): service - handleMessage() quit looper
,D/Process (  900): killProcessQuiet, pid=4430
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4430:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  900): Client connection lost with reason: 4
,I/ActivityManager(  900): Recipient 4430
,D/TelephonyReceiver( 1214): switchBindHtcMsgCursor: null
,D/PMS     (  900): acquireWL(4221e0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4221e0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
,I/HtcPowerSaver(  900): >> updateStatus
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(4386f728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=195446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4386f728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(439f4728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{420390e0: PendingIntentRecord{43aee030 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230383, Int=0
,I/ActivityManager(  900): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4710 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  900): sending alarm PendingIntent{42017bb8: PendingIntentRecord{425855a8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449746364677, Int=10800000
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230387, Int=120000
,D/PMS     (  900): releaseWL(439f4728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.aurora (4710/10047)
,D/Process (  900): killProcessQuiet, pid=4289
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4289:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4289
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  900): acquireWL(43fddfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43fddfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43d4ff70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=255447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43d4ff70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  900): acquireWL(429d08a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): releaseWL(429d08a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(42e32038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42e32038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4262c5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=315447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4262c5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  900): acquireWL(42600620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=350387, Int=120000
,D/PMS     (  900): releaseWL(42600620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(43b93548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43b93548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  900): acquireWL(4344c938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4344c938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  900): acquireWL(43c718f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=375447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43c718f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  900): acquireWL(4264bf68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): releaseWL(4264bf68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3871): Toggling radios to false
I/jxcore-log( 3871): 
D/BluetoothManagerService(  900): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  900): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@423d7cd0 mBinding = false
W/HtcDLNAServiceManager(  900): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  900): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  900): Settings:Agentvalue: 0
W/Settings:Agent(  900): >> traceCallingStack()
W/Settings:Agent(  900): Process.myPid(): 900
W/Settings:Agent(  900): Process.myTid(): 1438
W/Settings:Agent(  900): Process.myUid(): 1000
W/Settings:Agent(  900): 
W/Settings:Agent(  900): 
,W/System.err(  900): java.lang.Throwable: stack dump
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  900): ,	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  900): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  900): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  900): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  900): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method),
W/Settings:Agent(  900): 
,W/Settings:Agent(  900): << traceCallingStack(): 3(ms),
,D/BluetoothManagerService(  900): Message: MESSAGE_DISABLE
,D/WifiManager( 3871): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,D/BluetoothManagerService(  900): Sending off request.
,D/WifiStateMachine(  900): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  900): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  900): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  900): Settings:Agentvalue: 0
W/Settings:Agent(  900): >> traceCallingStack()
W/Settings:Agent(  900): Process.myPid(): 900
W/Settings:Agent(  900): Process.myTid(): 1254
W/Settings:Agent(  900): Process.myUid(): 1000
W/Settings:Agent(  900): 
W/Settings:Agent(  900): 
W/System.err(  900): java.lang.Throwable: stack dump
W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  900): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  900): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  900): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  900): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  900): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  900): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
,W/System.err(  900): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  900): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
D/WifiService(  900): setWifiEnabled: false pid=3871, uid=10348
E/WifiService(  900): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  900): isSprintWifiRestricted(): false
,I/WifiService(  900): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  900): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  900): 
W/Settings:Agent(  900): << traceCallingStack(): 4(ms)
D/BluetoothAdapterState( 3917): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3917): Setting state to 13
I/BluetoothAdapterState( 3917): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3917): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  900): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3917): onBluetoothDisable()
I/BluetoothAdapterState( 3917): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 3917): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3917): BTM_SetDiscoverability
I/bt-btm  ( 3917): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3917): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3917): br_edr_supported=0x0
I/bt-btm  ( 3917): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3917): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3917): btm_ble_update_adv_flag old=0x0
I/BluetoothAdapterProperties( 3917): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 3917): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3917): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3917): BTM_SetConnectability
I/bt-btm  ( 3917): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode with no scan rsp
D/BluetoothAdapterProperties( 3917): Scan Mode:20
E/BTIF_CORE( 3917): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 3917): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothManagerService(  900): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  900): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothAdapterState( 3917): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService(  900): Bluetooth State Change Intent: 12 -> 13
I/bt-btm  ( 3917): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3917): BTA_JvDeleteRecord
I/bt-btif ( 3917): BTA_JvRfcommStopServer
D/bt-btm  ( 3917): BTM_FreeSCN 
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 3917): bta_jv_rfcomm_stop_server
I/bt-btif ( 3917): BTA_JvDeleteRecord
I/bt-btif ( 3917): BTA_JvRfcommStopServer
D/bt-btm  ( 3917): BTM_FreeSCN 
I/bt-btm  ( 3917): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:14
I/bt-btif ( 3917): BTA_JvDeleteRecord
E/bt-btif ( 3917): bta_jv_rfcomm_stop_server
I/bt-btif ( 3917): BTA_JvRfcommStopServer
I/bt-btm  ( 3917): BTM_FreeSCN 
D/bt-btm  ( 3917): BTM_FreeSCN 
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 3917): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3917): BTM_SEC_CLR[15]: id 54
I/bt-btif ( 3917): BTA_JvDeleteRecord
I/bt-btif ( 3917): BTA_JvRfcommStopServer
D/bt-sdp  ( 3917): BTM_FreeSCN 
D/bt-btm  ( 3917): BTM_FreeSCN 
E/bt-btif ( 3917): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3917): BTM_SEC_CLR[16]: id 55
I/bt-btif ( 3917): BTA_JvDeleteRecord
I/bt-btif ( 3917): BTA_JvRfcommStopServer
D/bt-btm  ( 3917): BTM_FreeSCN 
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 3917): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3917): BTM_SEC_CLR[17]: id 56
I/bt-btif ( 3917): BTA_JvDeleteRecord
I/bt-btif ( 3917): BTA_JvRfcommStopServer
D/bt-btm  ( 3917): BTM_FreeSCN 
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 3917): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3917): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3917): Write Extende,d Inquiry Response to controller
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btm  ( 3917): Write Extended Inquiry Response to controller
I/bt-btm  ( 3917): BTM_SetDiscoverability
I/bt-btm  ( 3917): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3917): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3917): br_edr_supported=0x0
I/bt-btm  ( 3917): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3917): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3917): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3917): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3917): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3917): BTM_SetConnectability
I/bt-btm  ( 3917): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3917): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3917): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3917): BTM_IsInquiryActive
I/bt-btm  ( 3917): BTM_CancelRemoteDeviceName()
W/bt-btif ( 3917): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:7
V/BluetoothSapService( 3917): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3917): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-btm  ( 3917): BTM_FreeSCN 
I/bt-btm  ( 3917): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3917): BTM_FreeSCN 
I/bt-btm  ( 3917): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3917): AVRC_Close handle:0
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 3917): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3917): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3917): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 3917): GATT_Deregister gatt_if=3
I/bt-att  ( 3917): GATT_Deregister gatt_if=4
I/IntentController( 1103): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/PMS     (  900): acquireWL(428fb9a0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 3917 1002 null
D/BluetoothRemoteDevices( 3917): Wake lock Aquired
V/BluetoothPbapReceiver( 3917): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3917): ***********state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 3980): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b64fb8
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3980): onDeInitialized
D/BluetoothMasReceiver( 3917): Bluetooth STATE CHANGED to 13
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3980): cancelAllNotification
V/BluetoothSapReceiver( 3917): SapReceiver onReceive 
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3980): getNotificationManager
V/BluetoothSapReceiver( 3917): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3917):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 3917): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  900): acquireWL(42ac4048): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3327 1000 null
,V/BluetoothPbapService( 3917): Pbap Service closeService in
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PMS     (  900): releaseWL(42ac4048): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3980): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3980):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 3980): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3980): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3980): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3980):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 3980): deinit: 0
D/BluetoothManagerService(  900): Message: MESSAGE_UNREGISTER_ADAPTER
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3980): disableBatteryAlarm
D/BluetoothManagerService(  900): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42134908:true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3980): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3980): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3980): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3980): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3980): setPendingRequestAlarm: false, mContext = null, null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3980): Exit IdleState
,I/jxcore-log( 3871): Radios toggled
I/jxcore-log( 3871): 
D/WirelessDisplayService(  900): getMirrorDisplayStatus:falsecurState:1
D/WifiPerfLock(  900): release()
,D/WifiStateMachine(  900): PerfLock released for exiting ConnectedState
D/PMS     (  900): acquireWL(42fe5700): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3327 1000 null
,D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): Power_Mode_Type mode = 0
I/wpa_supplicant( 4009): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  900):    returned true
,D/DhcpStateMachine(  900): [RunningState] Stop DHCP
D/ConnectivityService(  900): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  900): acquireWL(42f35ae0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 900 1000 null
D/WifiP2pService(  900): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  900): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  900): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  900): [NET] getaddrinfo-, SUCCESS
,D/DockEventReceiver( 3327): finishStartingService: stopping service
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/ActivityManager(  900): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4739 uid=10037 gids={50037, 3002, 3001}
D/BluetoothPbap( 3745): Proxy object disconnected
,D/PbapServerProfile( 3745): Bluetooth service disconnected
D/libc    (  900): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  900): [NET] getaddrinfo-, SUCCESS
D/BluetoothPbap( 3327): Proxy object disconnected
,D/PbapServerProfile( 3327): Bluetooth service disconnected
V/BluetoothPbapService( 3917): successfully stopped pbap service
V/BluetoothPbapService( 3917): Pbap Service closeService out
V/BluetoothSapService( 3917): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3917): state: 13
I/QuickSettingBluetooth( 1103): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
,D/PhoneStatusBar( 1103): removeIcon slot=bluetooth index=12 viewIndex=0
,D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING GET
D/BluetoothAdapter( 3917): 1102415744: getState(). Returning 13
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  900): stopDataStallAlarm: current tag=19832 mDataStallAlarmIntent=null
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
V/BluetoothSapService( 3917): Stopping SAP server process
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  900):    returned null
E/WifiStateMachine(  900): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  900): doString: DRIVER WLS_BATCHING STOP
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/PMS     (  900): releaseWL(42fe5700): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  900): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  900): Provision feature enable=false
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  900):    returned null
V/BluetoothSapService( 3917): Sap Service closeSapService in
V/BluetoothSapService( 3917): Close listen Socket : 
V/BluetoothSapService( 3917): Close rfcomm Socket : 
V/BluetoothSapService( 3917): Close sapd  Socket : 
,V/BluetoothSapReceiver( 3917): BluetoothSapReceiver deinit
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  900): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  900): isAvailable+-
D/UsbnetStateTracker(  900): reconnect
,D/UsbnetStateTracker(  900): isAvailable+-
,D/WISPrService( 3327): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/WifiStateMachine(  900): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 3327): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/SapServerProfile( 3327): Bluetooth service disconnected
V/BluetoothSapService( 3917): successfully stopped Sap service
V/BluetoothSapService( 3917): Sap Service closeSapService out
I/BtOppRfcommListener( 3917): stopping Accept Thread
,I/BtOppRfcommListener( 3917): BluetoothSocket listen thread finished
D/WifiStateMachine(  900): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WifiP2pService(  900): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
D/MDST    (  900): default: reconnect()
D/MDST    (  900): default: setTeardownRequested(false)
D/MDST    (  900): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  900): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  900): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  900): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  900): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  900): P2pDisablingState
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  900): P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): p2p socket connection lost
D/WifiDisplayController(  900): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  900): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
,D/SapServerProfile( 3745): Bluetooth service disconnected
D/WifiNative-wlan0(  900): doBoolean: DRIVER POWERMODE 0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4009): Power_Mode_Type mode = 0
I/wpa_supplicant( 4009): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 61
V/BluetoothPbapService( 3917): Pbap Service onDestroy
V/BluetoothPbapService( 3917): Pbap Service closeService in
V/BluetoothPbapService( 3917): Pbap Service closeService out
D/WifiNative-wlan0(  900):    returned true
,D/WifiNative-wlan0(  900): doBoolean: DRIVER BTCOEXMODE 2
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/WifiDisplayController(  900): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  900): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  900): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  900): P2pDisabledState
D/WifiP2pService(  900): P2pDisabledState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  900):  WFD CtrlPort: 0
D/WifiP2pService(  900):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  900): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  900): updateConnection
I/WifiDisplayController(  900): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  900): updateConnection enter step 4
D/WifiDisplayAdapter(  900): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  900):     Client/Owner: Client
D/WifiDisplayAdapter(  900):     GroupId: 
D/WifiDisplayAdapter(  900):     Passphrase: 
D/WifiDisplayAdapter(  900):     SessionId: 0
D/WifiDisplayAdapter(  900):     IP Address: }
D/WifiP2pService(  900): DefaultState{ when=-3ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  900):  WFD CtrlPort: 0
D/WifiP2pService(  900):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  900): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  900): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/WifiHW  (  900): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4009): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4009): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  900):    returned true
,V/BluetoothSapService( 3917): onUnbind: android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3917): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b90bb8
V/BluetoothSapService( 3917): Sap Service closeSapService in
V/BluetoothSapService( 3917): Close listen Socket : 
V/BluetoothSapService( 3917): Close rfcomm Socket : 
,V/BluetoothSapService( 3917): Close sapd  Socket : 
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,V/AudioService(  900): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  900):     Client/Owner: Client
V/AudioService(  900):     GroupId: 
V/AudioService(  900):     Passphrase: 
V/AudioService(  900):     SessionId: 0
V/AudioService(  900):     IP Address: }
D/HtcEffectManagerBase(  900): onEventChanged id=5 status=false
D/HtcEffectManager(  900): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  900): convertEffect before=902
W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,D/HtcEffectManager(  900): convertEffect after=902
D/WifiP2pService(  900): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  900): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  900): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiDisplayController(  900): Failed to set WFD info with reason 2.
,V/BluetoothSapService( 3917): Sap Service closeSapService out
,V/BluetoothSapService( 3917): ***onDestroyed***
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-p2p0(  900): doBoolean: TERMINATE
W/WifiHW  (  900): QCOM Debug wifi_send_command "TERMINATE"
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,E/wpa_supplicant( 4009): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 4009): TDLS: Tear down peers
I/wpa_supplicant( 4009): wpa_driver_nl80211_disconnect(reason_code=3)
,D/WifiNative-p2p0(  900):    returned true
W/ConnectivityService(  900): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  900): handleConnectivityChange: resetting
D/ConnectivityService(  900): resetConnections(wlan0, 3)
D/PMS     (  900): acquireWL(42997778): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1335 10028 null
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED disconnected
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/QuickSettingWifi( 1103): receive.wifiConnect:false wifiAPname:null elapse:1
,D/HtcBtWidget_BTWidgetProvider( 4739): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4739): updateWidget(context) for widget: 
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  900): acquireWL(440dd128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  900): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:4   entry:0xb7d9a2c8  removed 
D/WISPrService( 3327): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] entry_id:7   entry:0xb7d9a968  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb7d9a380  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb7d9ad68  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7d9a040  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7d9a0f8  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb7d99e78  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7d9a428  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7d9a1f8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7d9a4f0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
E/WifiStateMachine(  900): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  900): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,D/WISPrService( 3327): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/IntentController( 1103): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
D/PMS     (  900): releaseWL(440dd128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/Nat464Xlat(  900): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  900): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_ICON( 1103): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  900): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  900): acquireWL(43fd0d78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 4009): Clean 'force_connect' when disconnect
I/wpa_supplicant( 4009): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 4009): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  900): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 4009): TDLS: Remove peers on disassociation
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/HTCRequest(  900): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4009): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8a53bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4009):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  900): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 4009): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 4009): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4009): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4009): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  900): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  900): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  900): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 4009): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( ,4009): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  900): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  900): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
I/wpa_supplicant( 4009): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4009): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  900): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/HTCRequest(  900): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  900): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/ConnectivityService(  900): reportInetCondition for net -1, percentage: 0 by  (1335/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  900): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  900): releaseWL(42997778): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/WirelessDisplayService(  900): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  900): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
D/Tethering(  900): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10078)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/QuickSettingWifi( 1103): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  900): releaseWL(43fd0d78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  900): mActiveDefaultNetwork: -1
D/ConnectivityService(  900): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1103): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,D/Process (  900): killProcessQuiet, pid=3745
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4759 uid=10048 gids={50048}
I/ActivityManager(  900): Killing 3745:com.android.settings:remote/1000 (adj 15): empty #17
,E/BluetoothFtpService:RfcommSocketAcceptThread( 3917): Shutdown
,D/BluetoothMasReceiver( 3917): Bluetooth STATE CHANGED to 13
W/bt-btif ( 3917): ag scb idx 1 not allocated
W/bt-btif ( 3917): ag scb idx 2 not allocated
E/bt-btif ( 3917): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3917): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3917): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3917): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3917): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3917): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3917): L2CAP - PSM: 0x0017 not found for deregistration
,D/WifiService(  900): Client connection lost with reason: 4
,I/ActivityManager(  900): Recipient 3745
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3980): Received state change = 13
,I/RemoteViews( 1103): com.google.android.gms (false,0)
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41ed8e20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/GLSActivity( 1335): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1335): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1335): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1335): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1335): 	at dalvik.system.NativeStart.run(Native Method)
,E/bt_userial_mct( 3917): userial_close userial_thread_created userial_running is 1 
,I/RemoteViews.Performance( 1103): com.google.android.gms 1 13 4 12
,I/ActivityManager(  900): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4773 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  900): killProcessQuiet, pid=4337
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  900): Killing 4337:com.htc.task/u0a70 (adj 15): empty #17
,E/PlayEventLogger( 4624): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4624): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4624): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4624): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4624): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4624): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4624): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4624): 	at dalvik.system.NativeStart.run(Native Method)
,D/HtcWiFiWidget_WiFiWidgetProvider( 4759): onWiFiStateChanged() for widget: 
I/ActivityManager(  900): Recipient 4337
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcWiFiWidget_WiFiWidgetProvider( 4759): updateWidget(context) for widget: 
,D/Process (  900): killProcessQuiet, pid=4459
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  900): Killing 4459:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Recipient 4459
,D/libc    ( 4624): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4624): [NET] getaddrinfo-,err=8
D/libc    ( 4624): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4624): [NET] getaddrinfo-, 1
,D/libc    ( 4624): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =feef +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =feef (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=feef, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 4624): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4624): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/Settings:HtcSettingsApplication( 4773): [4773/4773] onCreate()
,D/WifiService(  900): New client listening to asynchronous messages
,E/wpa_supplicant( 4009): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 4009): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 4009): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  900): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/wpa_supplicant( 4009): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4009): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4009): nl80211: Unsubscribe mgmt frames handle 0xb8a54718 (mode change)
I/wpa_supplicant( 4009): htc_wext_command_deinit +
I/wpa_supplicant( 4009): htc_wext_command_deinit -
E/wpa_supplicant( 4009): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 4009): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 4009): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 4009): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 4009): TDLS: Tear down peers
I/wpa_supplicant( 4009): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4009): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4009): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4009): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4009): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4009): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4009): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4009): send_and_recv error 0 - cmd 18
E/WifiStateMachine(  900): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
D/Tethering(  900): interfaceLinkStateChanged wlan0, false
D/Tethering(  900): interfaceStatusChanged wlan0, false
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,D/Process (  900): killProcessQuiet, pid=4472
,I/ActivityManager(  900): Killing 4472:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  900): Recipient 4472
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/WifiStateMachine(  900): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  900): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
,I/wpa_ctrl(  900): [wpa_ctrl_close] ctrl=0x6a297940
I/wpa_ctrl(  900): [wpa_ctrl_close] ctrl=0x6c674338
W/WifiHW  (  900): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  900): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  900): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  900): doBoolean: SET_WIFI_ON 0
,D/WifiNative-wlan0(  900):    returned false
,D/WifiStateMachine(  900): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  900): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  900): WIFI Trun OFF
,D/WirelessDisplayService(  900): getDiscoveryDongleList
,I/IntentController( 1103): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1103): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  900): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  900): Exit handleNetworkDisconnect
,E/WifiStateMachine(  900): [MLHD] Error! unhandled message 6 { when=-133ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/HtcWiFiWidget_WiFiWidgetProvider( 4759): onWiFiStateChanged() for widget: 
,D/PMS     (  900): acquireWL(44113348): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 900 1000 null
D/HtcWiFiWidget_WiFiWidgetProvider( 4759): updateWidget(context) for widget: 
,I/bt-btif ( 3917): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/WifiDataStallTracker(  900): onReceive: action=android.net.wifi.STATE_CHANGE
D/BluetoothAdapterState( 3917): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  900): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  900): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
,D/HeadsetService( 3917): Received stop request...Stopping profile...
,D/WISPrService( 3327): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3327): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothHeadset(  900): Proxy object disconnected
D/BluetoothHeadset( 3327): Proxy object disconnected
D/HeadsetProfile( 3327): Bluetooth service disconnected
,I/QuickSettingWifi( 1103): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
D/BluetoothHeadset( 1214): Proxy object disconnected
D/BluetoothPhoneService( 1214): BluetoothHeadset onServiceDisconnected
,D/BluetoothHeadset( 1214): Proxy object disconnected
D/BluetoothHeadset( 1103): Proxy object disconnected
,I/QuickSettingMiniLite( 1103): btListener.disconnect:HEADSET
D/A2dpService( 3917): Received stop request...Stopping profile...
D/A2dpStateMachine( 3917): doQuit
,D/A2dpStateMachine( 3917): Exit Disconnected: -1
,D/BluetoothA2dp(  900): Proxy object disconnected
D/BluetoothA2dp( 3327): Proxy object disconnected
,D/A2dpProfile( 3327): Bluetooth service disconnected
,D/BluetoothAdapterService( 3917): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HidService( 3917): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 3917): Stopping profile services that were post enabled
D/BluetoothInputDevice( 3327): Proxy object disconnected
W/BluetoothHeadsetServiceJni( 3917): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3917): Cleaning up Bluetooth Handsfree callback object
,D/HidProfile( 3327): Bluetooth service disconnected
,D/HealthService( 3917): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3917): Profile still running: com.android.bluetooth.hdp.HealthService
D/PanService( 3917): Received stop request...Stopping profile...
,D/PanService( 3917): stop
,D/PanService( 3917): stop: mTetherAc send disconnect
,I/QuickSettingWifi( 1103): receive.wifiConnect:false wifiAPname:null elapse:1
,D/BluetoothTethering(  900): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  900): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  900): attempted to stop reverse tether with nothing tethered
D/BluetoothPan(  900): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 3327): BluetoothPAN Proxy object disconnected
,D/PanProfile( 3327): Bluetooth service disconnected
,D/A2dpStateMachine( 3917): cleanup
,D/Avrcp   ( 3917): Unregistering previous receiver
D/BluetoothAdapterService( 3917): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3917): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3917): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 3917): Cleaning up Bluetooth GID callback object
D/BtGatt.DebugUtils( 3917): handleDebugAction() action=null
D/BtGatt.GattService( 3917): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3917): stop()
D/BluetoothAdapterService( 3917): Profile still running: com.android.bluetooth.pan.PanService
,W/BluetoothHealthServiceJni( 3917): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 3917): Cleaning up Bluetooth Health object
D/PanService( 3917): CMD_CHANNEL_DISCONNECTED
D/PanService( 3917): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 3917): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 3917): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3917): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3917): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3917): Setting state to 10
I/BluetoothAdapterState( 3917): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 3917): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  900): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  900): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  900): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,I/BluetoothAdapterState( 3917): Entering OffState
D/BluetoothManagerService(  900): Broadcasting onBluetoothStateChange(false) to 13 receivers.
,D/BluetoothHeadset( 1103): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1214): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1214): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  900): onBluetoothStateChange: up=false
D/BluetoothA2dp(  900): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3327): onBluetoothStateChange: up=false
,D/BluetoothMap( 3327): onBluetoothStateChange: up=false
,E/BluetoothMap( 3327): 
E/BluetoothMap( 3327): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41cecb58
E/BluetoothMap( 3327): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3327): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3327): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3327): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3327): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3327): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3327): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothA2dp( 3327): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3327): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3327): onBluetoothStateChange: up=false
,D/BluetoothSap( 3327): onBluetoothStateChange on: false
,D/BluetoothManagerService(  900): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  900): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 3917): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b56bf0
D/BluetoothDevice( 3917): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 3917): onBluetoothServiceDown: done
D/BluetoothAdapter( 3871): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b57198
,D/BluetoothAdapter( 3871): onBluetoothServiceDown: done
D/BluetoothAdapter( 1402): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41dbcd08
D/BluetoothAdapter( 1402): onBluetoothServiceDown: done
D/BluetoothAdapter(  900): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@423d7cd0
D/BluetoothAdapter(  900): onBluetoothServiceDown: done
D/BluetoothAdapter( 1103): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41f96a20
,D/BluetoothAdapter( 1103): onBluetoothServiceDown: done
D/BluetoothAdapter( 1225): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c78400
D/BluetoothAdapter( 1225): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1214): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41dabda8
,D/BluetoothAdapter( 1214): onBluetoothServiceDown: done
D/BluetoothAdapter( 1736): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@421515a8
,D/BluetoothAdapter( 1736): onBluetoothServiceDown: done
D/BluetoothAdapter( 3980): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b65888
,D/BluetoothAdapter( 3980): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3327): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41cd6be8
,D/BluetoothAdapter( 3327): onBluetoothServiceDown: done
,D/BluetoothManagerService(  900): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@423d7cd0 mBinding = false
,D/BluetoothManagerService(  900): Sending unbind request.
,D/BluetoothManagerService(  900): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService( 3917): Cleaning up adapter native....
,I/bt-btif ( 3917): HAL bt_hal_cbacks->thread_evt_cb
D/NfcHandover( 1225): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,D/LocalBluetoothProfileManager( 3327): setBluetoothStateOff
D/HtcTagManager( 3327): stopProxy
,I/IntentController( 1103): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/PMS     (  900): releaseWL(428fb9a0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BluetoothAdapterService( 3917): Done cleaning up adapter native....
,D/BluetoothAdapterService(1102397568)( 3917): ****onDestroy()********
D/BtGatt.GattService( 3917): cleanup()
W/bt-btif ( 3917): GATTC Module not enabled/already disabled
W/bt-btif ( 3917): GATTS Module not enabled/already disabled
D/BluetoothMasReceiver( 3917): Bluetooth STATE CHANGED to 10
W/BluetoothHeadset( 1103): Proxy not attached to service
I/QuickSettingMiniLite( 1103): updateLiteState:no connect device!
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3980): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b64fb8
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3980): deinitLeServices: null
V/BluetoothMasService( 3917): onDestroy: mIsEmailEnabled: true
,D/TetherPref( 3327): persistRestoreBluetoothState false
D/PMS     (  900): acquireWL(43fcb368): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3327 1000 null
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/HtcBtWidget_BTWidgetProvider( 4739): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4739): updateWidget(context) for widget: 
D/PMS     (  900): releaseWL(43fcb368): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  900): acquireWL(43fcb2c8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3327 1000 null
,D/DockEventReceiver( 3327): finishStartingService: stopping service
D/PMS     (  900): releaseWL(43fcb2c8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothAdapter( 1103): 1105110128: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1103): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/BluetoothMasReceiver( 3917): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3980): Received state change = 10
,W/System.err(  900): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  900): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a00418:true
,W/System.err(  900): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  900): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  900): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  900): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  900): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4773): new LocationAgent instance!!
,D/HtcTagManager( 4773): HtcTagManager construction complete
,D/BluetoothAdapter( 4773): 1102383208: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 4773): BluetoothInputDevice()
,D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4773): 1102383208: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4773): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4773): Bluetooth service connected
D/BluetoothManagerService(  900): Registered receivers: 14
W/BluetoothInputDevice( 4773): Proxy not attached to service
,D/BluetoothPan( 4773): BluetoothPan()
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 15
D/BluetoothAdapter( 4773): 1102383208: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 4773): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 4773): Bluetooth service connected
D/BluetoothMap( 4773): Create BluetoothMap proxy object
,D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  900): Registered receivers: 16
E/BluetoothMap( 4773): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 17
,D/BluetoothSap( 4773): BluetoothSap() call bindService
,W/ContextImpl( 4773): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 4773): BluetoothPbap()
D/BluetoothManagerService(  900): registerStateChangeCallback+
D/BluetoothManagerService(  900): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  900): Registered receivers: 18
D/BluetoothAdapter( 4773): 1102383208: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4773): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4773): Bluetooth service connected
D/LocalBluetoothProfileManager( 4773): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 4773): 1102383208: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4773): 1102383208: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4773): setBluetoothStateOff
D/HtcTagManager( 4773): stopProxy
W/BluetoothEventManager( 4773): unregister mProfileBroadcastReceiver fail
,D/Process (  900): killProcessQuiet, pid=4407
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  900): Killing 4407:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4407
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  900): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  900): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  900): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  900): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4792 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Tethering(  900): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  900): bSetPropertyMultiRAB:false
,D/Tethering(  900): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  900): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  900): ipv4Default null
I/Tethering(  900): No IPv4 upstream interface, giving up.
,D/Tethering(  900): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  900): DelayedCaptiveCheckState
D/GpsLocationProvider(  900): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  900): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  900): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  900): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  900): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by  (900/1000)
D/PMS     (  900): acquireWL(43ad1190): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 900 1000 null
D/PMS     (  900): releaseWL(43ad1190): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1754/1000)
,D/CaptivePortalTracker(  900): NoActiveNetworkState
D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  900): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1242): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1402/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10078)
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.htc.launcher (1242/10075)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,I/MusicStore( 4792): Database version: 95
,W/ContextImpl( 4792): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/Netd    (  364): No subsystem found in netlink event
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,V/Tethering(  900): remove iface:wlan0
D/Tethering(  900): interfaceRemoved wlan0
,E/Tethering(  900): attempting to remove unknown iface (wlan0), ignoring
,W/ContextImpl( 4792): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4792): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4792): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4792): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4792, uid=10154, userID:0
,D/WifiDisplayAdapter(  900): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  900):     Client/Owner: Client
D/WifiDisplayAdapter(  900):     GroupId: 
D/WifiDisplayAdapter(  900):     Passphrase: 
D/WifiDisplayAdapter(  900):     SessionId: 0
D/WifiDisplayAdapter(  900):     IP Address: }
,D/MediaRouterService(  900): Client com.google.android.music (pid 4792): Registered
,D/WifiDisplayAdapter(  900): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  900):     Client/Owner: Client
D/WifiDisplayAdapter(  900):     GroupId: 
D/WifiDisplayAdapter(  900):     Passphrase: 
D/WifiDisplayAdapter(  900):     SessionId: 0
D/WifiDisplayAdapter(  900):     IP Address: }
,I/MediaRouter( 4792): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (2204/10021)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.music (4792/10154)
,I/ActivityManager(  900): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4812 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4792): getSelectedRoute
D/Tethering(  900): interfaceLinkStateChanged p2p0, false
,D/Tethering(  900): interfaceStatusChanged p2p0, false
,D/Tethering(  900): [isWifi] getHotspotEnabled: false
,I/NetworkMonitor( 4792): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  900): getNetworkInfo networkType=1 called by com.google.android.music (4792/10154)
,D/ACRA    ( 4812): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  900): killProcessQuiet, pid=4559
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4792, uid=10154, userID:0
,I/ActivityManager(  900): Killing 4559:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ACRA    ( 4812): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4812): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/ActivityManager(  900): Recipient 4559
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Netd    (  364): No subsystem found in netlink event
,V/Tethering(  900): remove iface:p2p0
,D/Tethering(  900): interfaceRemoved p2p0
,E/Tethering(  900): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,W/SystemClassLoaderAdder( 4812): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4812): Preparing secondary program dexes.
V/DexLibLoader( 4812): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4812): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4812): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4812): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4812): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4812): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4812): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4812): Dex already copied
D/OdexVerifier( 4812): Odex verification is skipped.
,V/DexLibLoader( 4812): Creating class loader
,V/DexLibLoader( 4812): Finished creating class loader
V/DexLibLoader( 4812): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4812): Dex already copied
D/OdexVerifier( 4812): Odex verification is skipped.
,V/DexLibLoader( 4812): Creating class loader
,V/DexLibLoader( 4812): Finished creating class loader
V/DexLibLoader( 4812): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4812): Dex already copied
D/OdexVerifier( 4812): Odex verification is skipped.
,V/DexLibLoader( 4812): Creating class loader
,V/DexLibLoader( 4812): Finished creating class loader
V/DexLibLoader( 4812): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4812): Dex already copied
D/OdexVerifier( 4812): Odex verification is skipped.
,V/DexLibLoader( 4812): Creating class loader,
V/DexLibLoader( 4812): Finished creating class loader
,V/DexLibLoader( 4812): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4812): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4812): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4812): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4812): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4812): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4812): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4812): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4812): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  900): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  900): [MLHD] Error! unhandled message 1 { when=-1s814ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  900): releaseWL(44113348): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,W/dalvikvm( 4812): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4812): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4812): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4812): Verify
,D/WifiService(  900): New client listening to asynchronous messages
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4812): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4812): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4812): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  900): killProcessQuiet, pid=4581
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  900): Killing 4581:com.google.android.setupwizard/u0a78 (adj 15): empty #17
D/PMS     (  900): acquireWL(423b2e60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1193 10028 null
I/ActivityManager(  900): Recipient 4581
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  900): acquireWL(4312a9c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1193 10028 null
D/PMS     (  900): releaseWL(423b2e60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,D/PMS     (  900): releaseWL(4312a9c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1335): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  900): getActiveNetworkInfo called by  (1335/10028)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,D/AutoSetting( 4203): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  900): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4835 uid=10078 gids={50078, 3003, 5012}
,W/fb4a(:<default>):UserScope( 4812): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4812): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutoSetting( 4203): Util - no network available!
,D/AutoSetting( 4203): service - onCreate()
D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (4203/10053)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.htc.sense.hsp (4203/10053)
W/fb4a(:<default>):UserScope( 4812): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/AutoSetting( 4203): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  900): request 42579560 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/AutoSetting( 4203): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  900): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4203): service - mHandler: cancel location update
D/AutoSetting( 4203): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4835): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4835): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4835): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4835): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  900): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4851 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4835/10078)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4835/10078)
,E/dalvikvm( 4812): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4812): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4812): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4812): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4812): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4812): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.setupwizard (4835/10078)
E/dalvikvm( 4812): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4812): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4812): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4812): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4812): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4812): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4812): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4812): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4812): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4812): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4812): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4812): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4812): Grow heap (frag case) to 9.923MB for 39954-byte allocation
,I/ActivityManager(  900): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4864 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  900): killProcessQuiet, pid=4489
,I/ActivityManager(  900): Killing 4489:com.google.android.configupdater/u0a16 (adj 15): empty #17
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/dalvikvm-heap( 4812): Grow heap (frag case) to 10.000MB for 79892-byte allocation
I/ActivityManager(  900): Recipient 4489
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4812): Grow heap (frag case) to 10.062MB for 84664-byte allocation
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4864): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4864): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/GAV2    ( 4864): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4864): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4812): Grow heap (frag case) to 10.087MB for 28144-byte allocation
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4864): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/PMS     (  900): acquireWL(441fc0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(441fc0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4864/10151)
I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
V/WebViewChromiumFactoryProvider( 4864): Binding Chromium to main looper Looper (main, tid 1) {41b42fa8}
I/LibraryLoader( 4864): Expected native library version number "",actual native library version number ""
I/chromium( 4864): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4864): Initializing chromium process, renderers=0
,I/dalvikvm-heap( 4812): Grow heap (frag case) to 10.274MB for 75760-byte allocation
,E/AudioManagerAndroid( 4864): BLUETOOTH permission is missing!
D/PMS     (  900): acquireWL(43de6660): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  900): acquireWL(42016768): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  900): releaseWL(43de6660): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4864): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4864): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4864): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4864): Local Branch: 
I/Adreno-EGL( 4864): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4864): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4864):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
W/BroadcastQueue(  900): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4401a650 u0 ReceiverList{43fd5d38 4812 com.facebook.katana/10026/u0 remote:43a21460}}
W/BroadcastQueue(  900): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4401a650 u0 ReceiverList{43fd5d38 4812 com.facebook.katana/10026/u0 remote:43a21460}}
W/BroadcastQueue(  900): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42ff9b78 u0 ReceiverList{427bebd0 4812 com.facebook.katana/10026/u0 remote:425d2678}}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,I/NSApplication( 4864): Starting up...
D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4864/10151)
D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.magazines (4864/10151)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (3654/10160)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.apps.plus (3654/10160)
,D/Process (  900): killProcessQuiet, pid=4682
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  900): Killing 4682:com.htc.updater/u0a84 (adj 15): empty #17
D/ConnectivityService(  900): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1736/10178)
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  900): Recipient 4682
D/PMS     (  900): acquireWL(4445aff8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
,D/PMS     (  900): acquireWL(42b76158): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
,D/PMS     (  900): releaseWL(4445aff8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1402): Unknown pending intent to remove.
D/PMS     (  900): releaseWL(42b76158): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4812): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4812): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4812): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService(  900): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  900): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
,D/PMS     (  900): releaseWL(42016768): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  900): acquireWL(43f71478): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4792 10154 null
,W/ContextImpl( 4792): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4792): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4792, uid=10154, userID:0
,I/MusicLeanback( 4792): Conditions not met for autocaching.
,I/MusicLeanback( 4792): Stop autocaching.
D/PMS     (  900): releaseWL(43f71478): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  900): acquireWL(443445f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=435447, Int=0
I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(443445f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,W/fb4a(:<default>):UserScope( 4812): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4812): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4812): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.facebook.katana (4812/10026)
,I/GAV2    ( 4864): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  900): acquireWL(43d6b070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
,D/PMS     (  900): acquireWL(4263cf00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1402 10028 null
,D/PMS     (  900): releaseWL(43d6b070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  900): releaseWL(4263cf00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiStateMachine(  900): startScan Pid: 900 Uid 1000
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{43a0f740 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/WirelessDisplayService(  900): HANDLE_WIFI_DIS
,D/WirelessDisplayService(  900): HANDLE_STOP_DIS
,D/WirelessDisplayService(  900): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  900): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1
D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/AutoSetting( 4203): service - handleMessage() stop self
,D/AutoSetting( 4203): service - handleMessage() quit looper
,D/AutoSetting( 4203): service - onDestroy() END
,D/PMS     (  900): acquireWL(427e5b78): PARTIAL_WAKE_LOCK  Icing 0x1 1193 10028 null
,D/PMS     (  900): releaseWL(427e5b78): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  900): acquireWL(4446d260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=470387, Int=120000
,D/PMS     (  900): releaseWL(4446d260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(44450710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(44450710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/PowerUI ( 1103): closing low battery warning: level=100
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  900): Killing 4624:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  900): killProcessQuiet, pid=4624
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  900): Recipient 4624
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  900): releaseWL(42f35ae0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  900): NetTransition Wakelock for ConnectedState released by timeout
,D/PMS     (  900): acquireWL(43b499b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43b499b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  900): acquireWL(430e3028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=495447, Int=0
,D/PMS     (  900): releaseWL(430e3028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  900): acquireWL(4309adb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,D/PMS     (  900): releaseWL(4309adb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  900): acquireWL(42de22e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42de22e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42caa690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=555447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42caa690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42c71db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=590387, Int=120000
,D/PMS     (  900): releaseWL(42c71db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(42baa4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42baa4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  900): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
,D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(425878f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(425878f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  900): acquireWL(423ce140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=615447, Int=0
,D/PMS     (  900): releaseWL(423ce140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1214): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1214): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1214): sku_id=99
,D/ContactMessageStore( 1214): start background delete task...
,D/ContactMessageStore( 1214): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1214): size: 0 , 0
,D/ContactMessageStore( 1214): Background delete complete
,D/PMS     (  900): acquireWL(42536328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1103): closing low battery warning: level=98
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  900): batLight: plugged
V/LightsService(  900): setLight #8: color=#c8c800
,D/DotMatrix( 1523): [EventService] reorderNotification, total:1
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c80000
D/qdlights(  900): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): releaseWL(42536328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
,I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,I/ActivityManager(  900): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4932 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1103): status:2 level:98 unsupport:false plugged:true
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,W/ContextImpl( 4932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3327): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3327): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3327): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3327): Cust_ConnectToPC   : spcsc>false
D/        ( 3327): Cust_ConnectToPC   : IPT>true
,D/        ( 3327): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3327): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3327): Index of the first 1 = -1
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3327): hasRemovableStorageSlot: true
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3327): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3327): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3327): [ACC]android_networking:tethering_guard_support=false
,D/Process (  900): killProcessQuiet, pid=4301
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  900): Killing 4301:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4301
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  900): acquireWL(42361210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42361210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42122488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=675447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42122488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(4260f2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4260f2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PMS     (  900): runPSCheck
D/PowerUI ( 1103): closing low battery warning: level=98
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(42581a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
,I/BatteryService(  900): n_update end
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): releaseWL(42581a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=98
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(424de360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=735447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(424de360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(420cb258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(420cb258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=98
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
,I/HtcPowerSaver(  900): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(4204f090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710387, Int=120000
,I/ActivityManager(  900): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=4948 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,V/AlarmManager(  900): sending alarm PendingIntent{42453df8: PendingIntentRecord{42390e88 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449746901668, Int=0
,D/PMS     (  900): releaseWL(4204f090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4948, uid=10073, userID:0
,D/Finsky  ( 4948): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  900): getAllNetworkInfo called by com.android.vending (4948/10073)
,D/ConnectivityService(  900): getAllNetworkInfo called by com.android.vending (4948/10073)
,D/Finsky  ( 4948): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4948): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4948): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  900):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4948, uid=10073, userID:0
,D/Finsky  ( 4948): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4948): [1] 2.run: Finished loading 1 libraries.
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,D/Finsky  ( 4948): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Finsky  ( 4948): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4948): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4948): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/PMS     (  900): acquireWL(4264e078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10073}
,V/AlarmManager(  900): sending alarm PendingIntent{42631df0: PendingIntentRecord{42390e88 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449746902980, Int=0
,D/PMS     (  900): releaseWL(4264e078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4948): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4948): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4948): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4948): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4948): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/Process (  900): killProcessQuiet, pid=4710
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4710:com.htc.aurora/u0a47 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4710
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4948): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4948): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4948): [1] DailyHygiene.reschedule: Scheduling new run in 92 minutes (failures=3)
,D/PMS     (  900): acquireWL(4344bfa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10073}
,V/AlarmManager(  900): sending alarm PendingIntent{4311f6d0: PendingIntentRecord{43dfa220 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449746918162, Int=0
,D/PMS     (  900): releaseWL(4344bfa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4948): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  900): acquireWL(43dd72a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,D/ConnectivityService(  900): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  900): sending alarm PendingIntent{41e78800: PendingIntentRecord{4246ff60 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781927, Int=0
,D/PMS     (  900): releaseWL(43dd72a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): Done.
,D/ConnectivityService(  900): Setting timer for 720seconds
,D/PMS     (  900): acquireWL(43fcddd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): releaseWL(43fcddd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  900): updateBatteryInfo
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=98
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43316bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=795447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43316bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43f581a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43f581a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42fec7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=855446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42fec7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(43a18780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=830387, Int=120000
,V/AlarmManager(  900): sending alarm PendingIntent{4211ff00: PendingIntentRecord{41c534d0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449747000130, Int=1800000
,D/PMS     (  900): acquireWL(42dcac78): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1193 10028 null
,D/PMS     (  900): releaseWL(43a18780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  900): acquireWL(43fd6948): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1193 10028 null
,I/EventLogService( 1193): Aggregate from 1449746290060 (log), 1449745200075 (data)
D/PMS     (  900): releaseWL(42dcac78): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PMS     (  900): releaseWL(43fd6948): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  900): acquireWL(441600b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/PMS     (  900): releaseWL(441600b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=99
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  900): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  900): << updateStatus
,W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  900): acquireWL(43cd0ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43cd0ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(43cc4288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=915446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43cc4288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42ee2bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42ee2bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42dc6f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=975447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42dc6f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42ecddc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=950387, Int=120000
,V/AlarmManager(  900): sending alarm PendingIntent{4254c1b0: PendingIntentRecord{425ede90 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449747085037, Int=900000
,V/AlarmManager(  900): sending alarm PendingIntent{42390088: PendingIntentRecord{424fd700 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449747157086, Int=0
,W/ContextImpl( 4932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4932): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4932): MY_DEBUG = false
,D/SmartSyncUtils( 4932): isEpsOn(), nState = 0
D/PMS     (  900): acquireWL(42ddcd00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4932 1000 null
,D/PMS     (  900): releaseWL(42ecddc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/PMS     (  900): releaseWL(42ddcd00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  900): acquireWL(42e2c398): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4932 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4932): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4932): [updateNmRange] USERNIGHT_TIMESTART = 18, USERNIGHT_TIMEEND = 21, nStart = 18, nEnd = 21, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4932): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4932): SettingOnTime = 1449777600000, randomSettingOnTime = 1449775295000
D/SmartSyncScreenOnOffTimeReceiver( 4932): SettingOffTime = 1449766800000, randomSettingOffTime = 1449770418000
,D/SmartSyncScreenOnOffTimeReceiver( 4932): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4932): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4932): bNightModeTurnOffOnce = false
,D/PMS     (  900): releaseWL(42e2c398): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/PMS     (  900): acquireWL(44450710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(44450710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(443f1ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1035446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(443f1ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  900): killProcessQuiet, pid=4759
,D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4759:com.htc.widget.process2/u0a48 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 4759
,I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  900): acquireWL(44043b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(44043b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  900): updateBatteryInfo
,D/DotMatrix( 1523): [EventService] reorderNotification, total:0
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  900): BroadcastReceiver::onReceive+
D/UsbnetService(  900): onReceive BATTERY_CHANGED
D/UsbnetService(  900):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  900): BroadcastReceiver::onReceive-
D/PowerUI ( 1103): closing low battery warning: level=100
V/NotificationService(  900): batLight: Full, plugged
V/LightsService(  900): setLight #8: color=#c8c800
D/qdlights(  900): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  900): setLight #8: color=#c800
D/qdlights(  900): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  900): [LedInfo] has indicator attribute
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  900): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  900): runPSCheck
D/HtcPowerSaver(  900): Checking...
I/HtcPowerSaver(  900): >> updateStatus
W/ContextImpl( 4932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  900): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  900): << updateStatus
,D/TetherSettings( 3327): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3327): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3327): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3327): Cust_ConnectToPC   : spcsc>false
D/        ( 3327): Cust_ConnectToPC   : IPT>true
,D/        ( 3327): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3327): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3327): Index of the first 1 = -1
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3327): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3327): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3327): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  900): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1335): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1335): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1335): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1335): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1335): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1103): com.google.android.gms (false,0)
D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 4948): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4948): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4948): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4948): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4948): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{42078530 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.google.android.gms 3 11 2 12
,D/libc    ( 4948): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4948): [NET] getaddrinfo-,err=8
D/libc    ( 4948): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4948): [NET] getaddrinfo-, 1
,D/libc    ( 4948): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =34e7 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =34e7 (# 1) address = 192.168.1.1 (try=2,nscount=1),
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=34e7, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 4948): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4948): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  900): acquireWL(430a4b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1070387, Int=120000
,D/PMS     (  900): releaseWL(430a4b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(4309adb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4309adb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(43013fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1095446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(43013fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42ffb1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42ffb1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42ff4fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1155446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42ff4fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42ff49e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1190387, Int=120000
,D/PMS     (  900): releaseWL(42ff49e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(42ff46e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42ff46e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  900): acquireWL(42f7f1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1215446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42f7f1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42f2e968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42f2e968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42ecd970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1275447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42ecd970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42e73898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1310387, Int=120000
,D/PMS     (  900): releaseWL(42e73898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(42e32488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42e32488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42e19810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1335447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42e19810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1335): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1335): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1335): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1335): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1335): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4948): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4948): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4948): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4948): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4948): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    ( 4948): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4948): [NET] getaddrinfo-,err=8
D/libc    ( 4948): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4948): [NET] getaddrinfo-, 1
,D/libc    ( 4948): [NET] getaddrinfo_proxy+
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ab51 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =ab51 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=ab51, total retry = 3 times, errno=111,v_circuit=0-----
,D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 4948): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4948): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{420a5ae0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress},
,I/RemoteViews.Performance( 1103): com.google.android.gms 2 24 6 12
,D/PMS     (  900): acquireWL(42117ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42117ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42068d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1395446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42068d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(4248cd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41e38b30: PendingIntentRecord{424c47b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1419452, Int=0
,D/PMS     (  900): acquireWL(4243bee0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 900 1000 null
,D/PMS     (  900): releaseWL(4248cd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  900): getActiveNetworkInfo called by  (900/1000)
,D/PMS     (  900): acquireWL(42383e90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 900 1000 null
,D/PMS     (  900): releaseWL(4243bee0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  900): releaseWL(42383e90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  900): acquireWL(42512790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1430387, Int=120000
,D/PMS     (  900): releaseWL(42512790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(423222f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(423222f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(4211f1f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1455446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4211f1f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(430055f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(430055f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42b9d8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1515446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42b9d8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(4244a268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1550387, Int=120000
,D/PMS     (  900): releaseWL(4244a268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(43925d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43925d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42f75450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1575447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42f75450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42630f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42630f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(425b2cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1635447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(425b2cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,W/GLSActivity( 1335): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1335): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1335): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1335): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1335): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41b95380 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4948): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4948): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4948): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4948): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4948): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4948): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1103): com.google.android.gms 4 11 4 12
,D/libc    ( 4948): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4948): [NET] getaddrinfo-,err=8
D/libc    ( 4948): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4948): [NET] getaddrinfo-, 1
,D/libc    ( 4948): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =941d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =941d (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=941d, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 4948): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4948): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  900): acquireWL(42511798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1670387, Int=120000
,D/PMS     (  900): releaseWL(42511798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  900): acquireWL(4211d990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(4211d990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42de9d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1695447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42de9d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42579ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42579ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(42441910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1755447, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(42441910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/PMS     (  900): acquireWL(43c0bdf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(43c0bdf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  900): acquireWL(430e1d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1815446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(430e1d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(42ff99c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{41e78800: PendingIntentRecord{4246ff60 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1501946, Int=0
,D/ConnectivityService(  900): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  900): Done.
,D/ConnectivityService(  900): Setting timer for 720seconds
,I/ProcessStatsService(  900): Prepared write state in 52ms
,I/ProcessStatsService(  900): Prepared write state in 30ms
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1790387, Int=120000
,V/AlarmManager(  900): sending alarm PendingIntent{423d4de8: PendingIntentRecord{42537b00 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820854, Int=1800000
V/AlarmManager(  900): sending alarm PendingIntent{428824d0: PendingIntentRecord{42c2b828 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1853842, Int=0
,V/AlarmManager(  900): sending alarm PendingIntent{4254c1b0: PendingIntentRecord{425ede90 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449747985037, Int=900000
,D/PMS     (  900): acquireWL(439f03a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 900 1000 null
,D/PMS     (  900): releaseWL(439f03a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ProcessStatsService(  900): Pruning old procstats: /data/system/procstats/state-2015-12-09-17-15-16.bin
,W/ContextImpl( 4932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  900): releaseWL(42ff99c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/ConnectivityService(  900): getActiveNetworkInfo called by com.google.android.gms (1193/10028)
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,W/BatSI   (  900): Couldn't get kernel wake lock stats
,D/PMS     (  900): acquireWL(42597b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  900): n_update end
,D/PMS     (  900): releaseWL(42597b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  900): acquireWL(4263bfc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{1000}
,V/AlarmManager(  900): sending alarm PendingIntent{423c6d28: PendingIntentRecord{41e9e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1875446, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  900): releaseWL(4263bfc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  900): acquireWL(4262dac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 900 1000 WorkSource{10026}
,V/AlarmManager(  900): sending alarm PendingIntent{4208ece0: PendingIntentRecord{43c0c030 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1910387, Int=120000
,D/PMS     (  900): releaseWL(4262dac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5015): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5015): ====startRecUseTime====
D/htc.customization.log.level( 5015):  is 
W/CustomizationLogLevel( 5015): Level value is invalid, use default level 2
D/CustomizationManager( 5015):  Read ACC file spent 0.097 (s)
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5015): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5015): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5015): Parsing tag category name = system
I/CustomizationCIDLoader( 5015): Parsing tag category name = application
I/CustomizationCIDLoader( 5015): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5015): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5015): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5015): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5015): Parsing tag category name = Settings
D/CustomizationManager( 5015):  Read CID file spent 0.151 (s)
D/CustomizationManager( 5015):  All configurations done spent 0.151 (s)
W/HtcNativeFlag( 5015): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5015): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5015): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5015): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  900): deletePackageAsUser: pkg=com.test.thalitest, pid=5015, uid=2000 user=0
I/ActivityManager(  900): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  900): killProcessQuiet, pid=3871
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  900): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  900): Killing 3871:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  900):   Force finishing activity ActivityRecord{41b33418 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  900): Copying FileAsset 0x6784d8c8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  900): WIN DEATH: Window{4248dee8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  900): Client connection lost with reason: 4
W/InputMethodManagerService(  900): Got RemoteException sending setActive(false) notification to pid 3871 uid 10348
W/Binder  ( 1178): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1178): java.lang.NullPointerException
W/Binder  ( 1178): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1178): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1178): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1178): 	at dalvik.system.NativeStart.run(Native Method)
W/PackageSettings(  900): Skipping PackageSetting{42282e38 com.example.hello/10355} due to missing metadata
I/ActivityManager(  900): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1523): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1523): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1754): Unregistering com.test.thalitest
E/acms    ( 1754): Could not unregister removed application com.test.thalitest
I/Launcher( 1242): Deferring update until onResume
D/Launcher( 1242): waitUntilResume // bindAppsRemoved
D/PMS     (  900): acquireWL(44450710): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1402 10028 null
W/GeofencerStateMachine( 1402): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1300): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1300): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  900): releaseWL(44450710): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1268): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "sms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
D/AccTypeManager( 1300): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "smsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mmsto"
D/PackageBroadcastService( 1193): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "sms"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/ActivityManager(  900): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5034 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1300): Unsupported attribute readOnly
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "smsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mms"
I/PackageManager(  900):   Action: "android.intent.action.SENDTO"
I/PackageManager(  900):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  900):   Scheme: "mmsto"
I/PackageManager(  900): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
D/PhoneApp( 1214): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  900): Delaying start of: ServiceRecord{42f94448 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 5034): install
I/MultiDex( 5034): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5034): loading existing secondary dex files
I/MultiDex( 5034): load found 1 secondary dex files
I/ActivityManager(  900): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5053 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 5034): install done
I/PeopleContactsSync( 1193): CP2 sync disabled
I/PackageManager(  900):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1193, uid=10028, userID:0
I/Icing   ( 1193): doRemovePackageData com.test.thalitest
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.user._i.e66c36715ed1937e
D/PMS     (  900): acquireWL(4208d8b0): PARTIAL_WAKE_LOCK  Icing 0x1 1193 10028 null
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1193): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1193): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1193): Writing status failed
D/PMS     (  900): releaseWL(4208d8b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 5034): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 5053): install
I/MultiDex( 5053): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  900): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 5053): loading existing secondary dex files
I/MultiDex( 5053): load found 1 secondary dex files
I/MultiDex( 5053): install done
E/SQLiteDatabase( 1193): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1193): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1193): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1193): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1193): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1193): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1193): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1193): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1193): Runtime exception while performing operation
E/ClearPendingStateOp( 1193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1193): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1193): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1193): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1193): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1193): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1193): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ProviderInstaller( 5053): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
F/ClearPendingStateOp( 1193): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1193): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1193): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1193): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1193): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1193): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1193): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1193): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  900): Resuming delayed broadcast
E/DropBoxManagerService(  900): Can't write: system_app_wtf
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
E/SharedPreferencesImpl( 1178): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 4203): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/Prism.PackageStateRece_( 1242): action: android.intent.action.PACKAGE_REMOVED
E/SQLiteLog( 4203): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 4203): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca63838
W/[PluginManager]RegisterService( 4203): provider may killed!
W/[PluginManager]RegisterService( 4203): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 4203): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 4203): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 4203): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 4203): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 4203): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 4203): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 4203): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4203): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4203): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4203): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4203): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4203): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4203): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4203): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/InputMethodManagerService(  900): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2658): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/[PluginManager]RegisterService( 4203): handle notify Blinkfeed plugin client changed
I/ActivityManager(  900): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  900): Resuming delayed broadcast
D/Process (  900): killProcessQuiet, pid=4739
D/Process (  900): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  900): Killing 4739:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
I/ActivityManager(  900): Recipient 4739
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5076 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2658): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2658): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5cae5b90
W/dalvikvm( 2658): threadid=14: thread exiting with uncaught exception (group=0x4170ce30)
E/ActivityManager(  900): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2658): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2658): Process: com.google.android.googlequicksearchbox:search, PID: 2658
E/AndroidRuntime( 2658): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2658): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2658): 	at cid.d(PG:186)
E/AndroidRuntime( 2658): 	at clo.g(PG:594)
E/AndroidRuntime( 2658): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2658): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2658): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2658): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2658): 	at clr.tL(PG:827)
E/AndroidRuntime( 2658): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2658): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2658): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2658): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2658): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2658): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2658): killProcess, pid=2658
D/Process ( 2658): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop151.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
E/SQLiteDatabase( 5034): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 5034): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5034): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5034): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5034): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 5034): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 5034): 	at ctn.run(SourceFile:985)
W/dalvikvm( 5034): threadid=12: thread exiting with uncaught exception (group=0x4170ce30)
E/ActivityManager(  900): App crashed! Process: com.google.android.gms.drive
D/Process ( 5034): killProcess, pid=5034
E/AndroidRuntime( 5034): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5034): Process: com.google.android.gms.drive, PID: 5034
E/AndroidRuntime( 5034): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5034): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5034): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5034): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 5034): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 5034): 	at ctn.run(SourceFile:985)
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop152.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
D/Process ( 5034): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  900): Recipient 5034
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.google.android.gms.drive (pid 5034) has died.
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  900): Recipient 2658
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.google.android.googlequicksearchbox:search (pid 2658) has died.
D/MediaRouterService(  900): Client com.google.android.googlequicksearchbox (pid 2658): Died!
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/WifiService(  900): Client connection lost with reason: 4
W/ActivityManager(  900): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
E/SQLiteDatabase( 5076): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5076): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5076): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5076): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5076): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5076): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5076): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5076): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5076): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5076): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5076): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5076): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5076): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5076): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5076): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5076): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5076): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5076): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5076): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5076): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5076): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5076): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5076): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5076): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5076): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5076): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5076): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5076): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5076): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5076): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5076): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5076): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5076): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5076): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5076): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5076): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5076): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5076): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5076): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5076): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5076): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5076): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5076): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5076): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5076): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5076): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5076): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5076): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5076): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5076): threadid=11: thread exiting with uncaught exception (group=0x4170ce30)
E/ActivityManager(  900): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5076): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5076): Process: com.google.android.apps.docs, PID: 5076
E/AndroidRuntime( 5076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5076): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5076): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5076): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5076): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5076): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5076): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  900): Can't write: system_app_crash
E/DropBoxManagerService(  900): java.io.FileNotFoundException: /data/system/dropbox/drop153.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  900): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  900): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  900): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  900): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  900): 	... 5 more
D/Process ( 5076): killProcess, pid=5076
D/Process ( 5076): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  900): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5094 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  900): Recipient 5076
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  900): Process com.google.android.apps.docs (pid 5076) has died.
W/PackageManager(  900): Unable to load service info ResolveInfo{43113620 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  900): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  900): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  900): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  900): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  900): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  900): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  900): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  900): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  900): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  900): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  900): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 5094): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  900): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5107 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5094): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5094): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5094): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5094): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5094): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5094): threadid=10: thread exiting with uncaught exception (group=0x4170ce30)
E/AndroidRuntime( 5094): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5094): Process: com.android.keychain, PID: 5094
E/AndroidRuntime( 5094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5094): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5094): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5094): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5094): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  900): App crashed! Process: com.android.keychain
D/ErrorReport(  900): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5094): killProcess, pid=5094
D/Process ( 5094): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  900): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  900): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449748058043.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  900): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  900): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  900): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  900): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  900): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  900): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  900): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  900): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  900): 	... 4 more
I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1242): loadItems() com.htc.launcher.pageview.WidgetManager@41bceed0 +
I/Prism.WidgetManager( 1242): onLoadItems() +
I/ActivityManager(  900): Recipient 5094
I/ActivityManager(  900): Process com.android.keychain (pid 5094) has died.
I/DisplayManagerService(  900): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  900): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10346ms
D/AppTag  ( 5107): getInstance(Context context)

```
