#### Test 506502789252e15_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  903): acquireWL(42dcc588): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  903): releaseWL(42dcc588): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  903): acquireWL(429fb068): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  903): releaseWL(429fb068): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  903): acquireWL(42ee32c0): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  903): releaseWL(42ee32c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  903): acquireWL(42aeeb58): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  903): releaseWL(42aeeb58): PARTIAL_WAKE_LOCK  Icing 0x1 null
,--------- beginning of /dev/log/main
E/cutils-trace( 3840): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3840): ====startRecUseTime====
D/htc.customization.log.level( 3840):  is 
W/CustomizationLogLevel( 3840): Level value is invalid, use default level 2
D/CustomizationManager( 3840):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3840): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3840): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3840): Parsing tag category name = system
I/CustomizationCIDLoader( 3840): Parsing tag category name = application
I/CustomizationCIDLoader( 3840): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3840): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3840): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3840): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3840): Parsing tag category name = Settings
D/CustomizationManager( 3840):  Read CID file spent 0.088 (s)
D/CustomizationManager( 3840):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 3840): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3840): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3840): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3840): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3840
D/PMS     (  903): acquireHCC(424caad0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(42cb4958): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
W/asset   (  903): Copying FileAsset 0x62c2bdd0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1123044856
I/FeedHostManager( 1245): [onPause]
I/FeedProviderManager( 1245): onPause
I/FeedHostManager( 1245): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@424f2728
I/SocialFeedProvider( 1245): +onPause
I/SocialFeedProvider( 1245): -onPause
D/PMS     (  903): acquireWL(428dfdb8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3851 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1245): [trimMemory] 20
W/asset   ( 3851): Copying FileAsset 0x5c89c428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3851): Binding Chromium to main looper Looper (main, tid 1) {424d6740}
I/LibraryLoader( 3851): Expected native library version number "",actual native library version number ""
I/chromium( 3851): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3851): Initializing chromium process, renderers=0
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43f02078:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3851): 1112457592: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  903): acquireWL(42ee96e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): acquireWL(42dce950): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): releaseWL(42dce950): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3851): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3851): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3851): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3851): Local Branch: 
I/Adreno-EGL( 3851): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3851): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3851):                  aa63bbd948f41d15fc72f585e
W/chromium( 3851): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3851): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3851): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3851): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3851): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3851): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3851): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3851): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3851): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3851): CordovaWebView is running on device made by: HTC
,W/AwContents( 3851): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Disable input method client, pid=1245
,I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +261ms
,W/ResourceType( 3851): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3851): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4251d700, mServedView=org.apache.cordova.engine.SystemWebView{424e3490 VFEDH.C. .F...... 0,0-720,1134 #64}
W/XT9_C   ( 1180): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1180): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1180): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1180): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  903): Enable input method client, pid=3851
D/PMS     (  903): releaseWL(428dfdb8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3851): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3851): JniHelper::setJavaVM(0x42093010), pthread_self() = 1662557056
,D/JX-Cordova( 3851): jxcore cordova android initializing
,W/dalvikvm( 3851): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 11.520MB for 63974-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 11.557MB for 95956-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 11.630MB for 143930-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 11.745MB for 215890-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 11.919MB for 323830-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 12.594MB for 728606-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 13.192MB for 1092904-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 14.054MB for 1639352-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 15.436MB for 2459024-byte allocation
,I/dalvikvm-heap( 3851): Grow heap (frag case) to 17.446MB for 3688532-byte allocation
,W/jxcore-log( 3851): Initializing JXcore engine
,W/jxcore-log( 3851): JXcore engine is ready
,W/jxcore-log( 3851): Starting JXcore engine
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(424caad0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(42cb4958): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3851): Platform android
W/jxcore-log( 3851): 
,W/jxcore-log( 3851): Process ARCH arm
W/jxcore-log( 3851): 
,I/SensorManager(  903): mEventCount = 1200
,I/jxcore-log( 3851): JXcore Cordova bridge is ready!
I/jxcore-log( 3851): 
,W/jxcore-log( 3851): JXcore engine is started
,I/chromium( 3851): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 3851): Skipped 136 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3851): Toggling radios to true
I/jxcore-log( 3851): 
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  903): checking for enable restriction...
,D/BluetoothManagerService(  903): checkBTEasState, ret=true
I/BluetoothManagerService(  903): isBluetoothRestricted(): false
,D/BluetoothManagerService(  903): enable(): region ID = 6
D/BluetoothManagerService(  903): enable():  mBluetooth =null mBinding = false
,W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 1
W/Settings:Agent(  903): >> traceCallingStack()
,W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1409
,W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): 
,W/System.err(  903): java.lang.Throwable: stack dump
,W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
,W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 8(ms)
,D/BluetoothManagerService(  903): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  903): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3851): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1403
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
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
D/WifiService(  903): setWifiEnabled: true pid=3851, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,I/ActivityManager(  903): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3896 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3851): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 3851): reconnect: Base Package Name=com.test.thalitest, uid=10348
,I/jxcore-log( 3851): Radios toggled
I/jxcore-log( 3851): 
D/PMS     (  903): acquireWL(42d3b2c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
,D/AdapterServiceConfig( 3896): Adding HeadsetService
D/AdapterServiceConfig( 3896): Adding A2dpService
D/AdapterServiceConfig( 3896): Adding HidService
D/AdapterServiceConfig( 3896): Adding HealthService
D/AdapterServiceConfig( 3896): Adding PanService
,D/AdapterServiceConfig( 3896): Adding GattService
,W/linker  ( 3896): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3896): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43653c38:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3896): make
,I/BluetoothAdapterState( 3896): Entering OffState
,I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3896): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  903): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  903): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  903): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapter( 1468): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42756cf8
,D/BluetoothAdapter( 1468): onBluetoothServiceUp done
,D/BluetoothAdapter( 1741): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42ae9280
,D/BluetoothAdapter( 1741): onBluetoothServiceUp done
,D/BluetoothAdapter( 3851): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4303d908
D/BluetoothAdapter( 3851): onBluetoothServiceUp done
,D/BluetoothAdapter(  903): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42d55258
,D/BluetoothAdapter(  903): onBluetoothServiceUp done
,D/BluetoothAdapter( 1213): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4259a1f0
,D/BluetoothAdapter( 1213): onBluetoothServiceUp done
D/BluetoothAdapter( 1221): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42610000
,D/BluetoothAdapter( 1221): onBluetoothServiceUp done
D/BluetoothAdapter( 1103): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@428f00e0
,D/BluetoothAdapter( 1103): onBluetoothServiceUp done
D/BluetoothAdapter( 3896): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@424ef050
D/BluetoothAdapter( 3896): onBluetoothServiceUp done
,D/BluetoothManagerService(  903): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3896): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3896): Setting state to 11
I/BluetoothAdapterState( 3896): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3896): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  903): +onBluetoothStateChange prev=10 new=11
,D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothBondStateMachine( 3896): make
,D/BluetoothManagerService(  903): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1103): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3896): StableState(): Entering Off State
,D/HeadsetService( 3896): Received start request. Starting profile...
D/HeadsetStateMachine( 3896): Version 1.6
,D/HeadsetStateMachine( 3896): make
,D/PMS     (  903): releaseWL(42ee96e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3922 uid=10037 gids={50037, 3002, 3001}
,I/BluetoothAdapterState( 3896): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/QuickSettingBluetooth( 1103): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,I/HeadsetStateMachine( 3896): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3896): Received start request. Starting profile...
,V/Avrcp   ( 3896): make
,D/Avrcp   ( 3896): fillIntentFilter()
,D/A2dpStateMachine( 3896): make
,D/A2dpStateMachine( 3896): Enter Disconnected: -2
,D/HidService( 3896): Received start request. Starting profile...
,D/HtcBtWidget_BTWidgetProvider( 3922): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3922): updateWidget(context) for widget: 
,D/HealthService( 3896): Received start request. Starting profile...
,D/Process (  903): killProcessQuiet, pid=3014
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PanService( 3896): Received start request. Starting profile...
,D/BluetoothTethering(  903): supplyMessenger
D/BluetoothTethering(  903): supplyMessenger mAsyncChannel is null
,D/BluetoothTethering(  903): got MESSAGE_CONNECT_PANSERVICE, call connect
,D/PanService( 3896): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  903): got CMD_CHANNEL_HALF_CONNECTED
,D/BtGatt.DebugUtils( 3896): handleDebugAction() action=null
D/BtGatt.GattService( 3896): Received start request. Starting profile...
,D/BtGatt.GattService( 3896): start()
V/BluetoothPbapService( 3896): Pbap Service onCreate
,V/BluetoothPbapService( 3896): Starting PBAP service
,I/ActivityManager(  903): Killing 3014:com.android.defcontainer/u0a19 (adj 15): empty #17
D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 11
D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 11
E/BluetoothMasService( 3896): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3896): Add permission for SmsProvider.
V/BluetoothMasService( 3896): Starting MAS instances
,D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 11
,I/MailMessageReceiver( 3896): reg:com.android.bluetooth.btservice.AdapterApp@424e25b8 with com.htc.util.mail.MailMessageReceiver@425223f8
I/ActivityManager(  903): Recipient 3014
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/MailManager( 3896): MailManager contruct! com.htc.util.mail.MailMessageReceiver@425223f8
V/EmailUtils( 3896): Manager Instance is not NULL
,I/ActivityManager(  903): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3941 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
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
D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/PMS     (  903): releaseWL(42d3b2c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  903): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 3896): ============NULL aList========
,V/EmailUtils( 3896): <-getEmailAccountIdList
,V/BluetoothMasService( 3896): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 11
V/BluetoothMasService( 3896): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3896): Manager Instance is not NULL
D/EmailUtils( 3896): ============NULL aList========
,V/EmailUtils( 3896): <-getEmailAccountIdList
V/BluetoothSapService( 3896): Sap Service onCreate
V/BluetoothSapService( 3896): initBinder
V/BluetoothSapService( 3896): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@42527c28
V/BluetoothSapReceiver( 3896): BluetoothSapReceiver init
D/BluetoothSapService( 3896): setSapService()
V/BluetoothSapService( 3896): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3896): state: 12
D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 11
D/BluetoothAdapterService( 3896): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3896): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3896): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3896): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3896): Profile still not running:com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 3896): Profile still not running:com.android.bluetooth.gatt.GattService
D/PanService( 3896): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothTethering(  903): got CMD_CHANNEL_FULLY_CONNECTED
,D/BluetoothAdapterState( 3896): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/Process (  903): killProcessQuiet, pid=3380
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/BluetoothMasReceiver( 3896): Bluetooth STATE CHANGED to 11
I/ActivityManager(  903): Killing 3380:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/qcom-bluetooth( 3959): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  903): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3960 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 3977): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 3978): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3960): Received state change = 11
,I/qcom-bluetooth( 3980): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3981): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3982): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3983): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  903): New client listening to asynchronous messages
,D/WifiMonitor(  903): startMonitoring(wlan0) with mConnected = false
I/IntentController( 1103): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1103): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  903): Recipient 3380
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  903): Client com.google.android.music (pid 3380): Died!
,I/wpa_supplicant( 3988): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 3988): Add randomness: count=1 entropy=0
D/wpa_supplicant( 3988): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3988): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 3988): Get randomness: len=20 entropy=1
D/wpa_supplicant( 3988): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3988): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 3988): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 3988): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3988): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 3988): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3988): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3988): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3988): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3988): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3988): update_config=1
D/wpa_supplicant( 3988): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3988): device_name='Android_63cc'
D/wpa_supplicant( 3988): manufacturer='HTC'
D/wpa_supplicant( 3988): model_name='HTC_PHONE'
D/wpa_supplicant( 3988): model_number='1234'
D/wpa_supplicant( 3988): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3988): p2p_oper_reg_class=126
D/wpa_supplicant( 3988): p2p_oper_channel=36
D/wpa_supplicant( 3988): p2p_ssid_postfix='-Android_63cc'
,D/wpa_supplicant( 3988): persistent_reconnect=1
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 3988): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3988): nl80211: RFKILL status not available
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3988): nl80211: Using driver-based roaming
D/wpa_supplicant( 3988): nl80211: TDLS supported
D/wpa_supplicant( 3988): nl80211: TDLS external setup
D/wpa_supplicant( 3988): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3988): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3988): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3988): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3988): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3988): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 3988): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3988): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8288758
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8288758
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3988): htc_wext_command_init +
E/wpa_supplicant( 3988): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 3988): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3988): nl80211: Use Multi channel concurrency
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3988): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3988): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3988): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3988): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3988): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 57240-63720 @ 2160 MHz
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3988): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  903): interfaceLinkStateChanged p2p0, false
D/Tethering(  903): interfaceStatusChanged p2p0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged p2p0, false
D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/Process (  903): killProcessQuiet, pid=3686
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=3990 uid=10048 gids={50048}
I/ActivityManager(  903): Killing 3686:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3686
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,I/QuickSettingWifi( 1103): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/HtcWiFiWidget_WiFiWidgetProvider( 3990): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 3990): updateWidget(context) for widget: 
,D/Process (  903): killProcessQuiet, pid=3362
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  903): Killing 3362:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4002 uid=10077 gids={50077}
,D/PMS     (  903): acquireWL(42fd5ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10077}
,V/AlarmManager(  903): sending alarm PendingIntent{42ee95b0: PendingIntentRecord{42f837d0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449683635311, Int=60000
,D/PMS     (  903): releaseWL(42fd5ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4002): SMSBackupAgentService started
,D/SMSBackup( 4002): Checking restore status
D/SMSBackup( 4002): Restore complete
,D/SMSBackup( 4002): cancelCheckAlarm
I/ActivityManager(  903): Recipient 3362
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SMSBackup( 4002): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  903): killProcessQuiet, pid=3532
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/qcom-bluetooth( 4015): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/ActivityManager(  903): Killing 3532:com.google.android.gm/u0a107 (adj 15): empty #17
I/qcom-bluetooth( 4016): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3896): btu_task pending for preload complete event
,I/wpa_supplicant( 3988): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 3988):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 3988):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3988):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): nl80211: Flush PMKIDs
E/wpa_supplicant( 3988): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 3988): State: DISCONNECTED -> INACTIVE
,D/wpa_supplicant( 3988): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3988): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3988): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3988): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3988): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3988): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3988): Using existing control interface directory.
D/wpa_supplicant( 3988): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 3988): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 3988): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 3988): P2P: Own listen channel: 1
D/wpa_supplicant( 3988): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 3988): P2P: Add operating class 81
I/wpa_supplicant( 3988): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 3988): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 3988): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3988): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 3988): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/ActivityManager(  903): Recipient 3532
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 3988): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3988): disable_scan_offload=1
D/wpa_supplicant( 3988): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 3988): update_config=1
D/wpa_supplicant( 3988): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3988): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3988): manufacturer='HTC'
D/wpa_supplicant( 3988): model_name='HTC Desire 820'
D/wpa_supplicant( 3988): model_number='HTC Desire 820'
D/wpa_supplicant( 3988): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 3988): persistent_reconnect=1
D/wpa_supplicant( 3988): p2p_disabled=1
D/wpa_supplicant( 3988): hs20=1
D/wpa_supplicant( 3988): interworking=1
D/wpa_supplicant( 3988): Line: 18 - start of a new network block
D/wpa_supplicant( 3988): key_mgmt: 0x2
D/wpa_supplicant( 3988): priority=1 (0x1)
D/wpa_supplicant( 3988): signinfail=0 (0x0)
,D/wpa_supplicant( 3988): Priority group 1,
D/wpa_supplicant( 3988):    id=0 ssid='NG700'
I/wpa_supplicant( 3988): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3988): nl80211: RFKILL status not available
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3988): nl80211: Using driver-based roaming
D/wpa_supplicant( 3988): nl80211: TDLS supported
D/wpa_supplicant( 3988): nl80211: TDLS external setup,
D/wpa_supplicant( 3988): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3988): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 1
,D/wpa_supplicant( 3988): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3988): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3988): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3988): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 3988): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3988): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8298718
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3988): htc_wext_command_init +
I/wpa_supplicant( 3988): htc_wext_command_init -
I/wpa_supplicant( 3988): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 3988): Don't set 00 to countryID.conf
,D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 3988): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 3988): nl80211: Use separate P2P group interface
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3988): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3988): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3988): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3988): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3988): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5735-5835 @ 80 MHz
,D/wpa_supplicant( 3988): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3988): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 3988): wapi_supplicant_init: Init WAI packet wlan0,
D/wpa_supplicant( 3988):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3988):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 3988):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): nl80211: Flush PMKIDs
,E/wpa_supplicant( 3988): send_and_recv error -22 - cmd 54,
,D/wpa_supplicant( 3988): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 3988): TDLS: Driver uses external link setup,
D/wpa_supplicant( 3988): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 3988): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3988): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3988): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3988): Using existing control interface directory.
I/wpa_supplicant( 3988): set country (DE) from /data/misc/wifi/countryID.conf
,I/wpa_supplicant( 3988): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 3988): Auto country group 1: ch36
I/wpa_supplicant( 3988): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=-1, operstate=5
,I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING - ret = 0
V/RegulatoryObserver(  903): uevent:
V/RegulatoryObserver(  903): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4421, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
D/wpa_supplicant( 3988): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 3988): Get randomness: len=20 entropy=0
,D/wpa_supplicant( 3988): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 3988): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_903-2
D/wpa_supplicant( 3988): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 3988): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3988): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3988): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3988): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3988): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3988): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3988): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3988): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3988): nl80211: Event message available
D/wpa_supplicant( 3988): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
,D/wpa_supplicant( 3988): nl80211: Regulatory domain change
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3988): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3988): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3988): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3988): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3988): P2P: Add operating class 81
D/wpa_supplicant( 3988): P2P: Add operating class 115
D/wpa_supplicant( 3988): P2P: Add operating class 116
D/wpa_supplicant( 3988): P2P: Add operating class 117
D/wpa_supplicant( 3988): P2P: Update channel list
D/wpa_supplicant( 3988): p2p0: Updating hw mode
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3988): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3988): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3988): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3988): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 3988): nl80211: Added 802.11b mode based on 802.11g information
,D/WifiNative-wlan0(  903): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 3988): set wifi ON
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER MACADDR
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  903): Loading config and enabling all networks
,D/WifiNative-wlan0(  903): doString: LIST_NETWORKS
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): list_network_info: ret=0x1, pos=0xb829b117 buf=0xb829b0e8
I/wpa_supplicant( 3988): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3988): 0	NG700	any	
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WifiNative-wlan0(  903):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  903): 0	NG700	any	
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 ssid
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
V/RegulatoryObserver(  903): Regulatory Country Code:DE
V/RegulatoryObserver(  903): Start wifi-crda service to run crda.
V/RegulatoryObserver(  903): Country Code is DE
V/RegulatoryObserver(  903): Send broadcast country code message.
I/RegulatoryObserver(  903): Broadcast intent for crda country code: DE
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 bssid
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 priority
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 3,988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'user_cert_file'
I/IntentController( 1103): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 psk
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 3988): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 proto
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  903): Failed to look-up a string: W
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  903): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 group
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  903): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wapi_psk'
D/HtcWiFiWidget_WiFiWidgetProvider( 3990): onWiFiStateChanged() for widget: 
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
D/HtcWiFiWidget_WiFiWidgetProvider( 3990): updateWidget(context) for widget: 
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  903): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 limited
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WIFI_ICON( 1103): updateWifiState: WIFI_STATE_CHANGED enabled
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 eap
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 phase2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 identity
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 password
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'password'
I/wpa_supplicant( 3988): wpa_supplicant_scan enter
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
I/wpa_supplicant( 3988): State: DISCONNECTED -> SCANNING
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 3988): ap_scan=1 , scan_req =1
I/wpa_supplicant( 3988): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 3988): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'client_cert'
D/wpa_supplicant( 3988): nl80211: Event message available
D/wpa_supplicant( 3988): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 engine
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 key_id
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  903): doString: GET_NETWORK 0 private_key
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 3988): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  903): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  903): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 3988): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3988): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET manufacturer HTC
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 3988): manufacturer='HTC'
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 3988): model_name='HTC Desire 820'
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 3988): model_number='HTC Desire 820'
D/WifiNative-wlan0(  903):    returned true
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 3988): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET auto_interworking 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 3988): auto_interworking=0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: STATUS
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): SET_SCREEN_ON:On
I/wpa_supplicant( 3988): htc_wext_set_keepalive +
I/wpa_supplicant( 3988): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3988): getPrivFuncNum +	
I/wpa_supplicant( 3988): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3988): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3988): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET ps 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 3988): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
W/Settings(  903): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  903): doBoolean: CTRL-DAT-AIR_MODE-0:1
D/libc    (  903): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): SETBAND: 0
D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 3988): P2P: Add operating class 81
D/wpa_supplicant( 3988): P2P: Add operating class 115
D/wpa_supplicant( 3988): P2P: Add operating class 116
D/wpa_supplicant( 3988): P2P: Add operating class 117
D/wpa_supplicant( 3988): P2P: Update channel list
I/wpa_supplicant( 3988): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 3988): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3988): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 3988): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 3988): p2p_oper_reg_class=126
D/wpa_supplicant( 3988): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3988): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 3988): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3988): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 3988): p2p_oper_channel=36
E/wpa_supplicant( 3988): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3988): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3988): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 3988): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 3988): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: BSS_FLUSH 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/WifiP2pService(  903): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiMonitor(  903): startMonitoring(p2p0) with mConnected = true
D/WifiNative-wlan0(  903):    returned false
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  903): doBoolean: SET pno 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 3988): wpa_supplicant_scan enter
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 3988): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 3988): persistent_reconnect=1
I/wpa_supplicant( 3988): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET device_name Android_63cc
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 3988): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 3988): device_name='Android_63cc'
I/wpa_supplicant( 3988): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 3988): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 3988): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 3988): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 3988): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 3988): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 3988): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 3988): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3988): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 3988): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  903): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 3988): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 3988): Single channel concurrency preference: sta
I/wpa_supplicant( 3988): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doString: STATUS
D/WifiP2pService(  903): P2pEnablingState
D/WifiP2pService(  903): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2p socket connection successful
D/WifiP2pService(  903): P2pEnabledState
D/WifiStateMachine(  903): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  903): sending p2p connection changed broadcast
D/WifiDisplayController(  903): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  903): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  903): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  903): mWfdEnabled :false, networkInfo.isConnected() :false
W/WifiHW  (  903): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  903): doBoolean: P2P_FLUSH
W/WifiHW  (  903): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 3988): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 3988): P2P: Stopping find
D/wpa_supplicant( 3988): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 3988): P2P: State IDLE -> IDLE
I/wpa_supplicant( 3988): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  903): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 3988): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 3988): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doString: LIST_NETWORKS
W/WifiHW  (  903): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 3988): list_network_info: ret=0x22, pos=0xb829b10a buf=0xb829b0e8
I/wpa_supplicant( 3988): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3988): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  903):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  903): doBoolean: AP_SCAN 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  903):    returned false
D/WifiNative-p2p0(  903): doBoolean: SET wifi_display 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 3988): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 3988): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 3988): WFD: Update WFD IE
I/wpa_supplicant( 3988): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3988): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  903):    returned true
D/WifiNative-p2p0(  903): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  903): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 3988): WFD: Set subelement 0
D/wpa_supplicant( 3988): WFD: Update WFD IE
I/wpa_supplicant( 3988): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3988): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  903):    returned true
V/AudioService(  903): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  903):     Client/Owner: Client
V/AudioService(  903):     GroupId: 
V/AudioService(  903):     Passphrase: 
V/AudioService(  903):     SessionId: 0
V/AudioService(  903):     IP Address: }
D/HtcEffectManagerBase(  903): onEventChanged id=5 status=false
D/HtcEffectManager(  903): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  903): convertEffect before=902
D/HtcEffectManager(  903): convertEffect after=902
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
D/WifiP2pService(  903): P2pEnabledState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
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
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
I/QuickSettingWifi( 1103): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
,D/wpa_supplicant( 3988): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 3988): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3988): nl80211: if_removed already cleared - ignore event
D/Tethering(  903): interfaceLinkStateChanged p2p0, false
,D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 3988): nl80211: Event message available
D/wpa_supplicant( 3988): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 3988): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3988): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 3988): nl80211: Survey data missing
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3988): Sorted scan results
I/wpa_supplicant( 3988): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 3988): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-43
I/wpa_supplicant( 3988): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-43
I/wpa_supplicant( 3988): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-83
D/wpa_supplicant( 3988): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 3988): Add randomness: count=2 entropy=0
D/wpa_supplicant( 3988): Add randomness: count=3 entropy=1
D/wpa_supplicant( 3988): Add randomness: count=4 entropy=2
D/wpa_supplicant( 3988): Add randomness: count=5 entropy=3
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 3988): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3988): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3988): wpa_supplicant_pick_network+
I/wpa_supplicant( 3988): Selecting BSS from priority group 1
I/wpa_supplicant( 3988): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3988): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3988): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 3988): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 3988): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 3988):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 3988):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-43
I/wpa_supplicant( 3988): Start print parameters
I/wpa_supplicant( 3988): wpa_s->wpa_state is 3
I/wpa_supplicant( 3988): wpa_s->br_have_IP is 0
I/wpa_supplicant( 3988): isConcurrentMode() is 0
I/wpa_supplicant( 3988): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 3988): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 3988): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 3988): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 3988): wpa_s->reassociate is 0
I/wpa_supplicant( 3988): wpa_s->is_screen_on 1
I/wpa_supplicant( 3988): wpa_s->ifname wlan0
I/wpa_supplicant( 3988): End print parameters
I/wpa_supplicant( 3988): selected network = 2
D/wpa_supplicant( 3988): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb82994e8  current_ssid=0x0
D/wpa_supplicant( 3988): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3988): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 3988): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 3988): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 3988): check if in concurrent case
,I/wpa_supplicant( 3988): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 3988): wpa_supplicant_associate, 1777
D/wpa_supplicant( 3988): wpa_supplicant_associate, 1780
D/wpa_supplicant( 3988): wpa_supplicant_associate, 1795
D/wpa_supplicant( 3988): RSN: PMKSA cache search - network_ctx=0xb82994e8 try_opportunistic=0
D/wpa_supplicant( 3988): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3988): RSN: No PMKSA cache entry found
I/wpa_supplicant( 3988): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3988): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 3988): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3988): nl80211: Unsubscribe mgmt frames handle 0xb8298718 (mode change)
D/wpa_supplicant( 3988): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8298718
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Register frame type=0xd0 nl_handle=0xb8298718
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3988): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 3988):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3988):   * freq=2412
D/wpa_supplicant( 3988):   * Auth Type 0,
D/wpa_supplicant( 3988):   * WPA Versions 0x2
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 3988): nl80211: Connect request send successfully
D/wpa_supplicant( 3988): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3988): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 3988): reply (489) for get BSS: id=0
I/wpa_supplicant( 3988): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3988): freq=5220
I/wpa_supplicant( 3988): level=-52
I/wpa_supplicant( 3988): tsf=0000000105390934
I/wpa_supplicant( 3988): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3988): ssid=NG7005g
I/wpa_supplicant( 3988): ====
I/wpa_supplicant( 3988): id=1
I/wpa_supplicant( 3988): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 3988): freq=2412
I/wpa_supplicant( 3988): level=-43
I/wpa_supplicant( 3988): tsf=0000000105390921
I/wpa_supplicant( 3988): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 3988): ssid=01ABC
,I/wpa_supplicant( 3988): ====
I/wpa_supplicant( 3988): id=2
I/wpa_supplicant( 3988): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3988): freq=2412
I/wpa_supplicant( 3988): level=-43
I/wpa_supplicant( 3988): tsf=0000000105390930
I/wpa_supplicant( 3988): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3988): ssid=NG700
I/wpa_supplicant( 3988): ====
I/wpa_supplicant( 3988): id=3
I/wpa_supplicant( 3988): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 3988): freq=2427
I/wpa_supplicant( 3988): level=-83
I/wpa_supplicant( 3988): tsf=0000000105390939
I/wpa_supplicant( 3988): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 3988): ssid=Gonzos
I/wpa_supplicant( 3988): ####
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 5220, timestamp: 105390934, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -43, frequency: 2412, timestamp: 105390921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -43, frequency: 2412, timestamp: 105390930, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2427, timestamp: 105390939, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/bt-btu  ( 3896): btu_task received preload complete event
,D/bt-btm  ( 3896): btm_acl_device_down
D/bt-btm  ( 3896): btm_acl_reset_paging
,D/bt-btm  ( 3896): btm_acl_set_discing
,I/bt-btm  ( 3896): btm_reset_complete
,I/bt-btm  ( 3896): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3896): Start reading local supported commands
D/wpa_supplicant( 3988): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3988): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3988): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3988): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 3988): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 3988): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 3988): nl80211: if_removed already cleared - ignore event
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 3988): nl80211: Event message available
D/wpa_supplicant( 3988): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 3988): nl80211: Connect event
D/wpa_supplicant( 3988): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 3988): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3988): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 3988): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3988): Add randomness: count=6 entropy=4
I/wpa_supplicant( 3988): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 3988): TDLS: Remove peers on association
D/wpa_supplicant( 3988): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 3988): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 3988): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 3988): EAPOL: SUPP_BE entering state IDLE
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 3988): htc_wext_set_keepalive +
I/wpa_supplicant( 3988): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 3988): getPrivFuncNum +	
I/wpa_supplicant( 3988): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3988): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3988): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 3988): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3988): Get randomness: len=32 entropy=5
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412,
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/WifiStateMachine(  903): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Associated
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48,
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/bt-btm  ( 3896): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 3896): BTM reads next extended features page (1)
,D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
,D/bt-btm  ( 3896): BTM reads next extended features page (2)
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/bt-btm  ( 3896): BTM reached last extended features page (2)
,D/bt-btm  ( 3896): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
I/wpa_supplicant( 3988): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb82989f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 3988):    addr=c0:ff:d4:d3:aa:48
,D/bt-btm  ( 3896): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
D/WifiApDatabaseHandler(  903): updateConnectedAP...
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 3988): EAPOL: External notification - portValid=1
I/wpa_supplicant( 3988): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f5ab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 3988):    broadcast key
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 3988): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 3988): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3988): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3988): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 3988): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/bt-btm  ( 3896): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/bt-btm  ( 3896): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 3896): btm_read_ble_wl_size 
E/wpa_supplicant( 3988): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 3988): set send_ind_to_ndc = 0
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3988): EAPOL: External notification - portValid=1
D/wpa_supplicant( 3988): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 3988): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 3988): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 3988): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3988): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 3988): EAPOL authentication completed successfully
I/wpa_supplicant( 3988): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 3988): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3988): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 3988): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/bt-btm  ( 3896): btm_read_white_list_size_complete 
,D/bt-btm  ( 3896): btm_get_ble_buffer_size 
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
D/bt-btm  ( 3896): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3896): btm_read_ble_local_supported_features 
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/bt-btm  ( 3896): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3896): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3896): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3896): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3896): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3896): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3896): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3896):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3896): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3896): BTM_SetInquiryMode
I/bt-btm  ( 3896): BTM_SetPageScanType
I/bt-btm  ( 3896): BTM_SetInquiryScanType
D/bt-btm  ( 3896): btm_decode_ext_features_page page: 1
,D/bt-btm  ( 3896): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3896): BTM_BleLoadLocalKeys
D/bt-btm  ( 3896): BTM_BleLoadLocalKeys
I/bt-btm  ( 3896): BTM_Sec: application registered
E/bt-btm  ( 3896): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fbc941 
I/bt-btm  ( 3896): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3896): SMP_Register state=0
E/bt-btm  ( 3896): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fbc941 
I/bt-btm  ( 3896): BTM_Sec: application registered
D/bt-btm  ( 3896): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3896): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3896): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3896): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
,D/bt-btm  ( 3896): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3896): BTM_RegBusyLevelNotif
I/bt-att  ( 3896): GATT_Register
D/bt-att  ( 3896): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3896): allocated gatt_if=3
I/bt-att  ( 3896): GATT_StartIf gatt_if=3
D/bt-att  ( 3896): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3896): gatt_find_the_connected_bda found=0 found_idx=7
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,E/bt-btif ( 3896): Calling BTA_HhEnable
E/bt-btif ( 3896): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3896): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3896): Address is:80:01:84:8A:B3:68
I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:1 len:14
,I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3896): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:7 len:4
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3896): BTM_AllocateSCN
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3896): BTM_AllocateSCN
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3896):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3896):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3896):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3896):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3896):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3896):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3896):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3896):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3896): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3896): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
D/bt-avp  ( 3896): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3896): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, pr,oto_id 6, chan_id 0
I/bt-btm  ( 3896):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3896): BTM_GetHCIConnHandle
I/bt-btm  ( 3896): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3896): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3896): BTM_GetHCIConnHandle
I/bt-btm  ( 3896): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3896): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3896): BTM_GetHCIConnHandle
I/bt-btm  ( 3896): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3896): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3896): BTM_GetHCIConnHandle
I/bt-btm  ( 3896): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3896): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3896): BTM_GetHCIConnHandle
I/bt-btm  ( 3896): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3896): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3896): GATT_Register
D/bt-att  ( 3896): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3896): allocated gatt_if=4
I/bt-att  ( 3896): GATT_StartIf gatt_if=4
D/bt-att  ( 3896): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3896): gatt_find_the_connected_bda found=0 found_idx=7
,D/BluetoothAdapterProperties( 3896): Scan Mode:20
I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3896): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:8 len:30
D/BluetoothAdapter( 3896): getBluetoothService(): entry
D/BluetoothAdapter( 3896): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3896): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@42532ae0
,D/BluetoothDevice( 3896): getService : Register callback
,D/BluetoothAdapterProperties( 3896): Adding bonded device:B4:CE:F6:AB:A4:6A
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/BluetoothAdapterProperties( 3896): Adding bonded device:08:EC:A9:50:76:27
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/BluetoothAdapterProperties( 3896): Adding bonded device:34:FC:EF:9D:93:0B
,D/BluetoothAdapterProperties( 3896): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3896): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3896): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3896): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3896): Remote class is:5898764
,I/bt-btif ( 3896): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3896): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 3896): Remote class is:5898764
I/bt-btif ( 3896): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/BluetoothRemoteDevices( 3896): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/BluetoothRemoteDevices( 3896): Remote class is:5898764
,D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
,I/bt-btif ( 3896): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,E/BluetoothRemoteDevices( 3896): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 3896): Remote class is:5898764
,I/bt-btif ( 3896): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3896): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/WifiService(  903): New client listening to asynchronous messages
D/BluetoothRemoteDevices( 3896): Remote class is:5898764
D/DhcpStateMachine(  903): [StoppedState] Start DHCP
I/bt-btif ( 3896): BTA_JvEnable
I/bt-btm  ( 3896): BTM_ReadConnectability
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/bt-btm  ( 3896): BTM_ReadDiscoverability
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/bt-btm  ( 3896): BTM_SetDiscoverability
I/bt-btm  ( 3896): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3896): br_edr_supported=0x2
I/bt-btm  ( 3896): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3896): btm_ble_update_adv_flag new=0x0
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3896): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3896): BTM_SetConnectability
I/bt-btm  ( 3896): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3896): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3896): BTM_SetDiscoverability
I/bt-btm  ( 3896): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3896): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3896): br_edr_supported=0x0
I/bt-btm  ( 3896): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3896): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3896): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3896): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3896): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3896): BTM_SetConnectability
I/bt-btm  ( 3896): HAL bt_hal_cbacksctability mode=0x0 combined_mode=0x0
I/bt-btif ( 3896): always disable adv in non-discoverable non-
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3896): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3896): bta_pan_co_init
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3896): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3896):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3896):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3896): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3896):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3896): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3896):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
D/BluetoothAdapterState( 3896): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3896): ScanMode =  20
D/BluetoothAdapterProperties( 3896): State =  11
I/bt-btm  ( 3896): BTM_SetDisco,verability
I/bt-btif ( 3896): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3896): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3896): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3896): br_edr_supported=0x0
I/bt-btm  ( 3896): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3896): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3896): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3896): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3896): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3896): BTM_SetConnectability
I/bt-btm  ( 3896): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3896): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3896): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3896): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3896): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:7 len:4
E/bt_mct  ( 3896): hci lib postload completed
D/BluetoothAdapterProperties( 3896): Setting state to 12
I/BluetoothAdapterState( 3896): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3896): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  903): +onBluetoothStateChange prev=11 new=12
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [2][0][0]
D/BluetoothAdapterProperties( 3896): Scan Mode:21
I/bt-btif ( 3896): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3896): Discoverable Timeout:120
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 3896): Entering On State
D/BluetoothManagerService(  903): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1213): onBluetoothStateChange: up=true
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  903): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): WiFioffload: update mobile network = Unknown
D/BluetoothAdapterService(1112458464)( 3896): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3896): getBondedDevices: length=5
D/WifiNative-wlan0(  903):    returned true
D/BluetoothHeadset( 1213): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1213): Proxy object connected
D/wpa_supplicant( 3988): EAPOL: disable timer tick
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): Power_Mode_Type mode = 1
I/wpa_supplicant( 3988): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
,D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WIFI_ICON( 1103): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(42e37fd0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
,D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/BluetoothPan(  903): onBluetoothStateChange(on) call bindService
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
,D/BluetoothHeadset( 1213): Proxy object connected
,D/BluetoothPhoneService( 1213): BluetoothHeadset onServiceConnected
,D/BluetoothHeadset( 1103): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1112458464)( 3896): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3896): getBondedDevices: length=5
,D/BluetoothAdapter( 1213): 1113795920: getState(). Returning 12
,D/BluetoothPan(  903): BluetoothPAN Proxy object connected
,D/BluetoothHeadset(  903): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  903): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  903): Proxy object connected
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43542718 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43542718 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothAdapter(  903): 1121933648: getState(). Returning 12
,D/BluetoothManagerService(  903): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1103): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothHeadset( 1103): Proxy object connected
I/QuickSettingMiniLite( 1103): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@427e60b8
,I/QuickSettingWifi( 1103): receive.wifiConnect:false wifiAPname:null elapse:1
,D/BluetoothA2dp(  903): Proxy object connected
,D/BluetoothAdapter(  903): 1121933648: getState(). Returning 12
V/BluetoothPbapReceiver( 3896): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3896): ***********state = 12
,D/BluetoothManagerService(  903): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMasReceiver( 3896): Bluetooth STATE CHANGED to 12
D/PMS     (  903): acquireWL(44471a20): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3316 1000 null
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  903): releaseWL(44471a20): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/HtcBtWidget_BTWidgetProvider( 3922): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3922): updateWidget(context) for widget: 
V/BluetoothSapReceiver( 3896): SapReceiver onReceive 
W/System.err(  903): java.lang.Throwable: stack dump
V/BluetoothSapReceiver( 3896): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3896):  Bluetooth Adapter state = 12
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
V/BluetoothSapReceiver( 3896): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43448858:true
,I/LocationAgent( 3316): new LocationAgent instance!!
,D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 12
,D/HtcTagManager( 3316): HtcTagManager construction complete
,D/PMS     (  903): acquireWL(42f818c0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3316 1000 null
D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 12
V/BluetoothMasService( 3896): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3896): Manager Instance is not NULL
D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
D/EmailUtils( 3896): ============NULL aList========
V/EmailUtils( 3896): <-getEmailAccountIdList
D/BluetoothInputDevice( 3316): BluetoothInputDevice()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 7
D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
,D/BluetoothInputDevice( 3316): BluetoothInputDevice(): Binding service...
,D/BluetoothPan( 3316): BluetoothPan()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
D/BluetoothPan( 3316): BluetoothPan(): Binding service...
,D/BluetoothManagerService(  903): Registered receivers: 8
,D/BluetoothMap( 3316): Create BluetoothMap proxy object
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
V/BluetoothSapService( 3896): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  903): Registered receivers: 9
,V/BluetoothSapService( 3896): state: 12
D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 12
,E/BluetoothMap( 3316): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 10
D/BluetoothSap( 3316): BluetoothSap() call bindService
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
,V/BluetoothSapService( 3896): Starting SAP server process
V/BluetoothPbapService( 3896): Handler(): got msg=1
,D/BluetoothPbap( 3316): BluetoothPbap()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 11
D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
,D/BluetoothPbap( 3316): BluetoothPbap(): Binding service...
,V/BluetoothPbapService( 3896): Pbap Service startRfcommSocketListener
,D/BluetoothA2dp( 3316): BluetoothA2dp()
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 12
D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
D/BluetoothA2dp( 3316): BluetoothA2dp(): Binding service...
D/BluetoothAdapter( 1103): 1115170632: getState(). Returning 12
V/BluetoothMasService( 3896): handleMessage: mIsEmailEnabledtrue
V/BluetoothPbapService( 3896): Pbap Service initSocket
V/BtMns   ( 3896): BluetoothMns: isEmailEnabled: true
D/BluetoothAdapter( 1103): 1115170632: getState(). Returning 12
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/QuickSettingBluetooth( 1103): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1103): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothHeadset( 3316): BluetoothHeadset()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothAdapter( 3896): getBluetoothService(): entry
,W/BluetoothAdapter( 3896): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 13
,D/BluetoothMasService( 3896): Map_prev 1
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
,D/BluetoothHeadset( 3316): BluetoothHeadset(): Binding service...
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
E/BluetoothServiceJni( 3896): SOCK FLAG = 1 ***********************
I/bt-btif ( 3896): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btif ( 3896): BTA_JvRfcommStartServer
I/bt-btm  ( 3896): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3896):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3896): Succeed to create listening socket 
,V/BluetoothPbapService( 3896): Accepting socket connection...
,D/HtcTagManager( 3316): startProxy
,W/ContextImpl( 3316): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
D/BluetoothAdapter( 3896): getBluetoothService(): entry
,W/BluetoothAdapter( 3896): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3316): LocalBluetoothProfileManager construction complete
E/BluetoothServiceJni( 3896): SOCK FLAG = 3 ***********************
I/bt-btif ( 3896): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btif ( 3896): BTA_JvRfcommStartServer
I/bt-btm  ( 3896): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3896):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/DockEventReceiver( 3316): finishStartingService: stopping service
D/BluetoothAdapter( 3896): getBluetoothService(): entry
W/BluetoothAdapter( 3896): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothPan( 3316): BluetoothPAN Proxy object connected
D/PanProfile( 3316): Bluetooth service connected
D/BluetoothA2dp( 3316): Proxy object connected
D/A2dpProfile( 3316): Bluetooth service connected
E/BluetoothServiceJni( 3896): SOCK FLAG = 3 ***********************
I/bt-btif ( 3896): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btif ( 3896): BTA_JvRfcommStartServer
I/bt-btm  ( 3896): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3896):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3960): onCreate: going to find gatt base service first.
D/BluetoothHeadset( 3316): Proxy object connected
D/HeadsetProfile( 3316): Bluetooth service connected
,D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
,D/BluetoothAdapter( 1103): 1115170632: getState(). Returning 12
,I/QuickSettingMiniLite( 1103): updateLiteState:no connect device!
,W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44a03598:true
,D/PMS     (  903): releaseWL(42f818c0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/[HTC_BLE][Constants]( 3960):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3960):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3960):  + discoverServicesOnBonded = false
,D/BluetoothInputDevice( 3316): Proxy object connected
,D/HidProfile( 3316): Bluetooth service connected
,D/BluetoothAdapter( 3316): 1114054272: getState(). Returning 12
V/TAG     ( 3896): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 3896): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@42529368
,D/SapServerProfile( 3316): Bluetooth service connected
D/BluetoothSapService( 3896): Sap_prev 1
V/BluetoothSapService( 3896): SAP Service startRfcommListenerThread
V/BluetoothSapService( 3896): Sap Service initRfcommSocket
,V/BluetoothPbapService( 3896): Pbap Service onBind
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothPbap( 3316): Proxy object connected
,D/PbapServerProfile( 3316): Bluetooth service connected
D/BluetoothAdapter( 3896): getBluetoothService(): entry
,W/BluetoothAdapter( 3896): getBluetoothService() called with no BluetoothManagerCallback
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3960):  + Google LE service found. Using BaseLeProfilesGoogle.
E/BluetoothServiceJni( 3896): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3896): BTA_JvCreateRecordByUser
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@424f24d0
D/[HTC_BLE][Constants]( 3960): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3960): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3960): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3960): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3960): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
D/[HTC_BLE][Constants]( 3960): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btif ( 3896): BTA_JvRfcommStartServer
I/bt-btm  ( 3896): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3896):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3896): Succeed to create listening socket 
,V/BluetoothSapService( 3896): Accepting socket connection...
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3960): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,I/BluetoothFtpService( 3896): Ftp Service onCreate
D/HtcTagManager( 3316): onServiceConnected
D/BluetoothAdapter( 3896): getBluetoothService(): entry
,D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 12
,D/BluetoothMasReceiver( 3896): Bluetooth STATE CHANGED to 12
,W/BluetoothAdapter( 3896): getBluetoothService() called with no BluetoothManagerCallback
D/HtcTagProfile( 3316): setup proxy
D/HtcPxpProfile( 3316): setup proxy
,D/HtcFmpProfile( 3316): setup proxy
D/BluetoothFtpService( 3896): Ftp_prev 1
D/wpa_supplicant( 3988): EAPOL: startWhen --> 0
D/wpa_supplicant( 3988): EAPOL: disable timer tick
E/BluetoothServiceJni( 3896): SOCK FLAG = 0 ***********************
,I/bt-btif ( 3896): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btif ( 3896): BTA_JvRfcommStartServer
I/bt-btm  ( 3896): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 3896):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,I/BtOppRfcommListener( 3896): Accept thread started.
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3960): Received state change = 12
D/BluetoothAdapter( 3896): getBluetoothService(): entry
,W/BluetoothAdapter( 3896): getBluetoothService() called with no BluetoothManagerCallback
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3960): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@424f24d0
E/BluetoothServiceJni( 3896): SOCK FLAG = 1 ***********************
I/bt-btif ( 3896): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3896): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btif ( 3896): BTA_JvRfcommStartServer
I/bt-btm  ( 3896): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
,I/bt-btm  ( 3896):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3960): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@424f24d0
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3960): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@424f24d0, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@424fd4b8
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3960): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@424f24d0
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3896): Run Accept thread
D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 12
V/BluetoothMasService( 3896): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3896): Manager Instance is not NULL
,D/EmailUtils( 3896): ============NULL aList========
,V/EmailUtils( 3896): <-getEmailAccountIdList
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothMasService( 3896): Map_prev 1
,D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43abcc78:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3816): new LocationAgent instance!!
,D/HtcTagManager( 3816): HtcTagManager construction complete
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/BluetoothInputDevice( 3816): BluetoothInputDevice()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/BluetoothInputDevice( 3816): BluetoothInputDevice(): Binding service...
,D/BluetoothManagerService(  903): Registered receivers: 14
,D/BluetoothPan( 3816): BluetoothPan()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/RingtoneManager( 3960): getExternalStorageState=mounted
,D/BluetoothManagerService(  903): Registered receivers: 15
D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/BluetoothPan( 3816): BluetoothPan(): Binding service...
,D/BluetoothMap( 3816): Create BluetoothMap proxy object
D/BluetoothManagerService(  903): registerStateChangeCallback+
W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 16
E/BluetoothMap( 3816): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3816): BluetoothSap() call bindService
,D/BluetoothManagerService(  903): Registered receivers: 17
,D/BluetoothPbap( 3816): BluetoothPbap()
D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 18
D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/BluetoothPbap( 3816): BluetoothPbap(): Binding service...
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[1]: Daisy
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[6]: Lavender
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[11]: Thalia
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[12]: Tulip
W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[13]: Wintergreen
D/BluetoothA2dp( 3816): BluetoothA2dp()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 19
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3960):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/BluetoothA2dp( 3816): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3816): BluetoothHeadset()
,D/BluetoothManagerService(  903): registerStateChangeCallback+
,D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  903): Registered receivers: 20
D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/BluetoothHeadset( 3816): BluetoothHeadset(): Binding service...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3960): BleProfilesStateMachine is initialized...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3960): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3960): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): initScanModeInterface: true
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f6b3f8:true
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3960): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3960):  + mTag.getPrimaryDeviceList() = []
W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/HtcTagManager( 3816): startProxy
D/[HTC_BLE][Constants]( 3960):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3960):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 3960):  + discoverServicesOnBonded = false
,W/ContextImpl( 3816): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3816): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3816): setBluetoothStateOn
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/HtcTagManager( 3816): startProxy
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
D/BluetoothAdapterService(1112458464)( 3896): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3896): getBondedDevices: length=5
,W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 3816): getBluetoothService(): entry
D/BluetoothAdapter( 3816): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3816): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@4252dbb8
D/BluetoothDevice( 3816): getService : Register callback
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3960): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@424fd4b8
E/BluetoothDevice( 3816): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
D/HtcTagManager( 3816): addHtcTagProfiles
,E/BluetoothDevice( 3816): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/HtcTagManager( 3816): addHtcTagProfiles
,E/BluetoothDevice( 3816): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/HtcTagManager( 3816): addHtcTagProfiles
,E/BluetoothDevice( 3816): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/HtcTagManager( 3816): addHtcTagProfiles
,E/BluetoothDevice( 3816): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/HtcTagManager( 3816): addHtcTagProfiles
,D/BluetoothInputDevice( 3816): Proxy object connected
,D/HidProfile( 3816): Bluetooth service connected
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/BluetoothPan( 3816): BluetoothPAN Proxy object connected
D/PanProfile( 3816): Bluetooth service connected
D/SapServerProfile( 3816): Bluetooth service connected
D/BluetoothPbap( 3816): Proxy object connected
D/PbapServerProfile( 3816): Bluetooth service connected
,D/BluetoothA2dp( 3816): Proxy object connected
,D/A2dpProfile( 3816): Bluetooth service connected
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/BluetoothHeadset( 3816): Proxy object connected
,D/HeadsetProfile( 3816): Bluetooth service connected
,D/BluetoothAdapter( 3816): 1112491200: getState(). Returning 12
,D/HtcTagManager( 3816): onServiceConnected
D/HtcTagProfile( 3816): setup proxy
D/HtcPxpProfile( 3816): setup proxy
,D/HtcFmpProfile( 3816): setup proxy
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): Power_Mode_Type mode = 0
,I/wpa_supplicant( 3988): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  903): releaseWL(42e37fd0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -42 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3988): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WIFI_ICON( 1103): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  903): gateway: /192.168.1.1
D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -42, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  903): startDataStallAlarm: tag=20463 delay=15s
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WifiWatchdogStateMachine(  903): WAN detection
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
D/MDST    (  903): default: setTeardownRequested(true)
,D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WISPrService( 3316): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@42dfb550
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
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
D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  903): acquireWL(42f51bf8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1103): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42f51bf8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4091 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,V/Tethering(  903): bSetPropertyMultiRAB:false
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1468/10028)
,I/ConnectivityHelper( 1245): [onReceive] WIFI(1): CONNECTED
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/CaptivePortalTracker(  903): NoActiveNetworkState
D/libc    (  903): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ffd2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1245/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1760/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3416/10051)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (3746/10100)
D/PMS     (  903): acquireWL(427e9c70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (3746/10100)
,D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=50 [2][1][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(44695928): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  903): acquireWL(42fe3e88): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 903 1000 WorkSource{10096}
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 13
D/libc    (  364): [NET]res_nsend:resplen=104
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
,I/MusicStore( 4091): Database version: 95
I/ActivityManager(  903): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4110 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/PMS     (  903): acquireWL(43549a90): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.games.background/com.google/***** 0x1 903 1000 WorkSource{10028}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/ContextImpl( 4091): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  903): BroadcastRSSIForIMS, newrssi =-43 , oldRssi= -200
D/PMS     (  903): releaseWL(42fe3e88): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3988): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/GpsLocationProvider(  903): [handleMessage] INJECT_NTP_TIME
D/libc    (  903): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =479b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/PMS     (  903): acquireWL(42ac03a0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 903 1000 WorkSource{10096}
D/WIFI_ICON( 1103): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  903): releaseWL(44695928): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42e6c520): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
W/ContextImpl( 4091): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  903): acquireWL(429acfe0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 903 1000 WorkSource{10160}
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,D/GpsLocationProvider(  903): NTP server returned: 1449683639242 (Wed Dec 09 18:53:59 CET 2015) reference: 108648 certainty: 14 system time offset: -9
,D/GpsLocationProvider(  903): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  903): releaseWL(427e9c70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/IntentController( 1103): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1532): [EventService] EVENT_RESET_THEME_TIMESTAMP
,I/FeedActionBar( 1245): updateLastUpdatedTime(in String) LAST UPDATED 18:52
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4091): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/DotMatrix( 1532): [EventService] isTheSameDay:false,timestamp is early than today:true
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42e6c520): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(431cdc40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(431cdc40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(435658d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(435658d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(448927b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  903): releaseWL(429acfe0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(448927b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/GamesSyncAdapter( 1198): User is not G+ enabled. Aborting sync
,W/ContextImpl( 4091): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4091): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/DelayedSyncController( 4110): Delaying sync.
D/PMS     (  903): acquireWL(44e32200): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(44e32200): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4091, uid=10154, userID:0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(444226b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42ac03a0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  903): acquireWL(43b42548): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 903 1000 WorkSource{10096}
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/PMS     (  903): releaseWL(444226b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/DelayedSyncController( 4110): Delaying sync.
D/PMS     (  903): acquireWL(44937388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(44937388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/MediaRouterService(  903): Client com.google.android.music (pid 4091): Registered
D/PMS     (  903): acquireWL(444edaf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/PMS     (  903): releaseWL(43549a90): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.games.background/com.google/***** 0x1 WorkSource{10028}
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
D/PMS     (  903): releaseWL(444edaf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/MediaRouter( 4091): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/PMS     (  903): acquireWL(43e905a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(43b42548): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  903): releaseWL(43e905a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (4091/10154)
,I/NetworkMonitor( 4091): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2205/10021)
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4140 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4091): getSelectedRoute
,I/NetworkMonitor( 4091): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4091/10154)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
,D/Process (  903): killProcessQuiet, pid=3715
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3715:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4091, uid=10154, userID:0
,I/ActivityManager(  903): Recipient 3715
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 4140): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4140): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4140): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4140): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4140): Preparing secondary program dexes.
,V/DexLibLoader( 4140): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4140): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4140): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4140): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4140): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4140): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4140): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4140): Dex already copied
D/OdexVerifier( 4140): Odex verification is skipped.
,V/DexLibLoader( 4140): Creating class loader
,V/DexLibLoader( 4140): Finished creating class loader
,V/DexLibLoader( 4140): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4140): Dex already copied
D/OdexVerifier( 4140): Odex verification is skipped.
,V/DexLibLoader( 4140): Creating class loader,
,V/DexLibLoader( 4140): Finished creating class loader,
V/DexLibLoader( 4140): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4140): Dex already copied
D/OdexVerifier( 4140): Odex verification is skipped.
,V/DexLibLoader( 4140): Creating class loader,
,V/DexLibLoader( 4140): Finished creating class loader,
V/DexLibLoader( 4140): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4140): Dex already copied
D/OdexVerifier( 4140): Odex verification is skipped.
,V/DexLibLoader( 4140): Creating class loader,
,V/DexLibLoader( 4140): Finished creating class loader
,V/DexLibLoader( 4140): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4140): DexLibLoader.ensureDexLoaded took 91 ms
,I/ClockThread( 1103): now=1449683639763 next=237
,I/ClockThread( 1103): now=1449683640001 next=59999
D/PMS     (  903): acquireWL(43b559f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=109397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43b559f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1103): WifiActivity: 3
,D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/BTIF_CORE( 3896): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3896): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3896): Wake lock released
,W/dalvikvm( 4140): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4140): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4140): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4140): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4140): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4140): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4140): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4140): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4140): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4140): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4140): Verify
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5620 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/WIFI_ICON( 1103): WifiActivity: 1
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4140/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4140): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4140): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/23.59.123.86
,I/dalvikvm-heap( 4140): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,W/ActivityManager(  903): Disable JIT of com.htc.bgp
,I/ActivityManager(  903): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4160 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  903): killProcessQuiet, pid=1371
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 1371:com.htc.sense.hsp/u0a53 (adj 15): empty #17
,I/CalendarProvider2( 4160): Created com.android.providers.calendar.CalendarAlarmManager@4250ead8(com.android.providers.calendar.HtcCalendarProvider@424f6e60)
,D/CalendarProvider2( 4160): wait start:true
,D/CalendarProvider2( 4160): wait end:false
D/PMS     (  903): acquireWL(43622658): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,D/PMS     (  903): acquireWL(44012530): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(43622658): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
I/ActivityManager(  903): Recipient 1371
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4140): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4140): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/GCM     ( 1357): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,W/fb4a(:<default>):UserScope( 4140): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  903): releaseWL(44012530): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1357): [NET] getaddrinfo-,err=8
,D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1357): [NET] getaddrinfo-, 1
D/libc    ( 1357): [NET] getaddrinfo_proxy+
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =662a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,W/ContextImpl( 4140): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/PMS     (  903): acquireWL(43b1de78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1357 10028 null
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  903): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4186 uid=10053 gids={50053, 1023, 3003, 5012}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 238
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1357): [NET] getaddrinfo_proxy-, success
,E/dalvikvm( 4140): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4140): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4140): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4140): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4140): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4140): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4140): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4140): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4140): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4140): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4140): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4140): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4140): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4140): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4140): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4140): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4140): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4140): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4140): Grow heap (frag case) to 9.964MB for 84664-byte allocation
D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1357): [NET] getaddrinfo-,err=8
W/ActivityThread( 1357): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/PluginProvider( 4186): PluginProvider onCreate
,D/PluginProvider( 4186): current plugin count: 19
,D/HtcAppUPService( 4186): HtcUPDataProvider onCreate()
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,D/PMS     (  903): acquireWL(443ba9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,D/PMS     (  903): releaseWL(443ba9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/dalvikvm-heap( 4140): Grow heap (frag case) to 10.003MB for 39954-byte allocation
,I/dalvikvm-heap( 4140): Grow heap (frag case) to 10.080MB for 79892-byte allocation
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42bb5378
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/SensorService(  903): pid=903, uid=1000
D/AutoSetting( 4186): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42bb5378, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42d45f40
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@42ef1900
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  903): mWirelessDisplayManager is null
,I/dalvikvm-heap( 4140): Grow heap (frag case) to 10.098MB for 28144-byte allocation
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4202 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (4186/10053)
,D/Process (  903): killProcessQuiet, pid=3746
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3746:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 4186): service - onCreate()
,D/GCM     ( 1357): Connected
,D/AutoSetting( 4186): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  903): request 42e7b418 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/AutoSetting( 4186): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/LocationManagerService(  903): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 4186): service - onStartCommand() screen is off, don't request location
D/PMS     (  903): acquireWL(429ab3f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/PMS     (  903): releaseWL(43b1de78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (4186/10053)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1357/10028)
D/AutoSetting( 4186): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4186): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/PMS     (  903): releaseWL(429ab3f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(43b99b58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1357/10028)
,D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1357): Message class mpf
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1357/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/PMS     (  903): releaseWL(43b99b58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(42d211e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10028 null
D/PMS     (  903): releaseWL(42d211e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  903): Recipient 3746
,I/dalvikvm-heap( 4140): Grow heap (frag case) to 10.282MB for 75760-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4140/10026)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b1dec8 u0 ReceiverList{43a0acc8 4140 com.facebook.katana/10026/u0 remote:43383e20}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{440cd7b8 u0 ReceiverList{440cd758 4140 com.facebook.katana/10026/u0 remote:42fc9ef0}}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4140/10026)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=54 [11][6][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4140/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4140/10026)
,D/PMS     (  903): acquireWL(4453edd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1468 10028 null
,D/PMS     (  903): releaseWL(4453edd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1468): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(43d8e3b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1468 10028 null
D/PMS     (  903): releaseWL(43d8e3b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ContactMessageStore( 1213): notify MmsSms
,D/AccFlag ( 1213): sense_version=6.0
,D/AccFlag ( 1213): sku_id=99
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 385ms
V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43c014a8)
D/NfcService( 1221): ScreenObserver: OFF
,D/NfcService( 1221): applyRouting - 0
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
D/PMN     (  903): wakingUp
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
I/IntentController( 1103): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1221): applyRouting -2
I/WindowManager(  903): No lock screen! windowToken=null
D/PMS     (  903): acquireWL(445b0bd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1221 1027 null
I/InputMethodManagerService(  903): Disable input method client, pid=3851
D/PMS     (  903): releaseWL(445b0bd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  903): onScreenOn
D/PMS     (  903): acquireWL(43a1f940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43a1f940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/MtpService( 2205): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2205): [MTP][onReceive]-
,D/NfcService( 1221): applyRouting - 0
,D/NfcService( 1221): applyRouting -2
D/PMS     (  903): acquireWL(435f46c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1221 1027 null
D/WIFI_ICON( 1103): WifiActivity: 3
D/PMS     (  903): releaseWL(435f46c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=20464 delay=15s
,I/ClockThread( 1103): stop update clock
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
I/wpa_supplicant( 3988): SET_SCREEN_ON:On
I/wpa_supplicant( 3988): htc_wext_set_keepalive +
I/wpa_supplicant( 3988): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3988): getPrivFuncNum +	
I/wpa_supplicant( 3988): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3988): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3988): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -43 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WIFI_ICON( 1103): WifiActivity: 0
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
V/SRS_Proc(  372): ParamSet string: screen_state=on
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/MobileConnectivityChangeReceiver( 4202): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4202): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4202): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4202): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4140): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4202/10078)
D/WIFI_ICON( 1103): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4231 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/NetworkPolicy(  903): updateScreenOn: false
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4140): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4202/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4202/10078)
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): acquireWL(429b3f58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1468 10028 null
D/PMS     (  903): releaseWL(429b3f58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4231): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3960): onScreenOn: 1449683642218
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3960): onScreenOn: 1449683642218
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4231): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42d45f40
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42d45f40, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@42ef1900
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/GAV2    ( 4231): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(444f1df8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,D/PMS     (  903): acquireWL(42f70040): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4231): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20464 mDataStallAlarmIntent=PendingIntent{42e738e8: PendingIntentRecord{42eb1bd8 android broadcastIntent}}
,W/ContextImpl( 4231): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/PMS     (  903): acquireWL(43a63b38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
D/PMS     (  903): releaseWL(444f1df8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): SET_SCREEN_ON:Off
I/wpa_supplicant( 3988): htc_wext_set_keepalive +
I/wpa_supplicant( 3988): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3988): getPrivFuncNum +	
I/wpa_supplicant( 3988): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3988): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3988): get_ip_address source addr = c0a80176
I/wpa_supplicant( 3988): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 3988): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/CheckinService( 1198): Preparing to send checkin request
,I/EventLogService( 1198): Accumulating logs since 1449683570933
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
D/PMS     (  903): acquireWL(43ff4558): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
,D/ContactMessageStore( 1213): start background delete task...
D/ContactMessageStore( 1213): size: 0 , 0
,D/ContactMessageStore( 1213): Background delete complete
,D/NetworkPolicy(  903): updateScreenOn: false
I/CalendarProvider2( 4160): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
W/ContentResolver( 4160): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,D/Process (  903): killProcessQuiet, pid=3766
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  903): releaseWL(43ff4558): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  903): Killing 3766:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3766
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GoogleHttpClient( 1198): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1198): Using GMS GoogleHttpClient
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=100 [1][1][0]
,D/WifiService(  903): New client listening to asynchronous messages
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3960): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3960): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3960): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3960): onScreenOff
D/AutoSetting( 4186): service - mHandler: cancel location update
,D/AutoSetting( 4186): service -           changes count: 0
D/PMS     (  903): acquireWL(43aec000): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1468 10028 null
D/PMS     (  903): releaseWL(43aec000): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4231/10151)
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1198/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
,V/WebViewChromiumFactoryProvider( 4231): Binding Chromium to main looper Looper (main, tid 1) {424d81b8}
,I/LibraryLoader( 4231): Expected native library version number "",actual native library version number ""
,I/chromium( 4231): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4231): Initializing chromium process, renderers=0
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1198/10028)
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
,E/AudioManagerAndroid( 4231): BLUETOOTH permission is missing!
D/PMS     (  903): acquireWL(449a1bf0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): acquireWL(43557ba8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): releaseWL(449a1bf0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4231): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4231): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4231): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4231): Local Branch: 
I/Adreno-EGL( 4231): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4231): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4231):                  aa63bbd948f41d15fc72f585e
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,I/NSApplication( 4231): Starting up...
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4231/10151)
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4231/10151)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/NotificationStore( 1357): System rebooted after Notification storage file was last written
,I/NotificationStore( 1357): Deleting the file
,D/Process (  903): killProcessQuiet, pid=3784
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
,I/ActivityManager(  903): Killing 3784:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
,I/ActivityManager(  903): Recipient 3784
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3988): environment dirty rate=0 [0][0][0]
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertReceiver( 3802): beginStartingService
D/PMS     (  903): acquireWL(43fffc78): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3802 10013 null
,W/CheckinRequestBuilder( 1198): awaiting user notification for token
D/PMS     (  903): acquireWL(4468d9d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,D/DotMatrix( 1532): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/PMS     (  903): releaseWL(4468d9d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/AlertService( 3802): start to updateAlertNotification!
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{42502368 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/AlertService( 3802): No fired or scheduled alerts
D/HtcAlertUtils( 3802): -- cancelReminderNotification --
,I/RemoteViews.Performance( 1103): com.google.android.gms 1 8 3 12
,D/HtcAlertUtils( 3802): broadcastExistReminder!
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3802): stopSelfResult true
D/PMS     (  903): releaseWL(43fffc78): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4277 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4290 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/WeatherRequest( 1103): request cur loc, but there is no sys cur
,I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4305 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4277): can't get weather sync account
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/MultiDex( 4290): install
,I/MultiDex( 4290): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4290): loading existing secondary dex files
,I/MultiDex( 4290): load found 1 secondary dex files
,I/MultiDex( 4290): install done
D/PMS     (  903): acquireWL(42fe07e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4305 10070 null
,D/PMS     (  903): acquireWL(43683f50): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4305 10070 null
W/WeatherRequest( 4277): request cur loc, but there is no sys cur
,W/Settings( 4277): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  903): releaseWL(42fe07e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  903): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4322 uid=10090 gids={50090, 3003, 5012, 1028}
D/TodoTaskshortcut( 4305): update TASK shortcut>
I/ProviderInstaller( 4290): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/TodoTaskNotifyService( 4305): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/RemoteViews( 1245): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1245): com.htc.widget.weatherclock 2 10 17
,I/TodoTaskNotifyService( 4305): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4305): stopSelfResult true
D/PMS     (  903): releaseWL(43683f50): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/Process (  903): killProcessQuiet, pid=3733
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3733:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/WorldClock.Global( 4322): isHtcDevice = true
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3733
,I/WorldClock.Global( 4322): isHtcDevice = true
W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,W/ActivityManager(  903): Activity pause timeout for ActivityRecord{42a75bd0 u0 com.test.thalitest/.MainActivity t2}
,I/WorldClock.AlarmUtils( 4322): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  903): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4337 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 4322): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4322): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1103): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/Process (  903): killProcessQuiet, pid=3595
,D/TimeService( 4337): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683643000
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3595:com.android.vending/u0a73 (adj 15): empty #17
,D/Process (  903): killProcessQuiet, pid=4002
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4002:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  903): Recipient 4002
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4352 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/ActivityManager(  903): Recipient 3595
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/dalvikvm( 4352): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4352): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,I/Babel   ( 4352): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4352): MmsConfig.loadMmsSettings
E/dalvikvm( 4352): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4352): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4352): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4290): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4290): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4290):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  903): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4377 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,D/MessageFrequencyProvider( 4377): onCreate
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4352, uid=10111, userID:0
,V/GetPrviateResource( 4377): GetPrviateResource
,V/GetPrviateResource( 4377): GetPrviateResource
,D/MmsCustomizationProvider( 4377): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/Settings( 4352): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 4377): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4352): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4352): MmsConfig.loadFromDatabase
,E/Babel   ( 4352): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4352): MmsConfig.loadFromResources
,E/Babel   ( 4352): canonicalizeMccMnc: invalid mccmnc nullnull
I/ProviderInstaller( 4352): Installed default security provider GmsCore_OpenSSL
,I/Babel   ( 4352): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4352, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4352, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4352, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4352, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4352, uid=10111, userID:0
,I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,D/Process (  903): killProcessQuiet, pid=3990
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/MessageCustFlag( 4377): sense_version=6.0
,D/BTAccessoryUtil( 4377): createReceiver
,D/BTAccessoryUtil( 4377): registerReceiver return intent = null
D/MessageCustFlag( 4377): sku_id=99
,W/SystemReader( 4377): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  903): Killing 3990:com.htc.widget.process2/u0a48 (adj 15): empty #17
D/Messaging( 4377): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4377): networkCode: 
D/MessageCustFlag( 4377): sku_id=99
D/MmsConfig( 4377): SIE smsPri: null
,D/MmsConfig( 4377): networkCode: 
I/ActivityManager(  903): Recipient 3990
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (4352/10111)
,D/HtcTelephonyCapability( 4377): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4377): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4377): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4377): Cannot find qct_8960_interface, use default value instead
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (4352/10111)
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4352): UserRecoverableAuthException.
,E/Babel   ( 4352): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4352): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4352): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4352): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4352): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4352): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4352): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4352): Error getting auth token
,E/Babel   ( 4352): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4352): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4352): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4352): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4352): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4352): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4352): Account registration failedRedacted-21
E/Babel   ( 4352): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4352): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4352): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4352): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4352): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4352): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4352): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4352): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (4352/10111)
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4352): Unexpected exception while authenticating.
,E/Babel   ( 4352): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4352): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4352): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4352): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4352): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4352): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4352): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4352): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4352): 	at java.lang.Thread.run(Thread.java:864)
D/DotMatrix( 1532): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{425231f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.google.android.gms 2 5 3 12
,D/AutoSetting( 4186): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  903): killProcessQuiet, pid=3922
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 3922:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TetherSettings( 3316): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3316): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3316): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3316): Cust_ConnectToPC   : spcsc>false
D/        ( 3316): Cust_ConnectToPC   : IPT>true
D/        ( 3316): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3316): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3316): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3316): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 4186): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/jxcore-log( 3851): Test app app.js loaded
I/jxcore-log( 3851): 
,I/Choreographer( 3851): Skipped 556 frames!  The application may be doing too much work on its main thread.
I/PSReceiver( 3316): onReceive:android.intent.action.USER_PRESENT
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4290): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4290): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4290):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  903): Recipient 3922
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  903): mEventCount = 1350
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Delay finish: com.android.settings/.PSReceiver
,W/ResourceType( 3851): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3851): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{424e3490 VFEDH.C. .F....ID 0,0-720,1134 #64}
I/SmartNS_PSService( 3316): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3316):  defaultType:0
,I/chromium( 3851): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  903): releaseWL(42f70040): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4290): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4290): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4290):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4401 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/Settings( 4290): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 4401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4401): isEpsOn(), nState = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4290/10028)
D/PMS     (  903): acquireWL(429a2a88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4401 1000 null
,D/PMS     (  903): releaseWL(429a2a88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4401): getMobilePolicyEnabled, result = true
,D/Process (  903): killProcessQuiet, pid=3941
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3941:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Recipient 3941
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4401): isEpsOn(), nState = 0
D/SmartSyncUtils( 4401): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4401): isEpsOn(), nState = 0
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42ef1900
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  903): New client listening to asynchronous messages
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/ProviderChangeReceiver( 3802): ---------------------------------------------------
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
D/ProviderChangeReceiver( 3802): ProviderChangeReceiver onReceive, start to update notification!
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42ef1900, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
D/AlertService( 3802): start to updateAlertNotification!
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42ef1900, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42ef1900
,W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42fe4080 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42fe4080 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AlertService( 3802): No fired or scheduled alerts
,D/HtcAlertUtils( 3802): -- cancelReminderNotification --
,D/HtcAlertUtils( 3802): broadcastExistReminder!
I/ActivityManager(  903): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  903): Resuming delayed broadcast
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42f9a078): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4305 10070 null
,D/PMS     (  903): acquireWL(43575060): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4305 10070 null
,I/ActivityManager(  903): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,E/TodoTaskNotifyService( 4305): java.lang.NullPointerException
W/System.err( 4305): java.lang.NullPointerException
,D/PMS     (  903): releaseWL(42f9a078): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/System.err( 4305): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4305): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4305): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4305): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4305): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4305): stopSelfResult true
D/PMS     (  903): releaseWL(43575060): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(42e36dc8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4305 10070 null
D/PMS     (  903): acquireWL(43b54068): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4305 10070 null
,I/CheckinTask( 1198): Sending checkin request (9100 bytes)
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4428 uid=10038 gids={50038}
,E/TodoTaskNotifyService( 4305): java.lang.NullPointerException
,W/System.err( 4305): java.lang.NullPointerException
W/System.err( 4305): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4305): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4305): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4305): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4305): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  903): releaseWL(42e36dc8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  903): releaseWL(43b54068): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4305): stopSelfResult true
W/ActivityThread( 1198): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4140/10026)
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4442 uid=10077 gids={50077}
,D/Process (  903): killProcessQuiet, pid=4091
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1198): [NET] getaddrinfo-, 1
,D/libc    ( 1198): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =dd0d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
I/ActivityManager(  903): Killing 4091:com.google.android.music:main/u0a154 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4140/10026)
,I/ActivityManager(  903): Recipient 4091
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  903): Client com.google.android.music (pid 4091): Died!
,D/SMSBackup( 4442): Got a database change event
,D/Process (  903): killProcessQuiet, pid=4140
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  903): Killing 4140:com.facebook.katana/u0a26 (adj 15): empty #17
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 263
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1198): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1198): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,I/ActivityManager(  903): Recipient 4140
,D/PMS     (  903): acquireWL(4487d4e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1468 10028 null
,D/PMS     (  903): acquireWL(42d3da70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1468 10028 null
,D/PMS     (  903): releaseWL(4487d4e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(42d3da70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): acquireWL(449a1c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10028 null
,D/PMS     (  903): releaseWL(449a1c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1198/10028)
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1198/10028)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: survey data missing!
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3988): environment dirty rate=20 [20][4][0]
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1532): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1198): awaiting user notification for token
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{4252e728 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.google.android.gms 2 9 3 12
,I/CheckinTask( 1198): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1198): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): releaseWL(43a63b38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/ActivityThread( 1198): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4266a068 that was originally bound here
E/ActivityThread( 1198): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4266a068 that was originally bound here
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
,I/GCM     ( 1357): GCM config loaded
,D/Messaging( 4377): mNeedToUpdateDate2 start
,D/MmsConfig( 4377): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4377): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4377): 
D/MmsAsyncWorkHandler( 4377): HM tk = 20001
,D/ReportIndicatorCache( 4377): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4377): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@424dd768
,I/Messaging( 4377): mccmnc> 
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4377): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4377): [DraftCache/1] refresh
,D/MmsConfig( 4377): networkCode: 
,D/Messaging( 4377): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1213): sku_id=99
,D/PhoneStorageUtil( 4377): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4377): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4377): createReceiver
,D/MessageCustFlag( 4377): sense_version=6.0
,D/Jerry   ( 4377): start to preload cursor >>>>>>>
,D/TelephUtils( 1213): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,V/MmsProvider( 1213): Update uri=content://mms, match=0
,D/DraftCache( 4377): [DraftCache/451] rebuildCache
,V/MmsProvider( 1213): selection=st=129 AND m_type!=134
,D/Messaging( 4377): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4377): TransactionService is going to be woken up.
,V/TransactionService( 4377): 1-Creating TransactionService
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/Jerry   ( 1213): URI_DRAFT
V/TransactionService( 4377): onStartCommand: 1
,D/MmsSystemEventReceiver( 4377): unRegisterForConnectionStateChanges
V/TransactionService( 4377): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4377): Loading previous transactions.
,D/DraftCache( 4377): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4377): [DraftCache/451] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4377): 
D/MmsAsyncWorkHandler( 4377): HM tk = 20002
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/PMS     (  903): releaseWL(43557ba8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/AccFlag ( 1213): device_type: 1
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1213):  phoneType = -1
D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/TransactionService( 4377): Force set service start id to 1
V/TransactionService( 4377): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4377): unRegisterForConnectionStateChanges
D/TransactionService( 4377): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4377): Destroying TransactionService
V/TransactionService( 4377): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4377): mNeedToUpdateDate2: false
D/Messaging( 4377): ViewCache CreatePreload
,D/Messaging( 4377): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1213): sku_id=99
,D/Cust_MMSMS( 4377): _has_set_default_values_2=true
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MsgPreferenceUtils( 4377): def_index: 0
,D/Messaging( 4377): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MsgPreferenceUtils( 4377): globalIndex = 1
,D/AccFlag ( 1213): sku_id=99
,D/MsgPreferenceUtils( 4377): phone state: true
D/MsgPreferenceUtils( 4377): sd state: false
,D/MsgPreferenceUtils( 4377): vIndex = 0
,I/GAV2    ( 4231): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  903): killProcessQuiet, pid=3416
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3416:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3416
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4352, uid=10111, userID:0
,D/Process (  903): killProcessQuiet, pid=4202
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 4202:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4202
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=4110
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4110:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4110
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/AutoSetting( 4186): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4186): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4186): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{435cc7e8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
W/Prism.AllAppsManager( 1245): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1221): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/Launcher( 1245): Deferring update until onResume
D/Launcher( 1245): waitUntilResume // bindAppsUpdated
,I/[PluginManager]RegisterService( 4186): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 4186): handle notify Blinkfeed plugin client changed
,D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/ActivityManager(  903): Resuming delayed broadcast
,I/PeopleContactsSync( 1198): CP2 sync disabled
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4488 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,D/PMS     (  903): acquireWL(43c09a90): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,E/ExternalAccountType( 1308): Unsupported attribute readOnly
,D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  903): releaseWL(43c09a90): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4488, uid=10073, userID:0
,D/Finsky  ( 4488): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4488/10073)
,D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4488/10073)
,D/Finsky  ( 4488): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4488): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4488): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4488, uid=10073, userID:0
,D/Finsky  ( 4488): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4488): [1] 2.run: Finished loading 1 libraries.
,D/Process (  903): killProcessQuiet, pid=4231
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4231:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/IcingCorporaProvider( 2641): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  903): Recipient 4231
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(4497c708): PARTIAL_WAKE_LOCK  AsyncService 0x1 3631 10160 null
,D/PMS     (  903): releaseWL(4497c708): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4488): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4488): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm-heap( 3631): Grow heap (frag case) to 13.528MB for 1821008-byte allocation
,I/IcingCorporaProvider( 2641): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] 
,W/PackageManager(  903): Unable to load service info ResolveInfo{42fea860 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@42566fb0 +
,I/Prism.WidgetManager( 1245): onLoadItems() +
,D/PMS     (  903): acquireWL(42f338d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
,V/AlarmManager(  903): sending alarm PendingIntent{449ab940: PendingIntentRecord{42f81f70 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449683660178, Int=0
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
,D/PMS     (  903): releaseWL(42f338d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4488): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4488): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/asset   ( 1245): Copying FileAsset 0x67d094b8 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1245): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1245): onLoadItems() -
,I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@42566fb0 -
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4488): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4488): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4488): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/PhoneApp( 1213): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1213): -- N1 =0
,D/PhoneApp( 1213): -- N2 =0
,D/PhoneApp( 1213): -- N3 =0
,D/PMS     (  903): acquireWL(44021a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(44021a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
,D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(42fe9780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4279a400: PendingIntentRecord{42e5a960 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=138616, Int=0
,D/PMS     (  903): acquireWL(43fdd5d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): releaseWL(42fe9780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(440bc008): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43fdd5d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(440bc008): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 4186): service - mHandler: update timezone
,D/AutoSetting( 4160): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4160): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4160): service - onCreate()
,D/AutoSetting( 4160): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4160): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4160): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4160): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4160): service - mHandler: update timezone
,D/AutoSetting( 4160): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4160): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4160): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4160): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1532): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1103): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{42688c00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.htc.htclocationservice 1 10 1 11
,D/PMS     (  903): acquireWL(4487d7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4487d7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 4186): service - handleMessage() stop self
,D/AutoSetting( 4186): service - handleMessage() quit looper
,D/AutoSetting( 4186): service - onDestroy() END
,D/PMS     (  903): acquireWL(43fdd898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{43c62eb8: PendingIntentRecord{42f369f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141734, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{42aa30c0: PendingIntentRecord{42e94c98 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141921, Int=0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,V/AlarmManager(  903): sending alarm PendingIntent{43c9ca78: PendingIntentRecord{42d6e1d8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449683675371, Int=0
,D/PMS     (  903): acquireWL(444ef718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10028 null
,D/PMS     (  903): releaseWL(444ef718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC <<
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(4456ec98): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(43fdd898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5e1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243,
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Finsky  ( 4488): [1] 5.onFinished: Installation state replication succeeded.
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): releaseWL(4456ec98): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43bcd340 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  903): acquireWL(42f51fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=169397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42f51fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4160): service - handleMessage() stop self
,D/AutoSetting( 4160): service - onDestroy() END
,D/AutoSetting( 4160): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4277
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4277:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4277
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1213): switchBindHtcMsgCursor: null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/Process (  903): killProcessQuiet, pid=4322
,I/ActivityManager(  903): Killing 4322:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4322
,D/PMS     (  903): acquireWL(4443dbc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4443dbc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(449cc3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=229396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(449cc3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43a0a850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{42d22398: PendingIntentRecord{4310a248 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231496, Int=0
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4539 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{42eac7b0: PendingIntentRecord{42eb4f18 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449683752547, Int=10800000
,D/PMS     (  903): releaseWL(43a0a850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10047}
,D/PMS     (  903): acquireWL(439b2458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231499, Int=120000
,D/PMS     (  903): releaseWL(439b2458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4539/10047)
,D/Process (  903): killProcessQuiet, pid=4337
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4337:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4337
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(42f192a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f192a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(44559778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=289397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(44559778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42f85b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f85b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42dc9110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42dc9110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43a38c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=349397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43a38c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(42eefa00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=351499, Int=120000
,D/PMS     (  903): releaseWL(42eefa00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3851): Toggling radios to false
I/jxcore-log( 3851): 
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  903): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42d55258 mBinding = false
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1466
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
,W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 2(ms)
,D/BluetoothManagerService(  903): Message: MESSAGE_DISABLE
D/BluetoothManagerService(  903): Sending off request.
,D/WifiManager( 3851): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/BluetoothAdapterState( 3896): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3896): Setting state to 13
I/BluetoothAdapterState( 3896): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 3896): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  903): +onBluetoothStateChange prev=12 new=13
,D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapterProperties( 3896): onBluetoothDisable()
I/bt-btm  ( 3896): BTM_SetDiscoverability
I/bt-btm  ( 3896): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
I/BluetoothAdapterState( 3896): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 3896): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterProperties( 3896): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  903): Bluetooth State Change Intent: 12 -> 13
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1467
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
D/bt-btm  ( 3896): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3896): br_edr_supported=0x0
I/bt-btm  ( 3896): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3896): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3896): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3896): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3896): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3896): BTM_SetConnectability
I/bt-btm  ( 3896): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode with no scan rsp
,I/bt-btm  ( 3896): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/WifiService(  903): setWifiEnabled: false pid=3851, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/BluetoothAdapterProperties( 3896): Scan Mode:20
E/BTIF_CORE( 3896): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 3896): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothAdapterState( 3896): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/IntentController( 1103): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
I/bt-btif ( 3896): BTA_JvDeleteRecord
I/bt-btif ( 3896): BTA_JvRfcommStopServer
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:15
D/bt-btm  ( 3896): BTM_FreeSCN 
E/bt-btif ( 3896): bta_jv_rfcomm_stop_server
I/bt-btif ( 3896): BTA_JvDeleteRecord
I/bt-btif ( 3896): BTA_JvRfcommStopServer
D/bt-btm  ( 3896): BTM_FreeSCN 
I/bt-btif ( 3896): BTA_JvDeleteRecord
I/bt-btif ( 3896): BTA_JvRfcommStopServer
D/bt-btm  ( 3896): BTM_FreeSCN 
I/bt-btif ( 3896): BTA_JvDeleteRecord
I/bt-btm  ( 3896): BTA_JvRfcommStopServer
I/bt-btif ( 3896): BTA_JvRfcommStopServer
D/bt-btm  ( 3896): BTM_FreeSCN 
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 3896): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3896): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 3896): bta_jv_rfcomm_stop_server
I/bt-btif ( 3896): BTA_JvDeleteRecord
I/bt-btm  ( 3896): BTA_JvRfcommStopServer
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 3896): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3896): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:11
V/BluetoothPbapReceiver( 3896): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3896): ***********state = 13
I/bt-btif ( 3896): SDP_DeleteRecord ok, n
D/bt-btm  ( 3896): BTM_FreeSCN 
E/bt-btif ( 3896): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3896): BTM_SEC_CLR[17]: id 56
I/bt-btif ( 3896): BTA_JvDeleteRecord
I/bt-btif ( 3896): BTA_JvRfcommStopServer
D/bt-btm  ( 3896): BTM_FreeSCN 
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 3896): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3896): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
I/bt-btm  ( 3896): Write Extended Inquiry Response to controller
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
I/bt-btm  ( 3896): BTM_SetDiscoverability
I/bt-btm  ( 3896): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3896): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3896): br_edr_supported=0x0
I/bt-btm  ( 3896): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3896): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3896): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3896): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3896): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3896): BTM_SetConnectability
I/bt-btm  ( 3896): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3896): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3896): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
I/bt-btm  ( 3896): BTM_IsInquiryActive
I/bt-btm  ( 3896): BTM_CancelRemoteDeviceName()
W/bt-btif ( 3896): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3896): BTM_FreeSCN 
I/bt-btm  ( 3896): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3896): SDP_,DeleteRecord ok, num_records:6
D/bt-btm  ( 3896): BTM_FreeSCN 
I/bt-btm  ( 3896): BTM_SEC_CLR[4]: id 29
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
D/bt-avp  ( 3896): AVRC_Close handle:0
V/BluetoothSapService( 3896): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 3896): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3896): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3896): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 3896): GATT_Deregister gatt_if=3
I/bt-att  ( 3896): GATT_Deregister gatt_if=4
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
E/BtOppRfcommListener( 3896): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 6(ms)
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 3960): Received state change = 13
,D/PMS     (  903): acquireWL(434c2f98): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 3896 1002 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@424fd4b8
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3960): onDeInitialized
D/BluetoothRemoteDevices( 3896): Wake lock Aquired
,D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3960): cancelAllNotification
,D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3960): getNotificationManager
D/BluetoothMasReceiver( 3896): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 3896): SapReceiver onReceive 
,V/BluetoothSapReceiver( 3896): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3896):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 3896): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 3896): Pbap Service closeService in
D/PMS     (  903): acquireWL(43191b00): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3316 1000 null
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3960): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3960):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 3960): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3960): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3960): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3960):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 3960): deinit: 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3960): disableBatteryAlarm
D/BluetoothManagerService(  903): Message: MESSAGE_UNREGISTER_ADAPTER
D/BluetoothManagerService(  903): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43160e28:true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3960): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3960): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3960): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3960): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3960): setPendingRequestAlarm: false, mContext = null, null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3960): Exit IdleState
D/PMS     (  903): releaseWL(43191b00): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  903): acquireWL(43b3a700): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3316 1000 null
,D/DockEventReceiver( 3316): finishStartingService: stopping service
,D/WirelessDisplayService(  903): getMirrorDisplayStatus:falsecurState:1
I/jxcore-log( 3851): Radios toggled
I/jxcore-log( 3851): 
V/BluetoothPbapService( 3896): successfully stopped pbap service
,V/BluetoothPbapService( 3896): Pbap Service closeService out
V/BluetoothSapService( 3896): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3896): state: 13
D/WifiPerfLock(  903): release()
,D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
,D/BluetoothAdapter( 3896): 1112476640: getState(). Returning 13
D/BluetoothPbap( 3816): Proxy object disconnected
D/PbapServerProfile( 3816): Bluetooth service disconnected
D/BluetoothPbap( 3316): Proxy object disconnected
D/PbapServerProfile( 3316): Bluetooth service disconnected
,V/BluetoothSapService( 3896): Stopping SAP server process
I/ActivityManager(  903): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4563 uid=10037 gids={50037, 3002, 3001}
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): releaseWL(43b3a700): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): Power_Mode_Type mode = 0
I/wpa_supplicant( 3988): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
V/BluetoothSapService( 3896): Sap Service closeSapService in
D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
V/BluetoothSapService( 3896): Close listen Socket : 
V/BluetoothSapService( 3896): Close rfcomm Socket : 
V/BluetoothSapService( 3896): Close sapd  Socket : 
,V/BluetoothSapReceiver( 3896): BluetoothSapReceiver deinit
I/QuickSettingBluetooth( 1103): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/WifiNative-wlan0(  903):    returned true
,D/PhoneStatusBar( 1103): removeIcon slot=bluetooth index=12 viewIndex=0
D/DhcpStateMachine(  903): [RunningState] Stop DHCP
V/BluetoothSapService( 3896): successfully stopped Sap service
V/BluetoothSapService( 3896): Sap Service closeSapService out
D/PMS     (  903): acquireWL(445bbcb0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/SapServerProfile( 3816): Bluetooth service disconnected
I/BtOppRfcommListener( 3896): stopping Accept Thread
I/BtOppRfcommListener( 3896): BluetoothSocket listen thread finished
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/SapServerProfile( 3316): Bluetooth service disconnected
V/BluetoothPbapService( 3896): Pbap Service onDestroy
V/BluetoothPbapService( 3896): Pbap Service closeService in
V/BluetoothPbapService( 3896): Pbap Service closeService out
V/BluetoothSapService( 3896): onUnbind: android.bluetooth.IBluetoothSap
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
V/BluetoothSapService( 3896): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@42529368
V/BluetoothSapService( 3896): Sap Service closeSapService in
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/BluetoothSapService( 3896): Close listen Socket : 
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
V/BluetoothSapService( 3896): Close rfcomm Socket : 
V/BluetoothSapService( 3896): Close sapd  Socket : 
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  903):    returned null
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20465 mDataStallAlarmIntent=null
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
V/BluetoothSapService( 3896): Sap Service closeSapService out
,V/BluetoothSapService( 3896): ***onDestroyed***
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  903): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): Call handleNetworkDisconnect() in SupplicantStoppingState
,D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
D/WifiP2pService(  903): P2pDisablingState
D/WifiP2pService(  903): P2pDisablingState{ when=-7ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): p2p socket connection lost
D/WifiDisplayController(  903): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiP2pService(  903): P2pDisabledState
D/WifiDisplayController(  903): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  903): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  903): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  903): P2pDisabledState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  903):  WFD CtrlPort: 0
D/WifiP2pService(  903):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  903):  WFD CtrlPort: 0
D/WifiP2pService(  903):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  903): updateConnection
I/WifiDisplayController(  903): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  903): updateConnection enter step 4
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3988): Power_Mode_Type mode = 0
I/wpa_supplicant( 3988): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 61
D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3988): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3988): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
V/AudioService(  903): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  903):     Client/Owner: Client
V/AudioService(  903):     GroupId: 
V/AudioService(  903):     Passphrase: 
V/AudioService(  903):     SessionId: 0
V/AudioService(  903):     IP Address: }
D/HtcEffectManagerBase(  903): onEventChanged id=5 status=false
D/HtcEffectManager(  903): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  903): convertEffect before=902
,D/HtcEffectManager(  903): convertEffect after=902
,D/WifiNative-wlan0(  903):    returned true
D/HtcBtWidget_BTWidgetProvider( 4563): onBTStateChanged() for widget: 
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiDisplayController(  903): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/WifiP2pService(  903): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/HtcBtWidget_BTWidgetProvider( 4563): updateWidget(context) for widget: 
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/Process (  903): killProcessQuiet, pid=4352
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
I/ActivityManager(  903): Killing 4352:com.google.android.talk/u0a111 (adj 15): empty #17
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
,D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/WifiNative-p2p0(  903): doBoolean: TERMINATE
W/WifiHW  (  903): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 3988): Supplicant Terminat @ wpa_supplicant_deinit function
D/WifiNative-p2p0(  903):    returned true
D/wpa_supplicant( 3988): TDLS: Tear down peers
,I/wpa_supplicant( 3988): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] entry_id:3   entry:0xb75bd0f8  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb75b8f98  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb75bd428  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb75bd2d8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb75bd4f0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  903): acquireWL(430fbe18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10028 null
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=-32ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1103): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  903): acquireWL(448cde38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10028 null
D/PMS     (  903): releaseWL(448cde38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
I/IntentController( 1103): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 3988): Clean 'force_connect' when disconnect
I/wpa_supplicant( 3988): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 3988): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 3988): TDLS: Remove peers on disassociation
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3988): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8297bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 3988):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3988): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 3988): State: COMPLETED -> DISCONNECTED
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  903): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING - ret = 0
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 3988): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3988): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WIFI_ICON( 1103): up,dateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  903): acquireWL(42f84ec8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1357/10028)
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 3988): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3988): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3988): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/PMS     (  903): releaseWL(430fbe18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/ActivityManager(  903): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4582 uid=10048 gids={50048}
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,E/BluetoothFtpService:RfcommSocketAcceptThread( 3896): Shutdown
,I/QuickSettingWifi( 1103): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,D/BluetoothMasReceiver( 3896): Bluetooth STATE CHANGED to 13
D/PMS     (  903): releaseWL(42f84ec8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
,D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3960): Received state change = 13
I/QuickSettingWifi( 1103): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,W/bt-btif ( 3896): ag scb idx 1 not allocated
,W/bt-btif ( 3896): ag scb idx 2 not allocated
E/bt-btif ( 3896): BTA AG is already disabled, ignoring ...
,D/Process (  903): killProcessQuiet, pid=4401
W/bt-l2cap( 3896): L2CAP - PSM: 0x0019 not found for deregistration
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/bt-l2cap( 3896): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3896): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3896): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3896): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3896): L2CAP - PSM: 0x0017 not found for deregistration
I/ActivityManager(  903): Killing 4401:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4401
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,D/HtcWiFiWidget_WiFiWidgetProvider( 4582): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4582): updateWidget(context) for widget: 
,D/Process (  903): killProcessQuiet, pid=3802
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  903): Killing 3802:com.htc.calendar/u0a13 (adj 15): empty #17
,E/bt_userial_mct( 3896): userial_close userial_thread_created userial_running is 1 
I/ActivityManager(  903): Recipient 4352
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3802
,E/wpa_supplicant( 3988): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 3988): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 3988): nl80211: wpa_driver_nl80211_deinit
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/wpa_supplicant( 3988): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3988): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3988): nl80211: Unsubscribe mgmt frames handle 0xb8298718 (mode change)
I/wpa_supplicant( 3988): htc_wext_command_deinit +
I/wpa_supplicant( 3988): htc_wext_command_deinit -
E/wpa_supplicant( 3988): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
,I/wpa_supplicant( 3988): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 3988): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 3988): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 3988): TDLS: Tear down peers
I/wpa_supplicant( 3988): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3988): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3988): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3988): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3988): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3988): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3988): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3988): send_and_recv error 0 - cmd 18
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,I/bt-btif ( 3896): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 3896): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3896): Received stop request...Stopping profile...
,D/BluetoothHeadset(  903): Proxy object disconnected
,D/BluetoothHeadset( 1213): Proxy object disconnected
D/BluetoothHeadset( 3316): Proxy object disconnected
D/HeadsetProfile( 3316): Bluetooth service disconnected
,D/BluetoothHeadset( 1213): Proxy object disconnected
D/BluetoothHeadset( 1103): Proxy object disconnected
,I/QuickSettingMiniLite( 1103): btListener.disconnect:HEADSET
D/BluetoothPhoneService( 1213): BluetoothHeadset onServiceDisconnected
,D/BluetoothAdapterState( 3896): Stopping profile services that were post enabled
D/BluetoothHeadset( 3816): Proxy object disconnected
,D/HeadsetProfile( 3816): Bluetooth service disconnected
D/A2dpService( 3896): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3896): doQuit
,D/A2dpStateMachine( 3896): Exit Disconnected: -1
,D/BluetoothA2dp(  903): Proxy object disconnected
D/BluetoothA2dp( 3816): Proxy object disconnected
D/A2dpProfile( 3816): Bluetooth service disconnected
D/BluetoothA2dp( 3316): Proxy object disconnected
,D/A2dpProfile( 3316): Bluetooth service disconnected
,D/HidService( 3896): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 3316): Proxy object disconnected
,D/HidProfile( 3316): Bluetooth service disconnected
D/BluetoothInputDevice( 3816): Proxy object disconnected
D/HidProfile( 3816): Bluetooth service disconnected
,D/HealthService( 3896): Received stop request...Stopping profile...
,D/PanService( 3896): Received stop request...Stopping profile...
D/PanService( 3896): stop
,D/PanService( 3896): stop: mTetherAc send disconnect
,D/BluetoothTethering(  903): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  903): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  903): attempted to stop reverse tether with nothing tethered
,D/BluetoothAdapterService( 3896): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothPan(  903): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 3316): BluetoothPAN Proxy object disconnected
D/PanProfile( 3316): Bluetooth service disconnected
D/BluetoothPan( 3816): BluetoothPAN Proxy object disconnected
,D/PanProfile( 3816): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 3896): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3896): Cleaning up Bluetooth Handsfree callback object
D/BtGatt.DebugUtils( 3896): handleDebugAction() action=null
,D/BtGatt.GattService( 3896): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3896): stop()
D/BluetoothAdapterService( 3896): Profile still running: com.android.bluetooth.hdp.HealthService
,D/A2dpStateMachine( 3896): cleanup
,D/Avrcp   ( 3896): Unregistering previous receiver
,D/BluetoothAdapterService( 3896): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3896): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3896): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3896): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3896): Profile still running: com.android.bluetooth.pan.PanService
,W/BluetoothHealthServiceJni( 3896): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3896): Cleaning up Bluetooth Health object
D/PanService( 3896): CMD_CHANNEL_DISCONNECTED
D/PanService( 3896): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 3896): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 3896): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3896): Cleaning up Bluetooth PAN callback object
,E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
W/WifiHW  (  903): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
,I/wpa_ctrl(  903): [wpa_ctrl_close] ctrl=0x63fcb758
I/wpa_ctrl(  903): [wpa_ctrl_close] ctrl=0x63053c90
,W/WifiHW  (  903): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/BluetoothAdapterState( 3896): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3896): Setting state to 10
,I/BluetoothAdapterState( 3896): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3896): Broadcasting updateAdapterState() to 1 receivers.
,D/WifiStateMachine(  903): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  903): doBoolean: SET_WIFI_ON 0
,D/BluetoothManagerService(  903): +onBluetoothStateChange prev=13 new=10
D/WifiNative-wlan0(  903):    returned false
,D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
I/BluetoothAdapterState( 3896): Entering OffState
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothManagerService(  903): Broadcasting onBluetoothStateChange(false) to 20 receivers.
D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  903): WIFI Trun OFF
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/BluetoothHeadset( 1213): onBluetoothStateChange: up=false
,I/IntentController( 1103): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1103): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothHeadset( 1213): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1103): onBluetoothStateChange: up=false
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothHeadset( 3816): onBluetoothStateChange: up=false
D/HtcWiFiWidget_WiFiWidgetProvider( 4582): onWiFiStateChanged() for widget: 
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
E/WifiStateMachine(  903): [MLHD] Error! unhandled message 6 { when=-127ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/HtcWiFiWidget_WiFiWidgetProvider( 4582): updateWidget(context) for widget: 
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1103): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  903): acquireWL(44940e98): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WIFI_ICON( 1103): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1103): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/BluetoothA2dp( 3816): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3816): onBluetoothStateChange: up=false
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
D/BluetoothSap( 3816): onBluetoothStateChange on: false
D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothMap( 3816): onBluetoothStateChange: up=false
D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/BluetoothMap( 3816): 
E/BluetoothMap( 3816): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@4250cb20
E/BluetoothMap( 3816): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3816): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3816): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3816): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3816): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3816): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3816): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothInputDevice( 3816): onBluetoothStateChange: up=false
D/BluetoothHeadset(  903): onBluetoothStateChange: up=false
D/BluetoothA2dp(  903): onBluetoothStateChange: up=false
D/BluetoothPbap( 3316): onBluetoothStateChange: up=false
W/BluetoothHeadset( 1103): Proxy not attached to service
D/BluetoothA2dp( 3316): onBluetoothStateChange: up=false
I/QuickSettingMiniLite( 1103): updateLiteState:no connect device!
D/BluetoothHeadset( 3316): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3316): onBluetoothStateChange: up=false
D/BluetoothMap( 3316): onBluetoothStateChange: up=false
E/BluetoothMap( 3316): 
E/BluetoothMap( 3316): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@426887b8
E/BluetoothMap( 3316): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3316): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3316): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3316): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3316): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3316): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3316): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothSap( 3316): onBluetoothStateChange on: false
D/BluetoothManagerService(  903): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  903): Broadcasting onBluetoothServiceDown() to 11 receivers.
D/BluetoothAdapter( 1468): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42756cf8
D/BluetoothAdapter( 1468): onBluetoothServiceDown: done
D/BluetoothAdapter( 1741): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42ae9280
D/BluetoothAdapter( 1741): onBluetoothServiceDown: done
D/BluetoothAdapter( 3851): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4303d908
D/BluetoothAdapter( 3851): onBluetoothServiceDown: done
D/BluetoothAdapter(  903): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42d55258
D/BluetoothAdapter(  903): onBluetoothServiceDown: done
D/BluetoothAdapter( 1213): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4259a1f0
D/BluetoothAdapter( 1213): onBluetoothServiceDown: done
D/BluetoothAdapter( 1221): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42610000
D/BluetoothAdapter( 1221): onBluetoothServiceDown: done
I/QuickSettingWifi( 1103): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
D/BluetoothAdapter( 1103): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@428f00e0
D/,BluetoothAdapter( 1103): onBluetoothServiceDown: done
D/BluetoothAdapter( 3816): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424f4f28
D/BluetoothDevice( 3816): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 3816): onBluetoothServiceDown: done
D/BluetoothAdapter( 3316): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@426728e8
D/BluetoothAdapter( 3316): onBluetoothServiceDown: done
D/BluetoothAdapter( 3896): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@424ef050
D/BluetoothDevice( 3896): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 3896): onBluetoothServiceDown: done
D/BluetoothAdapter( 3960): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424fdd88
D/BluetoothAdapter( 3960): onBluetoothServiceDown: done
D/BluetoothManagerService(  903): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42d55258 mBinding = false
D/BluetoothManagerService(  903): Sending unbind request.
D/BluetoothManagerService(  903): Bluetooth State Change Intent: 13 -> 10
I/IntentController( 1103): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/LocalBluetoothProfileManager( 3316): setBluetoothStateOff
D/HtcTagManager( 3316): stopProxy
D/NfcHandover( 1221): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/BluetoothAdapterService( 3896): Cleaning up adapter native....
D/LocalBluetoothProfileManager( 3816): setBluetoothStateOff
,I/bt-btif ( 3896): HAL bt_hal_cbacks->thread_evt_cb
,D/PMS     (  903): releaseWL(434c2f98): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/HtcTagManager( 3816): stopProxy
I/QuickSettingWifi( 1103): receive.wifiConnect:false wifiAPname:null elapse:1
D/BluetoothAdapterService( 3896): Done cleaning up adapter native....
D/BluetoothAdapterService(1112458464)( 3896): ****onDestroy()********
D/BtGatt.GattService( 3896): cleanup()
W/bt-btif ( 3896): GATTC Module not enabled/already disabled
W/bt-btif ( 3896): GATTS Module not enabled/already disabled
D/BluetoothMasReceiver( 3896): Bluetooth STATE CHANGED to 10
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3960): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@424fd4b8
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3960): deinitLeServices: null
V/BluetoothMasService( 3896): onDestroy: mIsEmailEnabled: true
,D/TetherPref( 3316): persistRestoreBluetoothState false
,D/TetherPref( 3816): persistRestoreBluetoothState false
D/PMS     (  903): acquireWL(432a51a0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3316 1000 null
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/HtcBtWidget_BTWidgetProvider( 4563): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4563): updateWidget(context) for widget: 
,D/DockEventReceiver( 3316): finishStartingService: stopping service
D/PMS     (  903): releaseWL(432a51a0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  903): acquireWL(44a2f920): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3316 1000 null
,D/PMS     (  903): releaseWL(44a2f920): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothMasReceiver( 3896): Bluetooth STATE CHANGED to 10
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3960): Received state change = 10
,D/BluetoothAdapter( 3816): 1112491200: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1103): 1115170632: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1103): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/Process (  903): killProcessQuiet, pid=4305
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4305:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4305
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4603 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/PMS     (  903): acquireWL(44994ba0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(44994ba0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1468/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/CaptivePortalTracker(  903): NoActiveNetworkState
V/Tethering(  903): bSetPropertyMultiRAB:false
,I/ConnectivityHelper( 1245): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1760/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1245/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/MusicStore( 4603): Database version: 95
,W/ContextImpl( 4603): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4603): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Netd    (  364): No subsystem found in netlink event
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
V/Tethering(  903): remove iface:wlan0
D/Tethering(  903): interfaceRemoved wlan0
,E/Tethering(  903): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4603, uid=10154, userID:0
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.music (pid 4603): Registered
,I/MediaRouter( 4603): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (4603/10154)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2205/10021)
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4623 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4603): getSelectedRoute
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4603/10154)
I/NetworkMonitor( 4603): type=WIFI subType= reason=null isConnected=false
,D/Process (  903): killProcessQuiet, pid=4428
,D/ACRA    ( 4623): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 4428:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/Tethering(  903): interfaceLinkStateChanged p2p0, false
D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/ACRA    ( 4623): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4623): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4603, uid=10154, userID:0
I/ActivityManager(  903): Recipient 4428
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4623): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4623): Preparing secondary program dexes.
V/DexLibLoader( 4623): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4623): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4623): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4623): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4623): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4623): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4623): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4623): Dex already copied
D/OdexVerifier( 4623): Odex verification is skipped.
,V/DexLibLoader( 4623): Creating class loader
,V/DexLibLoader( 4623): Finished creating class loader
V/DexLibLoader( 4623): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4623): Dex already copied
D/OdexVerifier( 4623): Odex verification is skipped.
,V/DexLibLoader( 4623): Creating class loader
,V/DexLibLoader( 4623): Finished creating class loader
V/DexLibLoader( 4623): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4623): Dex already copied
D/OdexVerifier( 4623): Odex verification is skipped.
,V/DexLibLoader( 4623): Creating class loader
,V/DexLibLoader( 4623): Finished creating class loader
V/DexLibLoader( 4623): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4623): Dex already copied
D/OdexVerifier( 4623): Odex verification is skipped.
,V/DexLibLoader( 4623): Creating class loader
,V/DexLibLoader( 4623): Finished creating class loader
,V/DexLibLoader( 4623): Verifying classes from secondary dexes.
,D/DexLibLoader( 4623): DexLibLoader.ensureDexLoaded took 35 ms
,W/Netd    (  364): No subsystem found in netlink event
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,V/Tethering(  903): remove iface:p2p0
D/Tethering(  903): interfaceRemoved p2p0
,E/Tethering(  903): attempting to remove unknown iface (p2p0), ignoring
,W/dalvikvm( 4623): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=-1s882ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  903): releaseWL(44940e98): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4623): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4623): Verify
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4623): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4623): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/PMS     (  903): acquireWL(4446eae8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1198 10028 null
,D/PMS     (  903): acquireWL(4357ff00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(4446eae8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/GCM     ( 1357): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1357/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): releaseWL(4357ff00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/Process (  903): killProcessQuiet, pid=4442
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4442:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/AutoSetting( 4186): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  903): Recipient 4442
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4645 uid=10078 gids={50078, 3003, 5012}
,W/fb4a(:<default>):UserScope( 4623): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (4186/10053)
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4623): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutoSetting( 4186): Util - no network available!
,D/AutoSetting( 4186): service - onCreate()
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (4186/10053)
D/AutoSetting( 4186): service - AddressCache: using context: com.htc.Weather
W/fb4a(:<default>):UserScope( 4623): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/AutoSetting( 4186): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  903): request 42e7b418 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  903): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4186): service - mHandler: cancel location update
D/AutoSetting( 4186): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4645): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4645): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4645): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4645): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4662 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4645/10078)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4645/10078)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4645/10078)
,E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4623): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4623): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4623): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4623): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4623): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4623): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4623): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4623): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4623): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4623): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4623): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 9.915MB for 39954-byte allocation
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4676 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=4377
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4377:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 9.991MB for 79892-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 10.073MB for 84664-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 10.087MB for 28144-byte allocation
,I/ActivityManager(  903): Recipient 4377
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 10.254MB for 75760-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4499f380 u0 ReceiverList{43427ad0 4623 com.facebook.katana/10026/u0 remote:43e74260}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4499f380 u0 ReceiverList{43427ad0 4623 com.facebook.katana/10026/u0 remote:43e74260}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44982950 u0 ReceiverList{4338f4a0 4623 com.facebook.katana/10026/u0 remote:43caac40}}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4676): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4676): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,W/GAV2    ( 4676): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4676): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4676): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/PMS     (  903): acquireWL(44821780): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1468 10028 null
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/PMS     (  903): releaseWL(44821780): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1468): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(44548250): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1468 10028 null
D/PMS     (  903): releaseWL(44548250): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4676/10151)
,V/WebViewChromiumFactoryProvider( 4676): Binding Chromium to main looper Looper (main, tid 1) {424d2b38}
,I/LibraryLoader( 4676): Expected native library version number "",actual native library version number ""
I/chromium( 4676): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4676): Initializing chromium process, renderers=0
,D/PMS     (  903): acquireWL(42d29a70): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  903): acquireWL(42c83d30): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4676): BLUETOOTH permission is missing!
D/PMS     (  903): releaseWL(42d29a70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4676): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4676): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4676): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4676): Local Branch: 
I/Adreno-EGL( 4676): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4676): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4676):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4676): Starting up...
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4676/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4676/10151)
,I/dalvikvm-heap( 3631): Grow heap (frag case) to 15.227MB for 1821008-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
,D/Process (  903): killProcessQuiet, pid=4290
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
I/ActivityManager(  903): Killing 4290:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
,I/dalvikvm-heap( 3631): Grow heap (frag case) to 16.963MB for 1821008-byte allocation
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  903): Recipient 4290
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiP2pService(  903): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,D/PMS     (  903): acquireWL(42819130): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4603 10154 null
,W/ContextImpl( 4603): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4603): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4603, uid=10154, userID:0
,D/PMS     (  903): releaseWL(42819130): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4603): Conditions not met for autocaching.
I/MusicLeanback( 4603): Stop autocaching.
,D/PMS     (  903): releaseWL(42c83d30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,W/fb4a(:<default>):UserScope( 4623): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4623): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4623): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/PMS     (  903): acquireWL(4494f390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(4494f390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,I/GAV2    ( 4676): Thread[GAThread,5,main]: No campaign data found.
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(42f196f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1468 10028 null
,D/PMS     (  903): acquireWL(43011b20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1468 10028 null
,D/PMS     (  903): releaseWL(42f196f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(43011b20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{4497e7a8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  903): acquireWL(4400a1b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4400a1b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WirelessDisplayService(  903): HANDLE_WIFI_DIS
,D/WirelessDisplayService(  903): HANDLE_STOP_DIS
,D/WirelessDisplayService(  903): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  903): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4186): service - handleMessage() stop self
,D/AutoSetting( 4186): service - handleMessage() quit looper
,D/AutoSetting( 4186): service - onDestroy() END
,D/PMS     (  903): acquireWL(43d2f170): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(43d2f170): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(43e89bb8): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(43e89bb8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42d3e280): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(42d3e280): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(44508ea0): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  903): releaseWL(44508ea0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(43265f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=409396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43265f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): releaseWL(445bbcb0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1532): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,W/GLSActivity( 1357): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1357): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1357): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1357): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1357): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1357): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1357): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1357): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{42888688 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4488): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4488): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4488): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4488): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4488): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4488): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4488): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4488): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1103): com.google.android.gms 2 9 3 12
,D/libc    ( 4488): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4488): [NET] getaddrinfo-,err=8
D/libc    ( 4488): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4488): [NET] getaddrinfo-, 1
,D/libc    ( 4488): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cafb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =cafb (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=cafb, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 4488): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4488): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  903): acquireWL(42e55588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42e55588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4310b450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=469396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4310b450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(449cfa88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=471499, Int=120000
,D/PMS     (  903): releaseWL(449cfa88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(449de3a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(449de3a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(435f08c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=529396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(435f08c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(449c4610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(449c4610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43d56710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=589396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43d56710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43a7aaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=591499, Int=120000
,D/PMS     (  903): releaseWL(43a7aaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(43c43e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43c43e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/ContactMessageStore( 1213): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1213): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1213): sku_id=99
,D/ContactMessageStore( 1213): start background delete task...
,D/ContactMessageStore( 1213): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1213): size: 0 , 0
,D/ContactMessageStore( 1213): Background delete complete
,D/PMS     (  903): acquireWL(43680258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=649396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43680258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43605f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43605f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43e00660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43e00660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/PowerUI ( 1103): closing low battery warning: level=100
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43a25848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=709397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43a25848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43a68dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711499, Int=120000
,D/PMS     (  903): releaseWL(43a68dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/GLSUser ( 1357): GoogleAccountDataService.getToken()
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1357): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1357): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1532): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1357): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1357): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1357): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1357): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1357): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1357): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1357): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1357): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1103): com.google.android.gms (false,0)
,E/PlayEventLogger( 4488): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4488): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4488): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4488): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4488): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4488): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4488): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4488): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{427f6d98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4488): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4488): [NET] getaddrinfo-,err=8
D/libc    ( 4488): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4488): [NET] getaddrinfo-, 1
D/libc    ( 4488): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6a48 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =6a48 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=6a48, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 4488): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4488): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1103): com.google.android.gms 5 13 4 12
,D/PMS     (  903): acquireWL(42f7b2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f7b2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(42f79e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=769396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42f79e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(439f61a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(439f61a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43191dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=829396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43191dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43e97e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=831499, Int=120000
,D/PMS     (  903): releaseWL(43e97e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(44963bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(44963bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(449c8340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=889396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(449c8340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43c09b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43c09b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43985b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=949396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43985b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4401aac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4401aac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(42efd7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1009397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42efd7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(44e90280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  903): sending alarm PendingIntent{427cc868: PendingIntentRecord{42e05d08 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782937, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=951499, Int=120000
,V/AlarmManager(  903): sending alarm PendingIntent{42cf83b0: PendingIntentRecord{42995fa8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449684472871, Int=900000
,V/AlarmManager(  903): sending alarm PendingIntent{42667620: PendingIntentRecord{42f135f8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449684543926, Int=0
,D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4747 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4747): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4747): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4747): MY_DEBUG = false
,D/SmartSyncUtils( 4747): isEpsOn(), nState = 0
D/PMS     (  903): acquireWL(43ffaa18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4747 1000 null
D/PMS     (  903): releaseWL(44e90280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): releaseWL(43ffaa18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(43a25d10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4747 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4747): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4747): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4747): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4747): SettingOnTime = 1449698400000, randomSettingOnTime = 1449697006000
D/SmartSyncScreenOnOffTimeReceiver( 4747): SettingOffTime = 1449687600000, randomSettingOffTime = 1449687876000
,D/SmartSyncScreenOnOffTimeReceiver( 4747): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4747): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4747): bNightModeTurnOffOnce = false
,D/PMS     (  903): releaseWL(43a25d10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/Process (  903): killProcessQuiet, pid=4488
,I/ActivityManager(  903): Killing 4488:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4488
,D/PMS     (  903): acquireWL(4498d6f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4498d6f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4498ca58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(4498ca58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(448d4cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1069396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(448d4cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(448ce0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1071499, Int=120000
,D/PMS     (  903): releaseWL(448ce0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(4489dbf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4489dbf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(4489d908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1129396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4489d908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(44878d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(44878d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4468ddf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1189396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4468ddf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(445aa3d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1191499, Int=120000
,D/PMS     (  903): releaseWL(445aa3d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(445aa0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(445aa0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(445a9db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1249396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(445a9db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4458f410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4458f410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(44576ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1309397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(44576ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(445767e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1311499, Int=120000
,D/PMS     (  903): releaseWL(445767e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(44576520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(44576520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(445693a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1369396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(445693a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(445049e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(445049e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(444f3cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1429396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(444f3cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(444d2a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1431499, Int=120000
,D/PMS     (  903): releaseWL(444d2a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(444ab658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PMS     (  903): releaseWL(444ab658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(43aeb898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43aeb898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/ContextImpl( 4747): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3316): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3316): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3316): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3316): Cust_ConnectToPC   : spcsc>false
D/        ( 3316): Cust_ConnectToPC   : IPT>true
,D/        ( 3316): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3316): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3316): Index of the first 1 = 3
,W/Settings( 3316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 3316): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3316): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3316): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3316): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d83a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1489397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42d83a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42a79338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42a79338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42fe64c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42fe64c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PowerUI ( 1103): closing low battery warning: level=100
I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d06628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1549396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42d06628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42dce650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1551499, Int=120000
,D/PMS     (  903): releaseWL(42dce650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(4297f9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(4297f9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(42f12668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f12668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42d2eeb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1609396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42d2eeb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(424e0718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(424e0718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42e7a7c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42e7a7c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(429dd900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1669396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(429dd900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4355bfc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1671499, Int=120000
,D/PMS     (  903): releaseWL(4355bfc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(42e463f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42e463f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(42fc53e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42fc53e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(44a03698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1729397, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(44a03698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4367de40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(4367de40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43e82e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43e82e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
,D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42f20ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1789396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42f20ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(444bb838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(444bb838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  903): acquireWL(42f44e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42f44e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/ProcessStatsService(  903): Prepared write state in 30ms
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  903): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-34-54.bin
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/PMS     (  903): acquireWL(42f9beb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{427cc868: PendingIntentRecord{42e05d08 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1733347, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1791499, Int=120000
,V/AlarmManager(  903): sending alarm PendingIntent{42cf83b0: PendingIntentRecord{42995fa8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449685372871, Int=900000
,W/ContextImpl( 4747): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): releaseWL(42f9beb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(43b41ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1849396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43b41ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(443eb548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(443eb548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(44531350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(44531350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43102278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{428e6878: PendingIntentRecord{428d0e40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1909396, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43102278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  903): acquireWL(43e02590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
V/AlarmManager(  903): sending alarm PendingIntent{432bbbf8: PendingIntentRecord{430ff190 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=1911499, Int=120000
D/PMS     (  903): releaseWL(43e02590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
E/cutils-trace( 4789): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4789): ====startRecUseTime====
D/htc.customization.log.level( 4789):  is 
W/CustomizationLogLevel( 4789): Level value is invalid, use default level 2
D/CustomizationManager( 4789):  Read ACC file spent 0.100 (s)
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4789): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4789): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4789): Parsing tag category name = system
I/CustomizationCIDLoader( 4789): Parsing tag category name = application
I/CustomizationCIDLoader( 4789): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4789): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4789): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4789): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4789): Parsing tag category name = Settings
D/CustomizationManager( 4789):  Read CID file spent 0.163 (s)
D/CustomizationManager( 4789):  All configurations done spent 0.163 (s)
W/HtcNativeFlag( 4789): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4789): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4789): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4789): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4789, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  903): killProcessQuiet, pid=3851
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  903): Killing 3851:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  903):   Force finishing activity ActivityRecord{42a75bd0 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  903): Copying FileAsset 0x62f78dc8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1180): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 3851 uid 10348
W/InputDispatcher(  903): channel '42d7a548 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  903): channel '42d7a548 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '42d7a548 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  903): WIN DEATH: Window{42d7a548 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  903): Client connection lost with reason: 4
I/WindowManager(  903): WINDOW DIED Window{42d7a548 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  903): Skipping PackageSetting{42c09b58 com.example.hello/10355} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1532): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1532): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1760): Unregistering com.test.thalitest
E/acms    ( 1760): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1468): Ignoring removeGeofence because network location is disabled.
I/Launcher( 1245): Deferring update until onResume
D/Launcher( 1245): waitUntilResume // bindAppsRemoved
D/PMS     (  903): acquireWL(44e542b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1468 10028 null
D/PMS     (  903): releaseWL(44e542b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/SystemReader( 1221): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
D/VoicemailCleanupService( 1260): Cleaning up data for package: com.test.thalitest
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4805 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
E/ExternalAccountType( 1308): Unsupported attribute readOnly
I/ActivityManager(  903): Delaying start of: ServiceRecord{44557858 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/MultiDex( 4805): install
I/MultiDex( 4805): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/MultiDex( 4805): loading existing secondary dex files
I/MultiDex( 4805): load found 1 secondary dex files
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/MultiDex( 4805): install done
D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1198): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4823 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PMS     (  903): acquireWL(427d6ad8): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
I/Icing   ( 1198): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4805): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  903): releaseWL(427d6ad8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4823): install
I/MultiDex( 4823): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4823): loading existing secondary dex files
I/MultiDex( 4823): load found 1 secondary dex files
I/MultiDex( 4823): install done
I/ActivityManager(  903): Resuming delayed broadcast
I/ProviderInstaller( 4823): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 4186): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  903): Resuming delayed broadcast
I/[PluginManager]RegisterService( 4186): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4841 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  903): killProcessQuiet, pid=4539
I/ActivityManager(  903): Killing 4539:com.htc.aurora/u0a47 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4841, uid=10073, userID:0
W/PackageManager(  903): Unable to load service info ResolveInfo{430fa450 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/Finsky  ( 4841): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4841/10073)
I/ActivityManager(  903): Recipient 4539
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4841/10073)
E/SQLiteLog( 4805): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4805): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca42420
E/DriveAsyncService( 4805): disk I/O error (code 3850)
E/DriveAsyncService( 4805): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4805): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4805): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4805): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4805): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4805): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4805): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4805): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4805): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4805): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4805): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4805): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4805): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4805): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Finsky  ( 4841): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  903): acquireWL(4342fc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
V/AlarmManager(  903): sending alarm PendingIntent{4253b710: PendingIntentRecord{43bf0df8 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1855239, Int=0
V/AlarmManager(  903): sending alarm PendingIntent{42a00df8: PendingIntentRecord{42a1b7f8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449685370972, Int=1800000
W/Settings( 4841): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4841): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4841): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4841): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4841): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4841): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4841): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4841): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4841): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4841): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4841): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4841): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4841): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4841): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4841): threadid=25: thread exiting with uncaught exception (group=0x420a4e30)
E/ActivityManager(  903): App crashed! Process: com.android.vending
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4841, uid=10073, userID:0
E/AndroidRuntime( 4841): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4841): Process: com.android.vending, PID: 4841
E/AndroidRuntime( 4841): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4841): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4841): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4841): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4841): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4841): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4841): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4841): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4841): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4841): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4841): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4805): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4805): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca42420
D/Process (  903): killProcessQuiet, pid=4582
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4582:com.htc.widget.process2/u0a48 (adj 15): empty #17
E/DocListDatabase( 4805): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4805): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4805): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4805): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4805): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4805): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4805): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4805): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4805): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4805): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4805): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4805): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4805): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4805): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4805): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4805): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4805): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4805): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4805): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4805): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4805): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4805): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4841): killProcess, pid=4841
D/Prism.PackageStateRece_( 1245): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4841): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
W/dalvikvm( 4805): threadid=1: thread exiting with uncaught exception (group=0x420a4e30)
E/DropBoxManagerService(  903): Can't write: system_app_crash
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
E/AndroidRuntime( 4805): FATAL EXCEPTION: main
E/AndroidRuntime( 4805): Process: com.google.android.gms.drive, PID: 4805
E/AndroidRuntime( 4805): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4805): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4805): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4805): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4805): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4805): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4805): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4805): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4805): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4805): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4805): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4805): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4805): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4805): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4805): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4805): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4805): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4805): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4805): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4805): 	... 10 more
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
I/IcingCorporaProvider( 2641): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  903): Recipient 4582
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
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
D/Process ( 4805): killProcess, pid=4805
D/Process ( 4805): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4881 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2641): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2641): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x639d6370
W/dalvikvm( 2641): threadid=14: thread exiting with uncaught exception (group=0x420a4e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2641): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2641): Process: com.google.android.googlequicksearchbox:search, PID: 2641
E/AndroidRuntime( 2641): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2641): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2641): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2641): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2641): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2641): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2641): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2641): 	at cid.d(PG:186)
E/AndroidRuntime( 2641): 	at clo.g(PG:594)
E/AndroidRuntime( 2641): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2641): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2641): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2641): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2641): 	at clr.tL(PG:827)
E/AndroidRuntime( 2641): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2641): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2641): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2641): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2641): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2641): killProcess, pid=2641
D/Process ( 2641): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
I/ActivityManager(  903): Recipient 4841
W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/ActivityManager(  903): Process com.android.vending (pid 4841) has died.
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4805
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4805) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2641
D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2641): Died!
D/WifiService(  903): Client connection lost with reason: 4
I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2641) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10921ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20921ms
E/SQLiteDatabase( 4881): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4881): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4881): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4881): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4881): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4881): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4881): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4881): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4881): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4881): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4881): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4881): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4881): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4881): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4881): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4881): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4881): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4881): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4881): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4881): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4881): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4881): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4881): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4881): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4881): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4881): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4881): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4881): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4881): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4881): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4881): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4881): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4881): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4881): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4881): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4881): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4881): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4881): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4881): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4881): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4881): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4881): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4881): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4881): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4881): threadid=11: thread exiting with uncaught exception (group=0x420a4e30)
E/AndroidRuntime( 4881): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4881): Process: com.google.android.apps.docs, PID: 4881
E/AndroidRuntime( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4881): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4881): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4881): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4881): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4881): 	at aho.run(AbstractDatabaseInstance.java:455)
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
D/Process ( 4881): killProcess, pid=4881
D/Process ( 4881): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4897 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Recipient 4881
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4881) has died.
W/ContextImpl( 4897): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4897): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4897): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4897): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4897): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4897): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4897): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4897): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4897): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4897): threadid=10: thread exiting with uncaught exception (group=0x420a4e30)
E/AndroidRuntime( 4897): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4897): Process: com.android.keychain, PID: 4897
E/AndroidRuntime( 4897): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4897): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4897): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4897): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4897): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4897): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4897): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  903): App crashed! Process: com.android.keychain
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4910 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4897): killProcess, pid=4897
D/Process ( 4897): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449685444404.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  903): Recipient 4897
I/ActivityManager(  903): Process com.android.keychain (pid 4897) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20535ms
D/AppTag  ( 4910): getInstance(Context context)
D/AppTag  ( 4910): getInstance(Context context)
D/AppTag  ( 4910): onCreate()
D/PMS     (  903): acquireWL(433e2c78): PARTIAL_WAKE_LOCK  AsyncService 0x1 3631 10160 null
D/PMS     (  903): releaseWL(433e2c78): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4928 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4928): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4928 dbg=false s=true
I/DeviceManagement( 4928): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4928): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]

```
