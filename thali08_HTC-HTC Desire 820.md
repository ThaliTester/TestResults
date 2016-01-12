#### Test 55613145ac448d4_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  907): acquireWL(4246d590): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4246d590): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(41d97630): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
D/PMS     (  907): releaseWL(41d97630): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(41c4adf0): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
D/PMS     (  907): releaseWL(41c4adf0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(424d3080): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
D/PMS     (  907): releaseWL(424d3080): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
E/cutils-trace( 4025): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4025): ====startRecUseTime====
D/htc.customization.log.level( 4025):  is 
W/CustomizationLogLevel( 4025): Level value is invalid, use default level 2
D/CustomizationManager( 4025):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4025): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4025): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4025): Parsing tag category name = system
I/CustomizationCIDLoader( 4025): Parsing tag category name = application
I/CustomizationCIDLoader( 4025): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4025): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4025): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4025): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4025): Parsing tag category name = Settings
D/CustomizationManager( 4025):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4025):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4025): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4025): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4025): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4025): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4025
D/PMS     (  907): acquireHCC(42215158): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(421a3028): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x6f26d400 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1109913248
D/PMS     (  907): acquireWL(41edc478): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1249): [onPause]
I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d883b8
I/SocialFeedProvider( 1249): +onPause
I/SocialFeedProvider( 1249): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4038 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1249): [trimMemory] 20
W/asset   ( 4038): Copying FileAsset 0x5c8a5428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4038): Binding Chromium to main looper Looper (main, tid 1) {41bcb608}
I/LibraryLoader( 4038): Expected native library version number "",actual native library version number ""
I/chromium( 4038): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4038): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(4239f2e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): acquireWL(42319be0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42240568:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4038): 1102975040: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  907): releaseWL(4239f2e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4038): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4038): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4038): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4038): Local Branch: 
I/Adreno-EGL( 4038): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4038): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4038):                  aa63bbd948f41d15fc72f585e
W/chromium( 4038): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/SensorManager(  907): mEventCount = 1350
W/dalvikvm( 4038): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4038): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4038): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4038): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4038): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4038): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4038): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4038): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4038): CordovaWebView is running on device made by: HTC
,W/AwContents( 4038): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1249
,W/ResourceType( 4038): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4038): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41c125c8, mServedView=org.apache.cordova.engine.SystemWebView{41bd8358 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  907): Enable input method client, pid=4038
W/XT9_C   ( 1189): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1189): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1189): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1189): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4038): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +290ms
,D/PMS     (  907): releaseWL(41edc478): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4038): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4038): JniHelper::setJavaVM(0x416a2010), pthread_self() = 1662675544
,D/JX-Cordova( 4038): jxcore cordova android initializing
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 11.568MB for 63974-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 11.600MB for 95956-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 11.671MB for 143930-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 11.787MB for 215890-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 11.961MB for 323830-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 12.637MB for 728606-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 13.234MB for 1092904-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 14.100MB for 1639352-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 15.460MB for 2459024-byte allocation
,I/dalvikvm-heap( 4038): Grow heap (frag case) to 17.485MB for 3688532-byte allocation
,W/jxcore-log( 4038): Initializing JXcore engine
,W/jxcore-log( 4038): JXcore engine is ready
W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(42215158): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  907): releaseHCC(421a3028): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4038): Starting JXcore engine
,W/jxcore-log( 4038): Platform android
W/jxcore-log( 4038): 
,W/jxcore-log( 4038): Process ARCH arm
W/jxcore-log( 4038): 
,I/jxcore-log( 4038): JXcore Cordova bridge is ready!
I/jxcore-log( 4038): 
,W/jxcore-log( 4038): JXcore engine is started
,I/Choreographer( 4038): Skipped 136 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4038): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4038): Toggling radios to true
I/jxcore-log( 4038): 
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): checking for enable restriction...
,D/BluetoothManagerService(  907): checkBTEasState, ret=true
I/BluetoothManagerService(  907): isBluetoothRestricted(): false
,D/BluetoothManagerService(  907): enable(): region ID = 6
D/BluetoothManagerService(  907): enable():  mBluetooth =null mBinding = false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 1
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
,W/Settings:Agent(  907): Process.myTid(): 917
W/Settings:Agent(  907): Process.myUid(): 1000
,W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  907): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  907): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 4038): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 918
,W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4038, uid=10348
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,I/ActivityManager(  907): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4084 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
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
W/Settings:Agent(  907): << traceCallingStack(): 7(ms)
,D/WifiManager( 4038): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 4038): reconnect: Base Package Name=com.test.thalitest, uid=10348
,I/jxcore-log( 4038): Radios toggled
I/jxcore-log( 4038): 
,I/jxcore-log( 4038): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4038): 
D/PMS     (  907): acquireWL(42635400): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42319be0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/AdapterServiceConfig( 4084): Adding HeadsetService
D/AdapterServiceConfig( 4084): Adding A2dpService
D/AdapterServiceConfig( 4084): Adding HidService
D/AdapterServiceConfig( 4084): Adding HealthService
D/AdapterServiceConfig( 4084): Adding PanService
D/AdapterServiceConfig( 4084): Adding GattService
,W/linker  ( 4084): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 4084): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4237cc40:true
,D/BluetoothAdapterState( 4084): make
,I/BluetoothAdapterState( 4084): Entering OffState
,I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 4084): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  907): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  907): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapter( 1431): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e44048
,D/BluetoothAdapter( 1431): onBluetoothServiceUp done
,D/BluetoothAdapter( 1112): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bbe008
,D/BluetoothAdapter( 1112): onBluetoothServiceUp done
,D/BluetoothAdapter( 4038): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42730b18
,D/BluetoothAdapter( 4038): onBluetoothServiceUp done
D/BluetoothAdapter( 4084): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41bd8d68
,D/BluetoothAdapter( 4084): onBluetoothServiceUp done
,D/BluetoothAdapter( 1224): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e75098
,D/BluetoothAdapter( 1224): onBluetoothServiceUp done
,D/BluetoothAdapter(  907): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@430f69d8
,D/BluetoothAdapter(  907): onBluetoothServiceUp done
D/BluetoothAdapter( 1235): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41cff160
,D/BluetoothAdapter( 1235): onBluetoothServiceUp done
D/BluetoothAdapter( 1758): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42231288
,D/BluetoothAdapter( 1758): onBluetoothServiceUp done
,D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 4084): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 4084): Setting state to 11
I/BluetoothAdapterState( 4084): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 4084): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=10 new=11
,D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  907): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 4084): make
,I/IntentController( 1112): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 4084): StableState(): Entering Off State
,D/HeadsetService( 4084): Received start request. Starting profile...
D/HeadsetStateMachine( 4084): Version 1.6
,D/HeadsetStateMachine( 4084): make
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4110 uid=10037 gids={50037, 3002, 3001}
,I/BluetoothAdapterState( 4084): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 4084): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 4084): Received start request. Starting profile...
,V/Avrcp   ( 4084): make
,D/Avrcp   ( 4084): fillIntentFilter()
,D/A2dpStateMachine( 4084): make
,I/QuickSettingBluetooth( 1112): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/HtcBtWidget_BTWidgetProvider( 4110): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 4110): updateWidget(context) for widget: 
,D/A2dpStateMachine( 4084): Enter Disconnected: -2
,D/HidService( 4084): Received start request. Starting profile...
,D/Process (  907): killProcessQuiet, pid=2994
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 2994:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/HealthService( 4084): Received start request. Starting profile...
,D/PanService( 4084): Received start request. Starting profile...
D/BluetoothTethering(  907): supplyMessenger
D/BluetoothTethering(  907): supplyMessenger mAsyncChannel is null
,D/BluetoothTethering(  907): got MESSAGE_CONNECT_PANSERVICE, call connect
D/PanService( 4084): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  907): got CMD_CHANNEL_HALF_CONNECTED
I/ActivityManager(  907): Recipient 2994
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BtGatt.DebugUtils( 4084): handleDebugAction() action=null
D/BtGatt.GattService( 4084): Received start request. Starting profile...
D/BtGatt.GattService( 4084): start()
V/BluetoothPbapService( 4084): Pbap Service onCreate
V/BluetoothPbapService( 4084): Starting PBAP service
D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 11
D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 11
E/BluetoothMasService( 4084): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 4084): Add permission for SmsProvider.
V/BluetoothMasService( 4084): Starting MAS instances
D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 11
I/MailMessageReceiver( 4084): reg:com.android.bluetooth.btservice.AdapterApp@41bcc2d0 with com.htc.util.mail.MailMessageReceiver@41c0c110
I/MailManager( 4084): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41c0c110
V/EmailUtils( 4084): Manager Instance is not NULL
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=4128 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  907): interfaceAdded wlan0
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): wlan0 is not a tetherable iface, ignoring
,D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): interfaceAdded p2p0
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): p2p0 is not a tetherable iface, ignoring
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/PMS     (  907): releaseWL(42635400): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  907): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 4084): ============NULL aList========
,V/EmailUtils( 4084): <-getEmailAccountIdList
,V/BluetoothMasService( 4084): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 11
V/BluetoothMasService( 4084): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 4084): Manager Instance is not NULL
D/EmailUtils( 4084): ============NULL aList========
,V/EmailUtils( 4084): <-getEmailAccountIdList
V/BluetoothSapService( 4084): Sap Service onCreate
V/BluetoothSapService( 4084): initBinder
V/BluetoothSapService( 4084): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41c11500
,V/BluetoothSapReceiver( 4084): BluetoothSapReceiver init
,D/BluetoothSapService( 4084): setSapService()
V/BluetoothSapService( 4084): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 4084): state: 12
,D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 11
,D/BluetoothAdapterService( 4084): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4084): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 4084): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/HeadsetPhoneState( 4084): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 4084): Profile still not running:com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 4084): Profile still not running:com.android.bluetooth.gatt.GattService
,D/PanService( 4084): CMD_CHANNEL_FULL_CONNECTION
I/wpa_supplicant( 4144): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4144): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4144): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4144): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4144): Get randomness: len=20 entropy=1
,D/BluetoothAdapterState( 4084): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/BluetoothTethering(  907): got CMD_CHANNEL_FULLY_CONNECTED
D/wpa_supplicant( 4144): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4144): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4144): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4144): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4144): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4144): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4144): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4144): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4144): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4144): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4144): update_config=1
D/wpa_supplicant( 4144): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4144): device_name='Android_63cc'
D/wpa_supplicant( 4144): manufacturer='HTC'
D/wpa_supplicant( 4144): model_name='HTC_PHONE'
D/wpa_supplicant( 4144): model_number='1234'
D/wpa_supplicant( 4144): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4144): p2p_oper_reg_class=126
D/wpa_supplicant( 4144): p2p_oper_channel=36
D/wpa_supplicant( 4144): p2p_ssid_postfix='-Android_63cc'
,D/wpa_supplicant( 4144): persistent_reconnect=1
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4144): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4144): nl80211: RFKILL status not available
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4144): nl80211: Using driver-based roaming
D/wpa_supplicant( 4144): nl80211: TDLS supported
D/wpa_supplicant( 4144): nl80211: TDLS external setup
D/wpa_supplicant( 4144): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4144): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4144): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4144): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4144): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4144): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4144): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4144): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b9e758
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7b9e758
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4144): htc_wext_command_init +
E/wpa_supplicant( 4144): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4144): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4144): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4144): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4144): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4144): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4144): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4144): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4144): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  907): interfaceLinkStateChanged p2p0, false
D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Process (  907): killProcessQuiet, pid=3496
D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
,I/ActivityManager(  907): Killing 3496:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/BluetoothMasReceiver( 4084): Bluetooth STATE CHANGED to 11
I/qcom-bluetooth( 4148): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  907): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4153 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4165): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4167): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 4169): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4170): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4171): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4172): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4153): Received state change = 11
,I/ActivityManager(  907): Recipient 3496
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiMonitor(  907): startMonitoring(wlan0) with mConnected = false
,I/IntentController( 1112): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/MediaRouterService(  907): Client com.google.android.music (pid 3496): Died!
D/WIFI_ICON( 1112): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/ActivityManager(  907): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4175 uid=10048 gids={50048}
D/WifiService(  907): New client listening to asynchronous messages
,D/Process (  907): killProcessQuiet, pid=3875
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3875:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/HtcWiFiWidget_WiFiWidgetProvider( 4175): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4175): updateWidget(context) for widget: 
,D/Process (  907): killProcessQuiet, pid=3478
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/QuickSettingWifi( 1112): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
I/ActivityManager(  907): Killing 3478:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/wpa_supplicant( 4144): wapi_supplicant_init: Init WAI packet p2p0
,D/wpa_supplicant( 4144):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4144):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4144):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4144): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4144): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4144): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4144): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4144): nl80211: Flush PMKIDs
E/wpa_supplicant( 4144): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4144): State: DISCONNECTED -> INACTIVE
,I/ActivityManager(  907): Recipient 3478
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3875
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/wpa_supplicant( 4144): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4144): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4144): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4144): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4144): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4144): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): Using existing control interface directory.
D/wpa_supplicant( 4144): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4144): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4144): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4144): P2P: Own listen channel: 6
D/wpa_supplicant( 4144): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4144): P2P: Add operating class 81
I/wpa_supplicant( 4144): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4144): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4144): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4144): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4144): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf',
D/wpa_supplicant( 4144): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4144): disable_scan_offload=1
D/wpa_supplicant( 4144): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4144): update_config=1
D/wpa_supplicant( 4144): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4144): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4144): manufacturer='HTC',
D/wpa_supplicant( 4144): model_name='HTC Desire 820'
D/wpa_supplicant( 4144): model_number='HTC Desire 820'
D/wpa_supplicant( 4144): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4144): persistent_reconnect=1
D/wpa_supplicant( 4144): p2p_disabled=1
D/wpa_supplicant( 4144): hs20=1
D/wpa_supplicant( 4144): interworking=1
D/wpa_supplicant( 4144): Line: 18 - start of a new network block
D/wpa_supplicant( 4144): key_mgmt: 0x2,
D/wpa_supplicant( 4144): priority=1 (0x1)
,D/wpa_supplicant( 4144): signinfail=0 (0x0),
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4188 uid=10077 gids={50077}
D/PMS     (  907): acquireWL(4268e2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
,V/AlarmManager(  907): sending alarm PendingIntent{42359820: PendingIntentRecord{423597e8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452596495794, Int=60000
,D/PMS     (  907): releaseWL(4268e2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
I/qcom-bluetooth( 4194): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
I/qcom-bluetooth( 4199): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 4084): btu_task pending for preload complete event
,D/SMSBackup( 4188): SMSBackupAgentService started
,D/SMSBackup( 4188): Checking restore status
,D/SMSBackup( 4188): Restore complete
,D/SMSBackup( 4188): cancelCheckAlarm
D/wpa_supplicant( 4144): Priority group 1
D/wpa_supplicant( 4144):    id=0 ssid='NG700'
I/wpa_supplicant( 4144): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4144): nl80211: RFKILL status not available
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4144): nl80211: Using driver-based roaming
D/wpa_supplicant( 4144): nl80211: TDLS supported
D/wpa_supplicant( 4144): nl80211: TDLS external setup
D/wpa_supplicant( 4144): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4144): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4144): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4144): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4144): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4144): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4144): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4144): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7bae718
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4144): htc_wext_command_init +
I/wpa_supplicant( 4144): htc_wext_command_init -
I/wpa_supplicant( 4144): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4144): Don't set 00 to countryID.conf
D/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4144): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4144): nl80211: Use separate P2P group interface
,E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 95,
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4144): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4144): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4144): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4144): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4144): nl80211: 5170-5250 @ 80 MHz,
D/wpa_supplicant( 4144): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4144): nl80211: Added 802.11b mode based on 802.11g information
D/SMSBackup( 4188): SMSBackupAgentService completed: completed in 0.0 seconds
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Process (  907): killProcessQuiet, pid=3902
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Killing 3902:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3902
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 4144): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4144):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4144):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4144):  Initialization: WAPI:set Staues=1 
,D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4144): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4144): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4144): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4144): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4144): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4144): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4144): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4144): TDLS: Driver uses external link setup
D/wpa_supplicant( 4144): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4144): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4144): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4144): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4144): Using existing control interface directory.
I/wpa_supplicant( 4144): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4144): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4144): Auto country group 1: ch36
I/wpa_supplicant( 4144): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4144): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4144): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4144): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4144): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4144): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4144): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,I/wpa_supplicant( 4144): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_907-2
D/wpa_supplicant( 4144): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4144): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4144): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4144): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4144): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4144): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4144): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4144): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4144): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4144): nl80211: Event message available
D/wpa_supplicant( 4144): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4144): nl80211: Regulatory domain change
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4144): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4144): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4144): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4144): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4144): P2P: Add operating class 81
D/wpa_supplicant( 4144): P2P: Add operating class 115
D/wpa_supplicant( 4144): P2P: Add operating class 116
D/wpa_supplicant( 4144): P2P: Add operating class 117
D/wpa_supplicant( 4144): P2P: Update channel list
D/wpa_supplicant( 4144): p2p0: Updating hw mode
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4144): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4144): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4144): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4144): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4144): nl80211: Added 802.11b mode based on 802.11g information
,D/WifiNative-wlan0(  907): doBoolean: SET_WIFI_ON 1
V/RegulatoryObserver(  907): uevent:
V/RegulatoryObserver(  907): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  907): Regulatory Country Code:DE
V/RegulatoryObserver(  907): Start wifi-crda service to run crda.
V/RegulatoryObserver(  907): Country Code is DE
V/RegulatoryObserver(  907): Send broadcast country code message.
I/RegulatoryObserver(  907): Broadcast intent for crda country code: DE
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): set wifi ON
D/WifiNative-wlan0(  907):    returned true
,I/IntentController( 1112): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,D/WifiNative-wlan0(  907): doString: DRIVER MACADDR
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  907): Loading config and enabling all networks
D/WifiNative-wlan0(  907): doString: LIST_NETWORKS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): list_network_info: ret=0x1, pos=0xb7bb1117 buf=0xb7bb10e8
,I/wpa_supplicant( 4144): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4144): 0	NG700	any	
D/WIFI_ICON( 1112): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HtcWiFiWidget_WiFiWidgetProvider( 4175): onWiFiStateChanged() for widget: 
I/wpa_supplicant( 4144): wpa_supplicant_scan enter
D/WifiNative-wlan0(  907):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  907): 0	NG700	any	
I/wpa_supplicant( 4144): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4144): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4144): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4144): Scan req (ret=0) - timeout 10 secs
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 ssid
D/wpa_supplicant( 4144): nl80211: Event message available
D/wpa_supplicant( 4144): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HtcWiFiWidget_WiFiWidgetProvider( 4175): updateWidget(context) for widget: 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 bssid
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 priority
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2",
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4144): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 proto
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  907): Failed to look-up a string: W
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  907): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 group
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  907): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 limited
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 eap
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 phase2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 identity
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 password
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 engine
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 key_id
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 private_key
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4144): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  907): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  907): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4144): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4144): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET manufacturer HTC
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4144): manufacturer='HTC'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4144): model_name='HTC Desire 820'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4144): model_number='HTC Desire 820'
D/WifiNative-wlan0(  907):    returned true
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4144): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET auto_interworking 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4144): auto_interworking=0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: STATUS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): SET_SCREEN_ON:On
I/wpa_supplicant( 4144): htc_wext_set_keepalive +
I/wpa_supplicant( 4144): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4144): getPrivFuncNum +	
I/wpa_supplicant( 4144): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4144): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4144): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4144): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4144): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET ps 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4144): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiP2pService(  907): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  907): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  907): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): SETBAND: 0
D/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4144): P2P: Add operating class 81
D/wpa_supplicant( 4144): P2P: Add operating class 115
D/wpa_supplicant( 4144): P2P: Add operating class 116
D/wpa_supplicant( 4144): P2P: Add operating class 117
D/wpa_supplicant( 4144): P2P: Update channel list
I/wpa_supplicant( 4144): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4144): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4144): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4144): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4144): p2p_oper_reg_class=126
D/wpa_supplicant( 4144): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4144): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 4144): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4144): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4144): p2p_oper_channel=36
E/wpa_supplicant( 4144): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4144): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4144): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4144): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4144): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: BSS_FLUSH 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  907):    returned false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4144): wpa_supplicant_scan enter
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Wifi band: 0, ScanBroadCastCounter: 0
D/libc    (  907): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiMonitor(  907): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  907): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4144): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4144): persistent_reconnect=1
I/wpa_supplicant( 4144): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET device_name Android_63cc
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 4144): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 4144): device_name='Android_63cc'
I/wpa_supplicant( 4144): Recv Cmd 2: SET device_name=Android_63cc
I/QuickSettingWifi( 1112): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 4144): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 4144): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4144): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 4144): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4144): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4144): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4144): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4144): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4144): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4144): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4144): Single channel concurrency preference: sta
I/wpa_supplicant( 4144): Recv Cmd 2: P2P_SET conc_pref
D/WifiP2pService(  907): P2pEnablingState
D/WifiP2pService(  907): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2p socket connection successful
D/WifiP2pService(  907): P2pEnabledState
D/WifiP2pService(  907): sending p2p connection changed broadcast
D/WifiDisplayController(  907): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  907): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  907): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  907): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doString: STATUS
W/WifiHW  (  907): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  907): doBoolean: P2P_FLUSH
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4144): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4144): P2P: Stopping find
D/wpa_supplicant( 4144): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4144): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4144): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4144): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4144): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doString: LIST_NETWORKS
W/WifiHW  (  907): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4144): list_network_info: ret=0x22, pos=0xb7bb110a buf=0xb7bb10e8
I/wpa_supplicant( 4144): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4144): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  907):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  907): doBoolean: AP_SCAN 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  907):    returned false
D/WifiNative-p2p0(  907): doBoolean: SET wifi_display 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4144): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4144): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4144): WFD: Update WFD IE
I/wpa_supplicant( 4144): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4144): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  907): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4144): WFD: Set subelement 0
D/wpa_supplicant( 4144): WFD: Update WFD IE
I/wpa_supplicant( 4144): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4144): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  907):    returned true
V/AudioService(  907): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  907):     Client/Owner: Client
V/AudioService(  907):     GroupId: 
V/AudioService(  907):     Passphrase: 
V/AudioService(  907):     SessionId: 0
V/AudioService(  907):     IP Address: }
D/HtcEffectManagerBase(  907): onEventChanged id=5 status=false
D/HtcEffectManager(  907): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/WifiP2pService(  907): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  907): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
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
D/WifiP2pService(  907): P2pEnabledState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  907):  WFD CtrlPort: 7236
D/WifiP2pService(  907):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  907): Successfully set WFD info.
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  907): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
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
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/HtcEffectManager(  907): convertEffect before=902
D/HtcEffectManager(  907): convertEffect after=902
,D/wpa_supplicant( 4144): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4144): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4144): nl80211: if_removed already cleared - ignore event
D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4144): nl80211: Event message available
D/wpa_supplicant( 4144): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4144): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4144): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 4144): nl80211: Survey data missing
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4144): Sorted scan results
I/wpa_supplicant( 4144): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 4144): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 4144): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 4144): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 4144): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-82
I/wpa_supplicant( 4144): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 4144): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 4144): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4144): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4144): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4144): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4144): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4144): Add randomness: count=7 entropy=5
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4144): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4144): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4144): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4144): wpa_supplicant_pick_network+
I/wpa_supplicant( 4144): Selecting BSS from priority group 1
I/wpa_supplicant( 4144): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4144): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4144): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4144): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4144): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4144):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4144):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 4144): Start print parameters
I/wpa_supplicant( 4144): wpa_s->wpa_state is 3
I/wpa_supplicant( 4144): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4144): isConcurrentMode() is 0
I/wpa_supplicant( 4144): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4144): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4144): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4144): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4144): wpa_s->reassociate is 0
I/wpa_supplicant( 4144): wpa_s->is_screen_on 1
I/wpa_supplicant( 4144): wpa_s->ifname wlan0
I/wpa_supplicant( 4144): End print parameters
I/wpa_supplicant( 4144): selected network = 2
D/wpa_supplicant( 4144): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid,: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7baf4e8  current_ssid=0x0
D/wpa_supplicant( 4144): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4144): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4144): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4144): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4144): check if in concurrent case
,I/wpa_supplicant( 4144): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 4144): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4144): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4144): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4144): RSN: PMKSA cache search - network_ctx=0xb7baf4e8 try_opportunistic=0
D/wpa_supplicant( 4144): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4144): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4144): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 4144): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4144): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4144): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4144): nl80211: Unsubscribe mgmt frames handle 0xb7bae718 (mode change)
D/wpa_supplicant( 4144): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7bae718,
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718,
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Register frame type=0xd0 nl_handle=0xb7bae718,
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4144): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4144):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4144):   * freq=2412
D/wpa_supplicant( 4144):   * Auth Type 0
D/wpa_supplicant( 4144):   * WPA Versions 0x2
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 46,
D/wpa_supplicant( 4144): nl80211: Connect request send successfully
D/wpa_supplicant( 4144): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4144): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4144): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 4144): reply (779) for get BSS: id=0
I/wpa_supplicant( 4144): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4144): freq=5220
I/wpa_supplicant( 4144): level=-47
I/wpa_supplicant( 4144): tsf=0000000104321152
I/wpa_supplicant( 4144): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4144): ssid=NG7005g,
I/wpa_supplicant( 4144): ====
I/wpa_supplicant( 4144): id=1
I/wpa_supplicant( 4144): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4144): freq=2412
I/wpa_supplicant( 4144): level=-53
I/wpa_supplicant( 4144): tsf=0000000104321163
I/wpa_supplicant( 4144): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4144): ssid=01ABC
I/wpa_supplicant( 4144): ====
I/wpa_supplicant( 4144): id=2
I/wpa_supplicant( 4144): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4144): freq=2412
I/wpa_supplicant( 4144): level=-53
I/wpa_supplicant( 4144): tsf=0000000104321166
I/wpa_supplicant( 4144): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4144): ssid=NG700
I/wpa_supplicant( 4144): ====
I/wpa_supplicant( 4144): id=3
I/wpa_supplicant( 4144): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4144): freq=2452
I/wpa_supplicant( 4144): level=-77
I/wpa_supplicant( 4144): tsf=0000000104321170
I/wpa_supplicant( 4144): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4144): ssid=Gonzos
I/wpa_supplicant( 4144): ====
I/wpa_supplicant( 4144): id=4
I/wpa_supplicant( 4144): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 4144): freq=2437
I/wpa_supplicant( 4144): level=-82,
I/wpa_supplicant( 4144): tsf=0000000104321174
I/wpa_supplicant( 4144): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 4144): ssid=UPC Wi-Free
I/wpa_supplicant( 4144): ====
I/wpa_supplicant( 4144): id=5
I/wpa_supplicant( 4144): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 4144): freq=2437
I/wpa_supplicant( 4144): level=-85
I/wpa_supplicant( 4144): tsf=0000000104321177
I/wpa_supplicant( 4144): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4144): ssid=UPC5999698
I/wpa_supplicant( 4144): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 104321152, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 104321163, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 104321166, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 104321170, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -82, frequency: 2437, timestamp: 104321174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 104321177, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 4144): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4144): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4144): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4144): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4144): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4144): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4144): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4144): nl80211: Event message available
D/wpa_supplicant( 4144): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4144): nl80211: Connect event
D/wpa_supplicant( 4144): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4144): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4144): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4144): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4144): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4144): Add randomness: count=8 entropy=6
I/wpa_supplicant( 4144): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4144): TDLS: Remove peers on association
D/wpa_supplicant( 4144): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4144): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4144): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4144): htc_wext_set_keepalive +
I/wpa_supplicant( 4144): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4144): getPrivFuncNum +	
I/wpa_supplicant( 4144): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4144): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4144): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4144): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4144): Get randomness: len=32 entropy=7
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=24,12
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Associated
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/wpa_supplicant( 4144): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7bae9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4144):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4144): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4144): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f62b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4144):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4144): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4144): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4144): State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 4144): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4144): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 4144): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4144): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4144): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4144): set send_ind_to_ndc = 0
I/wpa_supplicant( 4144): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4144): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4144): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4144): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4144): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4144): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4144): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4144): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4144): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4144): EAPOL authentication completed successfully
I/wpa_supplicant( 4144): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4144): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4144): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4144): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1758/10178)
,D/WISPrService( 3822): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WISPrService( 3822): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  907): New client listening to asynchronous messages
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4144): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  907): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): Power_Mode_Type mode = 1
I/wpa_supplicant( 4144): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/PMS     (  907): acquireWL(42b6dfa0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43061488 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43061488 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 4144): EAPOL: disable timer tick
D/wpa_supplicant( 4144): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4144): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 18
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
,I/bt-btu  ( 4084): btu_task received preload complete event
,D/bt-btm  ( 4084): btm_acl_device_down
D/bt-btm  ( 4084): btm_acl_reset_paging
,D/bt-btm  ( 4084): btm_acl_set_discing
,I/bt-btm  ( 4084): btm_reset_complete
,I/bt-btm  ( 4084): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 4084): Start reading local supported commands
,D/bt-btm  ( 4084): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 4084): BTM reads next extended features page (1)
,D/bt-btm  ( 4084): BTM reads next extended features page (2)
D/bt-btm  ( 4084): BTM reached last extended features page (2)
,D/bt-btm  ( 4084): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 4084): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 4084): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 4084): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 4084): btm_read_ble_wl_size 
,D/bt-btm  ( 4084): btm_read_white_list_size_complete 
,D/bt-btm  ( 4084): btm_get_ble_buffer_size 
D/bt-btm  ( 4084): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 4084): btm_read_ble_local_supported_features 
D/bt-btm  ( 4084): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 4084): btm_reset_ctrlr_complete: max_page_number: 2
,D/bt-btm  ( 4084): btm_decode_ext_features_page page: 0
D/bt-btm  ( 4084): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 4084): Local supported SCO packet types: 0x038f
D/bt-btm  ( 4084): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 4084): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 4084):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 4084): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 4084): BTM_SetInquiryMode
I/bt-btm  ( 4084): BTM_SetPageScanType
I/bt-btm  ( 4084): BTM_SetInquiryScanType
D/bt-btm  ( 4084): btm_decode_ext_features_page page: 1
D/bt-btm  ( 4084): btm_decode_ext_features_page page: 2
D/bt-btm  ( 4084): BTM_BleLoadLocalKeys
D/bt-btm  ( 4084): BTM_BleLoadLocalKeys
I/bt-btm  ( 4084): BTM_Sec: application registered
E/bt-btm  ( 4084): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fdb941 
I/bt-btm  ( 4084): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 4084): SMP_Register state=0
E/bt-btm  ( 4084): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fdb941 
I/bt-btm  ( 4084): BTM_Sec: application registered
D/bt-btm  ( 4084): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 4084): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 4084): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 4084): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 4084): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 4084): BTM_RegBusyLevelNotif
I/bt-att  ( 4084): GATT_Register
D/bt-att  ( 4084): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 4084): allocated gatt_if=3
I/bt-att  ( 4084): GATT_StartIf gatt_if=3
D/bt-att  ( 4084): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 4084): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
E/bt-btif ( 4084): Calling BTA_HhEnable
,I/bt-btm  ( 4084): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 4084): BTM_AllocateSCN
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 4084): BTM_AllocateSCN
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btm  ( 4084): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 4084):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 4084):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 4084):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 4084):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 4084):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 4084):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 4084):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 4084):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 4084): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 4084): A2D_AddRecord uuid: 110a
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
D/bt-avp  ( 4084): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 4084): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btm  ( 4084): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 4084):                : sec: 0x80, service name [] (up, to 21 chars saved)
D/bt-btm  ( 4084): BTM_GetHCIConnHandle
I/bt-btm  ( 4084): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 4084): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4084): BTM_GetHCIConnHandle
I/bt-btm  ( 4084): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 4084): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4084): BTM_GetHCIConnHandle
I/bt-btm  ( 4084): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 4084): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4084): BTM_GetHCIConnHandle
I/bt-btm  ( 4084): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 4084): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 4084): GATT_Register
D/bt-att  ( 4084): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 4084): allocated gatt_if=4
I/bt-att  ( 4084): GATT_StartIf gatt_if=4
D/bt-att  ( 4084): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 4084): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btm  ( 4084): BTM_GetHCIConnHandle
I/bt-btm  ( 4084): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 4084): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4084): BTM_GetHCIConnHandle
I/bt-btm  ( 4084): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 4084): BTM_SecAddDevice : rmt_io_caps is 0 
E/bt-btif ( 4084): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 4084): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 4084): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:1 len:14
,I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 4084): Scan Mode:20
I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 4084): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:8 len:36
D/BluetoothAdapter( 4084): getBluetoothService(): entry
,D/BluetoothAdapter( 4084): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 4084): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41c1c7f8
,D/BluetoothDevice( 4084): getService : Register callback
,D/BluetoothAdapterProperties( 4084): Adding bonded device:B4:CE:F6:AB:A4:6A
,D/BluetoothAdapterProperties( 4084): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 4084): Adding bonded device:34:FC:EF:9D:93:0B
,D/BluetoothAdapterProperties( 4084): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 4084): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 4084): Adding bonded device:58:2A:F7:ED:96:BE
,I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 4084): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4084): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 4084): Remote class is:5898764
,I/bt-btif ( 4084): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4084): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 4084): Remote class is:5898764
,I/bt-btif ( 4084): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4084): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BluetoothRemoteDevices( 4084): Remote class is:5898764
,I/bt-btif ( 4084): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4084): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BluetoothRemoteDevices( 4084): Remote class is:5898764
,I/bt-btif ( 4084): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4084): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 4084): Remote class is:5898764
,I/bt-btif ( 4084): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4084): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothRemoteDevices( 4084): Remote class is:5898764
I/bt-btif ( 4084): BTA_JvEnable
I/bt-btm  ( 4084): BTM_ReadConnectability
I/bt-btm  ( 4084): BTM_ReadDiscoverability
I/bt-btm  ( 4084): BTM_SetDiscoverability
I/bt-btm  ( 4084): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 4084): br_edr_supported=0x2
I/bt-btm  ( 4084): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4084): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4084): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 4084): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4084): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4084): BTM_SetConnectability
I/bt-btm  ( 4084): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 4084): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4084): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 4084): BTM_SetDiscoverability
I/bt-btm  ( 4084): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4084): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4084): br_edr_supported=0x0
I/bt-btm  ( 4084): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4084): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4084): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4084): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 4084): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4084): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 4084): BTM_SetConnectability
I/bt-btm  ( 4084): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 4084): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4084): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 4084): bta_pan_co_init
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 4084): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 4084):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 4084):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 4084): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 4084):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 4084): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 4084):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
,I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
,E/bt_mct  ( 4084): hci lib postload completed
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:10
,I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btif ( 4084): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 4084): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4084): ScanMode =  20
D/BluetoothAdapterProperties( 4084): State =  11
I/bt-btm  ( 4084): BTM_SetDiscoverability
I/bt-btm  ( 4084): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4084): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4084): br_edr_supported=0x0
I/bt-btm  ( 4084): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4084): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4084): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4084): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 4084): evt_type=0x3 p-cb->evt_type=0x3 
D/BluetoothAdapterProperties( 4084): Setting state to 12
I/bt-btm  ( 4084): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4084): BTM_SetConnectability
I/bt-btm  ( 4084): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 4084): new flag=0x0 cur flag=0x4
D/bt-btm  ( 4084): btm_ble_update_adv_flag new=0x0
I/BluetoothAdapterState( 4084): Bluetooth adapter state changed: 11-> 12
D/bt-btm  ( 4084): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 4084): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4084): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterService( 4084): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btif ( 4084): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothManagerService(  907): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothAdapterProperties( 4084): Scan Mode:21
I/bt-btif ( 4084): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4084): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothManagerService(  907): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothAdapterProperties( 4084): Discoverable Timeout:120
I/BluetoothAdapterState( 4084): Entering On State
,D/BluetoothHeadset( 1224): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1102930424)( 4084): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 4084): getBondedDevices: length=6
D/BluetoothHeadset( 1224): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1224): Proxy object connected
,D/BluetoothPan(  907): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1224): Proxy object connected
,D/BluetoothPhoneService( 1224): BluetoothHeadset onServiceConnected
,D/BluetoothHeadset( 1112): onBluetoothStateChange: up=true
,D/BluetoothPan(  907): BluetoothPAN Proxy object connected
,D/BluetoothAdapter( 1224): 1104264888: getState(). Returning 12
,D/BluetoothHeadset(  907): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  907): onBluetoothStateChange: up=true
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset( 1112): Proxy object connected
I/QuickSettingMiniLite( 1112): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41ed4ce8
D/BluetoothHeadset(  907): Proxy object connected
D/BluetoothManagerService(  907): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapter(  907): 1112471896: getState(). Returning 12
I/IntentController( 1112): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 4084): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(1102930424)( 4084): Get Bonded Devices being called
D/BluetoothAdapterProperties( 4084): getBondedDevices: length=6
V/BluetoothPbapReceiver( 4084): ***********state = 12
,D/BluetoothA2dp(  907): Proxy object connected
,D/BluetoothAdapter(  907): 1112471896: getState(). Returning 12
D/PMS     (  907): acquireWL(42acde90): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3822 1000 null
,D/BluetoothMasReceiver( 4084): Bluetooth STATE CHANGED to 12
,V/BluetoothSapReceiver( 4084): SapReceiver onReceive 
V/BluetoothSapReceiver( 4084): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 4084):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 4084): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManagerService(  907): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/HtcBtWidget_BTWidgetProvider( 4110): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4110): updateWidget(context) for widget: 
,D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 12
D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 12
V/BluetoothMasService( 4084): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 4084): Manager Instance is not NULL
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  907): releaseWL(42acde90): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  907): acquireWL(43dd61f0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3822 1000 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440c45f0:true
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/EmailUtils( 4084): ============NULL aList========
V/EmailUtils( 4084): <-getEmailAccountIdList
V/BluetoothSapService( 4084): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 4084): state: 12
I/LocationAgent( 3822): new LocationAgent instance!!
D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 12
W/ContextImpl( 4084): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/HtcTagManager( 3822): HtcTagManager construction complete
V/BluetoothSapService( 4084): Starting SAP server process
V/BluetoothPbapService( 4084): Handler(): got msg=1
V/BluetoothPbapService( 4084): Pbap Service startRfcommSocketListener
D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
V/BluetoothPbapService( 4084): Pbap Service initSocket
V/BluetoothMasService( 4084): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 4084): BluetoothMns: isEmailEnabled: true
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 4084): getBluetoothService(): entry
D/BluetoothInputDevice( 3822): BluetoothInputDevice()
W/BluetoothAdapter( 4084): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 7
D/BluetoothMasService( 4084): Map_prev 1
E/BluetoothServiceJni( 4084): SOCK FLAG = 1 ***********************
I/bt-btif ( 4084): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btif ( 4084): BTA_JvRfcommStartServer
I/bt-btm  ( 4084): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 4084):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 4084): Succeed to create listening socket 
V/BluetoothPbapService( 4084): Accepting socket connection...
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
D/BluetoothInputDevice( 3822): BluetoothInputDevice(): Binding service...
D/BluetoothAdapter( 4084): getBluetoothService(): entry
W/BluetoothAdapter( 4084): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 4084): SOCK FLAG = 3 ***********************
I/bt-btif ( 4084): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btif ( 4084): BTA_JvRfcommStartServer
I/bt-btm  ( 4084): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 4084):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothPan( 3822): BluetoothPan()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4084): getBluetoothService(): entry
,W/BluetoothAdapter( 4084): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
D/BluetoothPan( 3822): BluetoothPan(): Binding service...
,D/BluetoothManagerService(  907): Registered receivers: 8
E/BluetoothServiceJni( 4084): SOCK FLAG = 3 ***********************
,I/bt-btif ( 4084): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btif ( 4084): BTA_JvRfcommStartServer
I/bt-btm  ( 4084): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 4084):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothMap( 3822): Create BluetoothMap proxy object
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 9
,E/BluetoothMap( 3822): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothAdapter( 1112): 1105662088: getState(). Returning 12
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3822): BluetoothSap() call bindService
,D/BluetoothManagerService(  907): Registered receivers: 10
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,D/BluetoothAdapter( 1112): 1105662088: getState(). Returning 12
,I/QuickSettingBluetooth( 1112): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1112): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothPbap( 3822): BluetoothPbap()
D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 11
D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
,D/BluetoothPbap( 3822): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 3822): BluetoothA2dp()
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
,D/BluetoothA2dp( 3822): BluetoothA2dp(): Binding service...
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 12
,D/BluetoothHeadset( 3822): BluetoothHeadset()
,D/BluetoothSapService( 4084): Sap_prev 1
,D/BluetoothManagerService(  907): registerStateChangeCallback+
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
V/BluetoothSapService( 4084): SAP Service startRfcommListenerThread
D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
D/BluetoothHeadset( 3822): BluetoothHeadset(): Binding service...
,V/BluetoothSapService( 4084): Sap Service initRfcommSocket
D/HtcTagManager( 3822): startProxy
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): Registered receivers: 13
D/BluetoothAdapter( 4084): getBluetoothService(): entry
,W/BluetoothAdapter( 4084): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 4084): SOCK FLAG = 3 ***********************
,I/bt-btif ( 4084): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btif ( 4084): BTA_JvRfcommStartServer
I/bt-btm  ( 4084): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 4084):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 4084): Succeed to create listening socket 
,V/BluetoothSapService( 4084): Accepting socket connection...
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
W/ContextImpl( 3822): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
D/LocalBluetoothProfileManager( 3822): LocalBluetoothProfileManager construction complete
,V/TAG     ( 4084): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 4084): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41c12c40
,D/BluetoothAdapter( 1112): 1105662088: getState(). Returning 12
,D/DockEventReceiver( 3822): finishStartingService: stopping service
D/BluetoothPan( 3822): BluetoothPAN Proxy object connected
D/PanProfile( 3822): Bluetooth service connected
,D/BluetoothA2dp( 3822): Proxy object connected
,D/A2dpProfile( 3822): Bluetooth service connected
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4153): onCreate: going to find gatt base service first.
,I/QuickSettingMiniLite( 1112): updateLiteState:no connect device!
,D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
,D/BluetoothHeadset( 3822): Proxy object connected
,D/HeadsetProfile( 3822): Bluetooth service connected
,D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
,D/BluetoothInputDevice( 3822): Proxy object connected
,D/HidProfile( 3822): Bluetooth service connected
,V/BluetoothPbapService( 4084): Pbap Service onBind
,D/BluetoothAdapter( 3822): 1104136832: getState(). Returning 12
D/wpa_supplicant( 4144): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4144): EAPOL: disable timer tick
,W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4413e498:true
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/SapServerProfile( 3822): Bluetooth service connected
D/BluetoothPbap( 3822): Proxy object connected
,D/PbapServerProfile( 3822): Bluetooth service connected
,D/PMS     (  907): releaseWL(43dd61f0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/[HTC_BLE][Constants]( 4153):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4153):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 4153):  + discoverServicesOnBonded = false
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/BluetoothFtpService( 4084): Ftp Service onCreate
,D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 12
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4153):  + Google LE service found. Using BaseLeProfilesGoogle.
D/BluetoothMasReceiver( 4084): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 4084): getBluetoothService(): entry
W/BluetoothAdapter( 4084): getBluetoothService() called with no BluetoothManagerCallback
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4153): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41bdc220
D/[HTC_BLE][Constants]( 4153): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4153): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4153): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4153): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4153): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4153): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,E/BluetoothServiceJni( 4084): SOCK FLAG = 0 ***********************
,D/BluetoothFtpService( 4084): Ftp_prev 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4153): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/bt-btif ( 4084): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:15
,I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
D/BluetoothAdapter( 4084): getBluetoothService(): entry
W/BluetoothAdapter( 4084): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 4084): BTA_JvRfcommStartServer
I/bt-btm  ( 4084): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 4084):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
E/BluetoothServiceJni( 4084): SOCK FLAG = 1 ***********************
I/bt-btif ( 4084): BTA_JvCreateRecordByUser
D/HtcTagManager( 3822): onServiceConnected
D/bt-sdp  ( 4084): SDP_CreateRecord ok, num_records:16
,I/BtOppRfcommListener( 4084): Accept thread started.
I/bt-btm  ( 4084): Write Extended Inquiry Response to controller
I/bt-btif ( 4084): BTA_JvRfcommStartServer
I/bt-btm  ( 4084): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 4084):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 4084): Run Accept thread
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4153): Received state change = 12
,D/BluetoothAdapter( 4084): 1102948600: getState(). Returning 12
V/BluetoothMasService( 4084): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 4084): Manager Instance is not NULL
D/HtcTagProfile( 3822): setup proxy
D/HtcPxpProfile( 3822): setup proxy
,D/HtcFmpProfile( 3822): setup proxy
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4153): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4153): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41bdc220
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4153): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41bdc220
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4153): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41bdc220, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41be7208
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4153): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41bdc220
,D/EmailUtils( 4084): ============NULL aList========
,V/EmailUtils( 4084): <-getEmailAccountIdList
,D/BluetoothMasService( 4084): Map_prev 1
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43066c98:true
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4003): new LocationAgent instance!!
,D/HtcTagManager( 4003): HtcTagManager construction complete
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/BluetoothInputDevice( 4003): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 14
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/BluetoothInputDevice( 4003): BluetoothInputDevice(): Binding service...
,W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 4003): BluetoothPan()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 15
D/RingtoneManager( 4153): getExternalStorageState=mounted
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/BluetoothPan( 4003): BluetoothPan(): Binding service...
,D/BluetoothMap( 4003): Create BluetoothMap proxy object
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 16
,E/BluetoothMap( 4003): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothSap( 4003): BluetoothSap() call bindService
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 17
W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,D/BluetoothPbap( 4003): BluetoothPbap()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 18
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/BluetoothPbap( 4003): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 4003): BluetoothA2dp()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[-1]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[2]: Feverfew
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[5]: Hangouts Message
,D/BluetoothManagerService(  907): Registered receivers: 19
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[7]: Licorice
W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[12]: Tulip
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
D/BluetoothA2dp( 4003): BluetoothA2dp(): Binding service...
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4153):  + mAlertUri: content://settings/system/alarm_alert
,D/BluetoothHeadset( 4003): BluetoothHeadset()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 20
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
D/BluetoothHeadset( 4003): BluetoothHeadset(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4153): BleProfilesStateMachine is initialized...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4153): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4153): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4153): initScanModeInterface: true
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4153): loadDeviceConfiguration() init =true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4153):  + mTag.getPrimaryDeviceList() = []
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/[HTC_BLE][Constants]( 4153):  + defaultServices = 0
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426267c0:true
,D/[HTC_BLE][Constants]( 4153):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4153):  + discoverServicesOnBonded = false
W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,D/HtcTagManager( 4003): startProxy
,W/ContextImpl( 4003): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4153): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41be7208
,D/LocalBluetoothProfileManager( 4003): LocalBluetoothProfileManager construction complete
W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
D/LocalBluetoothProfileManager( 4003): setBluetoothStateOn
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
D/HtcTagManager( 4003): startProxy
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
D/BluetoothAdapterService(1102930424)( 4084): Get Bonded Devices being called
D/BluetoothAdapterProperties( 4084): getBondedDevices: length=6
D/BluetoothAdapter( 4003): getBluetoothService(): entry
D/BluetoothAdapter( 4003): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 4003): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41c22a60
D/BluetoothDevice( 4003): getService : Register callback
E/BluetoothDevice( 4003): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/HtcTagManager( 4003): addHtcTagProfiles
,E/BluetoothDevice( 4003): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/HtcTagManager( 4003): addHtcTagProfiles
,E/BluetoothDevice( 4003): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/HtcTagManager( 4003): addHtcTagProfiles
,E/BluetoothDevice( 4003): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/HtcTagManager( 4003): addHtcTagProfiles
,E/BluetoothDevice( 4003): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/HtcTagManager( 4003): addHtcTagProfiles
,E/BluetoothDevice( 4003): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/HtcTagManager( 4003): addHtcTagProfiles
,D/BluetoothInputDevice( 4003): Proxy object connected
D/HidProfile( 4003): Bluetooth service connected
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/BluetoothPan( 4003): BluetoothPAN Proxy object connected
,D/PanProfile( 4003): Bluetooth service connected
D/SapServerProfile( 4003): Bluetooth service connected
D/BluetoothPbap( 4003): Proxy object connected
D/PbapServerProfile( 4003): Bluetooth service connected
D/BluetoothA2dp( 4003): Proxy object connected
,D/A2dpProfile( 4003): Bluetooth service connected
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/BluetoothHeadset( 4003): Proxy object connected
,D/HeadsetProfile( 4003): Bluetooth service connected
,D/BluetoothAdapter( 4003): 1103008616: getState(). Returning 12
,D/HtcTagManager( 4003): onServiceConnected
D/HtcTagProfile( 4003): setup proxy
D/HtcPxpProfile( 4003): setup proxy
,D/HtcFmpProfile( 4003): setup proxy
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4144): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(42b6dfa0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4144): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1758/10178)
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19404 delay=15s
,D/WifiWatchdogStateMachine(  907): WAN detection
,D/WISPrService( 3822): >>>>>WISPrService start isConnected = true<<<<<
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/MDST    (  907): default: setTeardownRequested(true)
,D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  366): *************************
D/libc    (  366): *** DNS CACHE FLUSHED ***
D/libc    (  366): *************************
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@424f55c8
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  366): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(42e1dcd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1112): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,I//system/bin/ip(  366): RTNETLINK answers: No such file or directory
,I/logwrapper(  366): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  366): RTNETLINK answers: No such process
,I/logwrapper(  366): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42e1dcd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4277 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(426239b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/ConnectivityHelper( 1249): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1249/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1431/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (3933/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1758/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3519/10051)
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =cad8 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1776/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (3933/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42449ec0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/PMS     (  907): acquireWL(43bbf300): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 907 1000 WorkSource{10096}
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4295 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  907): releaseWL(43bbf300): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 121
D/libc    (  366): [NET]res_nsend:resplen=104
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
,I/MusicStore( 4277): Database version: 95
,W/ContextImpl( 4277): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  907): acquireWL(426cd188): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 907 1000 WorkSource{10096}
D/PMS     (  907): acquireWL(44140e98): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 907 1000 WorkSource{10160}
,D/PMS     (  907): acquireWL(4250bb38): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.games.background/com.google/***** 0x1 907 1000 WorkSource{10028}
,D/GpsLocationProvider(  907): [handleMessage] INJECT_NTP_TIME
,D/PMS     (  907): releaseWL(42449ec0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =bcf6 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
,D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,D/PMS     (  907): releaseWL(42c63ba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/wpa_supplicant( 4144): WiFioffload: SignalStrength: =97
,D/PMS     (  907): acquireWL(425036f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907):    returned true
,I/IntentController( 1112): receive(android.intent.action.TIME_SET,4,false)
,D/PMS     (  907): releaseWL(425036f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,I/FeedActionBar( 1249): updateLastUpdatedTime(in String) LAST UPDATED 12:00
D/PMS     (  907): acquireWL(440779b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/DotMatrix( 1559): [EventService] EVENT_RESET_THEME_TIMESTAMP
,E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/DotMatrix( 1559): [EventService] isTheSameDay:false,timestamp is early than today:true
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(440779b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/ContextImpl( 4277): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42c63ba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/GpsLocationProvider(  907): NTP server returned: 1452596499153 (Tue Jan 12 12:01:39 CET 2016) reference: 107527 certainty: 17 system time offset: 2
,D/GpsLocationProvider(  907): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  907): releaseWL(426239b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/GamesSyncAdapter( 1203): User is not G+ enabled. Aborting sync
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4289e9a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/DelayedSyncController( 4295): Delaying sync.
D/PMS     (  907): releaseWL(4289e9a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42651100): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(426cd188): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42651100): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43dd43d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(44140e98): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/PMS     (  907): acquireWL(43d4e538): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 907 1000 WorkSource{10096}
,D/PMS     (  907): releaseWL(43dd43d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4277, uid=10154, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(421c2798): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/DelayedSyncController( 4295): Delaying sync.
D/PMS     (  907): releaseWL(421c2798): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43ef89f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(43d4e538): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  907): releaseWL(43ef89f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(437e2688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(4250bb38): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.games.background/com.google/***** 0x1 WorkSource{10028}
D/PMS     (  907): releaseWL(437e2688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4277): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 4277): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4277/10154)
,I/NetworkMonitor( 4277): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4327 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4277): getSelectedRoute
,I/NetworkMonitor( 4277): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4277/10154)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=1361
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 1361:com.htc.sense.hsp/u0a53 (adj 15): empty #17
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4277, uid=10154, userID:0
,I/ActivityManager(  907): Recipient 1361
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 4327): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4327): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4327): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/SensorManager(  907): mEventCount = 1500
,W/SystemClassLoaderAdder( 4327): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4327): Preparing secondary program dexes.
,V/DexLibLoader( 4327): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4327): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4327): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4327): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4327): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4327): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4327): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4327): Dex already copied
D/OdexVerifier( 4327): Odex verification is skipped.
,V/DexLibLoader( 4327): Creating class loader
,V/DexLibLoader( 4327): Finished creating class loader,
V/DexLibLoader( 4327): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4327): Dex already copied
D/OdexVerifier( 4327): Odex verification is skipped.
,V/DexLibLoader( 4327): Creating class loader,
,V/DexLibLoader( 4327): Finished creating class loader,
V/DexLibLoader( 4327): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4327): Dex already copied
D/OdexVerifier( 4327): Odex verification is skipped.
,V/DexLibLoader( 4327): Creating class loader,
,V/DexLibLoader( 4327): Finished creating class loader,
V/DexLibLoader( 4327): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4327): Dex already copied
D/OdexVerifier( 4327): Odex verification is skipped.
,V/DexLibLoader( 4327): Creating class loader,
,V/DexLibLoader( 4327): Finished creating class loader
,V/DexLibLoader( 4327): Verifying classes from secondary dexes.
,D/DexLibLoader( 4327): DexLibLoader.ensureDexLoaded took 92 ms
,W/dalvikvm( 4327): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4327): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4327): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4327): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4327): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4327): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4327): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/BTIF_CORE( 4084): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 4084): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 4084): Wake lock released,
,W/dalvikvm( 4327): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4327): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4327): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4327): Verify
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =b14f +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET] NOT IN CACHE
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4327): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4327): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  366): [NET]res_nsend:resplen=172
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,I/dalvikvm-heap( 4327): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  907): Disable JIT of com.htc.bgp
,D/Process (  907): killProcessQuiet, pid=3933
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4347 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
I/ActivityManager(  907): Killing 3933:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/CalendarProvider2( 4347): Created com.android.providers.calendar.CalendarAlarmManager@41c03908(com.android.providers.calendar.HtcCalendarProvider@41bebc90)
,D/CalendarProvider2( 4347): wait start:true
,D/CalendarProvider2( 4347): wait end:false
D/PMS     (  907): acquireWL(4316c750): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1203 10028 null
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3933
,D/PMS     (  907): acquireWL(43907418): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4316c750): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,W/fb4a(:<default>):UserScope( 4327): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4327): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,D/PMS     (  907): releaseWL(43907418): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1350): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
,W/fb4a(:<default>):UserScope( 4327): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    ( 1350): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1350): [NET] getaddrinfo-,err=8
D/libc    ( 1350): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1350): [NET] getaddrinfo-, 1
,D/libc    ( 1350): [NET] getaddrinfo_proxy+
,D/libc    (  366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
,D/PMS     (  907): acquireWL(42cd8d20): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1350 10028 null
D/libc    (  366): [NET] +++++ res_nsend xid =7cf4 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,I/ActivityManager(  907): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4370 uid=10053 gids={50053, 1023, 3003, 5012}
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4327): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 197
D/libc    (  366): [NET]res_nsend:resplen=79
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1350): [NET] getaddrinfo_proxy-, success
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/libc    ( 1350): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1350): [NET] getaddrinfo-,err=8
W/ActivityThread( 1350): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
,D/PMS     (  907): acquireWL(440d5bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10028 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
,D/PMS     (  907): releaseWL(440d5bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/dalvikvm( 4327): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4327): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4327): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4327): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4327): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4327): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4327): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4327): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4327): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4327): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4327): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4327): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/dalvikvm( 4327): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4327): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/dalvikvm( 4327): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4327): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4327): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4327): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/PluginProvider( 4370): PluginProvider onCreate
,D/PluginProvider( 4370): current plugin count: 19
,D/HtcAppUPService( 4370): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4327): Grow heap (frag case) to 9.924MB for 39954-byte allocation
,D/GCM     ( 1350): Connected
D/PMS     (  907): acquireWL(43c6f090): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1350 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
D/PMS     (  907): releaseWL(42cd8d20): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1350/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
D/PMS     (  907): releaseWL(43c6f090): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(43bcce20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1350 10028 null
,I/dalvikvm-heap( 4327): Grow heap (frag case) to 10.000MB for 79892-byte allocation
,D/AutoSetting( 4370): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4388 uid=10078 gids={50078, 3003, 5012}
,I/dalvikvm-heap( 4327): Grow heap (frag case) to 10.074MB for 84664-byte allocation
D/Process (  907): killProcessQuiet, pid=3954
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/GCM     ( 1350): Message class mpf
I/ActivityManager(  907): Killing 3954:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4370/10053)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1350/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1350/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
,D/PMS     (  907): releaseWL(43bcce20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/ActivityManager(  907): Recipient 3954
,D/AutoSetting( 4370): service - onCreate()
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(43829178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10028 null
D/PMS     (  907): releaseWL(43829178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,D/AutoSetting( 4370): service - AddressCache: using context: com.htc.Weather
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4219d6c8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4219d6c8, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42362db0
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@421c31d0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  907): Going to sleep due to screen timeout...
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,I/dalvikvm-heap( 4327): Grow heap (frag case) to 10.098MB for 28144-byte allocation
,W/PMS     (  907): mWirelessDisplayManager is null
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
D/AutoSetting( 4370): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/LocationManagerService(  907): request 42654880 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 4370): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 4370): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4370): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4370/10053)
,D/MobileConnectivityChangeReceiver( 4388): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4388): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4388): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4388): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4388/10078)
,D/PMS     (  907): acquireWL(41c02e28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1203 10028 null
,I/DeviceManagement( 3920): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4388/10078)
D/PMS     (  907): acquireWL(440de4b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1203 10028 null
D/PMS     (  907): releaseWL(41c02e28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4388/10078)
,I/DeviceManagement( 3920): WorkflowService: Starting workflow service
,I/DeviceManagement( 3920): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41d9a6b8] args=[Bundle[mParcelledData.dataSize=804]]
,I/CheckinService( 1203): Preparing to send checkin request
,I/EventLogService( 1203): Accumulating logs since 1452595921234
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4408 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [10][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
,I/DeviceManagement( 3920): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 3920): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
,I/DeviceManagement( 3920): NetworkChangeWorkflow: ==================================================
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
I/DeviceManagement( 3920): SessionStateController: Checking invariants...
,I/DeviceManagement( 3920): BackgroundController: Invariants are unchanged.
,I/dalvikvm-heap( 4327): Grow heap (frag case) to 10.282MB for 75760-byte allocation
,I/DeviceManagement( 3920): Perf: *** Cache update - start...
,I/DeviceManagement( 3920): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 3920): EnabledAppController: *** Updating enabled app database...
,I/DeviceManagement( 3920): Perf: *** Enabled app cache update - complete: 2 ms
I/DeviceManagement( 3920): Perf: *** Config cache update - start...
,I/DeviceManagement( 3920): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 3920): ConfigCacheController: *** Updating stale config cache entries...
,W/EventLogAggregator( 1203): Unknown tag: install_package_attempt
W/EventLogAggregator( 1203): Unknown tag: snet
,W/EventLogAggregator( 1203): Unknown tag: snet_gcore
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44102890 u0 ReceiverList{44102528 4327 com.facebook.katana/10026/u0 remote:440dd6b0}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b453f8 u0 ReceiverList{437fc788 4327 com.facebook.katana/10026/u0 remote:4266aad0}}
,W/dalvikvm( 3920): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
W/dalvikvm( 3920): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 3920): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
,I/GoogleHttpClient( 1203): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1203): Using GMS GoogleHttpClient
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,W/System.err( 3920): Starting the internal HTTP client
,I/DeviceManagement( 3920): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
D/PMS     (  907): acquireWL(431d7978): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1431 10028 null
D/PMS     (  907): releaseWL(431d7978): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1203/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1224): notify MmsSms
D/AccFlag ( 1224): sense_version=6.0
,D/AccFlag ( 1224): sku_id=99
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1203/10028)
,D/GCoreFlp( 1431): Unknown pending intent to remove.
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(42564718): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1431 10028 null
D/PMS     (  907): releaseWL(42564718): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,I/DeviceManagement( 3920): DeviceClientResource: Active network...
I/DeviceManagement( 3920):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/BuildInfo( 3920): Created new instance: com.htc.cs.lib.hms.BuildInfo@41eba0b8
,I/DeviceManagement( 3920): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc    ( 3920): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3920): [NET] getaddrinfo-, 1
D/libc    ( 3920): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3920): [NET] getaddrinfo_proxy-, success
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4327): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4327): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,W/CheckinRequestBuilder( 1203): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{4203b368 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 3920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
,D/libc    ( 3920): [NET] getaddrinfo-,err=8
D/libc    ( 3920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3920): [NET] getaddrinfo-, 1
D/libc    ( 3920): [NET] getaddrinfo_proxy+
,D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =5e15 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 8 2 12
D/WIFI_ICON( 1112): WifiActivity: 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 406ms
D/NfcService( 1235): ScreenObserver: OFF
,D/NfcService( 1235): applyRouting - 0
I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): OOBE c monitor 11
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4038
D/NfcService( 1235): applyRouting -2
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43722b08)
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): acquireWL(435f89c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1235 1027 null
D/PMN     (  907): wakingUp
D/PMS     (  907): releaseWL(435f89c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMN     (  907): onScreenOn
D/PMS     (  907): acquireWL(43d35210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43d35210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  366): [NET]res_nsend:resplen=204
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3920): [NET] getaddrinfo_proxy-, success
D/MtpService( 2180): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1235): applyRouting - 0
,D/MtpService( 2180): [MTP][onReceive]-
,D/NfcService( 1235): applyRouting -2
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): acquireWL(43ad4c98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1235 1027 null
D/PMS     (  907): releaseWL(43ad4c98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19405 delay=15s
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): SET_SCREEN_ON:On
I/wpa_supplicant( 4144): htc_wext_set_keepalive +
I/wpa_supplicant( 4144): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4144): getPrivFuncNum +	
I/wpa_supplicant( 4144): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4144): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4144): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4144): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4144): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  907):    returned true
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms,
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
I/ClockThread( 1112): stop update clock
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=33 [3][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4408): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
V/SRS_Proc(  373): ParamSet string: screen_state=on
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4144): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4408): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/NetworkPolicy(  907): updateScreenOn: false
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [2][0][0]
,W/GAV2    ( 4408): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4440 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/ContextImpl( 4408): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4408): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,W/Vold    (  356): Returning OperationFailed - no handler for errno 30
I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(42e03878): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,D/PMS     (  907): releaseWL(42e03878): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/MultiDex( 4440): install
I/MultiDex( 4440): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4153): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4153): onScreenOn: 1452596502170
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4153): onScreenOn: 1452596502170
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42362db0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42362db0, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@421c31d0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/MultiDex( 4440): loading existing secondary dex files
,D/PMN     (  907): goingToSleep
,I/MultiDex( 4440): load found 1 secondary dex files
,I/MultiDex( 4440): install done
D/PMS     (  907): acquireWL(42c5bc50): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/CalendarProvider2( 4347): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4347): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19405 mDataStallAlarmIntent=PendingIntent{42173f60: PendingIntentRecord{425a8900 android broadcastIntent}}
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4144): SET_SCREEN_ON:Off
I/wpa_supplicant( 4144): htc_wext_set_keepalive +
I/wpa_supplicant( 4144): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4144): getPrivFuncNum +	
I/wpa_supplicant( 4144): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4144): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4144): get_ip_address source addr = c0a80176
I/wpa_supplicant( 4144): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 4144): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/PMS     (  907): acquireWL(439f2ca0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/NetworkPolicy(  907): updateScreenOn: false
,D/wpa_supplicant( 4144): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,I/ProviderInstaller( 4440): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(439f2ca0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [3][0][0]
,D/ContactMessageStore( 1224): start background delete task...
D/ContactMessageStore( 1224): size: 0 , 0
,D/ContactMessageStore( 1224): Background delete complete
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4408/10151)
,V/WebViewChromiumFactoryProvider( 4408): Binding Chromium to main looper Looper (main, tid 1) {41bbf490}
,I/LibraryLoader( 4408): Expected native library version number "",actual native library version number ""
,I/chromium( 4408): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4408): Initializing chromium process, renderers=0
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): acquireWL(43804378): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,E/AudioManagerAndroid( 4408): BLUETOOTH permission is missing!
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4153): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4153): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4153): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4153): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4153): onScreenOff
,D/AutoSetting( 4370): service - mHandler: cancel location update
D/PMS     (  907): acquireWL(438432e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): releaseWL(43804378): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  907): acquireWL(44083f88): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,D/PMS     (  907): releaseWL(438432e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/AutoSetting( 4370): service -           changes count: 0
I/Adreno-EGL( 4408): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4408): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4408): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4408): Local Branch: 
I/Adreno-EGL( 4408): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4408): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4408):                  aa63bbd948f41d15fc72f585e
I/GoogleHttpClient( 4440): Falling back to old SSLCertificateSocketFactory
,I/NSApplication( 4408): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4408/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4408/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3803/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3803/10160)
,D/Process (  907): killProcessQuiet, pid=3971
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Killing 3971:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/libc    ( 4440): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4440): [NET] getaddrinfo-,err=8
D/libc    ( 4440): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4440): [NET] getaddrinfo-, 1
,D/libc    ( 4440): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  366): [NET] +++++ res_nsend xid =7ccd +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/AlertReceiver( 3989): beginStartingService
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1758/10178)
,I/ActivityManager(  907): Recipient 3971
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4340b108): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3989 10013 null
,D/PMS     (  907): acquireWL(4370c3b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4370c3b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 283
D/libc    (  366): [NET]res_nsend:resplen=86
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4440): [NET] getaddrinfo_proxy-, success
,D/AlertService( 3989): start to updateAlertNotification!
,I/DeviceManagement( 3920): DMServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3920): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3920): DeviceClientResourceController: handleDirectives: []
,W/dalvikvm( 3920): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 3920): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 3920): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3920): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3920): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 3920): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3920): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3920): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
,W/dalvikvm( 3920): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3920): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 3920): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3920): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
,W/dalvikvm( 3920): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3920): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 3920): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
D/AlertService( 3989): No fired or scheduled alerts
D/HtcAlertUtils( 3989): -- cancelReminderNotification --
,W/dalvikvm( 3920): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
W/dalvikvm( 3920): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,D/HtcAlertUtils( 3989): broadcastExistReminder!
I/System.out( 3920): isCompatible false
I/System.out( 3920): createObjectMapper
I/System.out( 3920): isCompatible false
,I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
,I/System.out( 3920): isCompatible false
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(4340b108): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/AlertReceiver( 3989): stopSelfResult true
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4488 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,W/WeatherRequest( 1112): request cur loc, but there is no sys cur
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4504 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4488): can't get weather sync account
D/libc    ( 4440): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4440): [NET] getaddrinfo-,err=8
,W/WeatherRequest( 4488): request cur loc, but there is no sys cur
,W/Settings( 4488): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  907): acquireWL(42c6a540): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4504 10070 null
D/PMS     (  907): acquireWL(43771ec0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4504 10070 null
,I/DeviceManagement( 3920): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
D/PMS     (  907): releaseWL(42c6a540): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4519 uid=10090 gids={50090, 3003, 5012, 1028}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
,I/DeviceManagement( 3920): DeviceClientResource: Active network...
I/DeviceManagement( 3920):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/TodoTaskshortcut( 4504): update TASK shortcut>
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=25 [12][3][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
,D/libc    ( 3920): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3920): [NET] getaddrinfo-, 1
,D/libc    ( 3920): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3920): [NET] getaddrinfo_proxy-, success
,I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 1 9 17
,I/TodoTaskNotifyService( 4504): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/libc    ( 3920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3920): [NET] getaddrinfo-,err=8
D/libc    ( 3920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3920): [NET] getaddrinfo-, 1
,D/libc    ( 3920): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =25c9 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3920): [NET] getaddrinfo_proxy-, success
,I/TodoTaskNotifyService( 4504): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(43c9e480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10028 null
D/PMS     (  907): releaseWL(43c9e480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/NotifyReceiver( 4504): stopSelfResult true
,I/WorldClock.Global( 4519): isHtcDevice = true
D/PMS     (  907): releaseWL(43771ec0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  907): Killing 3683:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3683
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/WorldClock.Global( 4519): isHtcDevice = true
W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4519): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 4519): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4519): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/ActivityManager(  907): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4536 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/IntentController( 1112): receive(android.intent.action.ALARM_CHANGED,1,false)
,W/ActivityManager(  907): Activity pause timeout for ActivityRecord{421c20e8 u0 com.test.thalitest/.MainActivity t2}
,I/ActivityManager(  907): Recipient 3683
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TimeService( 4536): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452596502765
,D/Process (  907): killProcessQuiet, pid=3767
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3767:com.android.vending/u0a73 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=4188
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4188:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/GCM     ( 1350): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.gcm.ServiceAutoStarter
I/ActivityManager(  907): Recipient 4188
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4440/10028)
,I/DeviceManagement( 3920): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3920): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3920): DeviceClientResourceController: handleDirectives: []
I/System.out( 3920): isCompatible false
,I/System.out( 3920): createObjectMapper
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
,I/System.out( 3920): isCompatible false
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3767
,I/DeviceManagement( 3920): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/DeviceManagement( 3920): DeviceClientResource: Active network...
I/DeviceManagement( 3920):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3920/10098)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=7 [26][2][0]
D/libc    ( 3920): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3920): [NET] getaddrinfo-, 1
D/libc    ( 3920): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3920): [NET] getaddrinfo_proxy-, success
D/libc    ( 3920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3920): [NET] getaddrinfo-,err=8
D/libc    ( 3920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3920): [NET] getaddrinfo-, 1
D/libc    ( 3920): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =2f8 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3920): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4440): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4440): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4440): Local Branch: 
I/Adreno-EGL( 4440): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4440): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4440):                  aa63bbd948f41d15fc72f585e
,I/DeviceManagement( 3920): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3920): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3920): DeviceClientResourceController: handleDirectives: []
I/System.out( 3920): isCompatible false
I/System.out( 3920): createObjectMapper
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
I/System.out( 3920): isCompatible false
,I/System.out( 3920): isCompatible false
,I/Adreno-EGL( 4440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4440): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4440): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4440): Local Branch: 
I/Adreno-EGL( 4440): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4440): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4440):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4440): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4440): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4440): Local Branch: 
I/Adreno-EGL( 4440): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4440): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4440):                  aa63bbd948f41d15fc72f585e
,I/DeviceManagement( 3920): ConfigCacheController: *** Update config cache: updating 3 entries...
,I/DeviceManagement( 3920): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,W/Settings( 4440): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/DeviceManagement( 3920): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 3920): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 3920): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 3920): AlarmController: Scheduling TTL alarm for: 2016.01.13 at 12:01:43.338 CET (due to: com.htc.launcher)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3920, uid=10098, userID:0
,I/DeviceManagement( 3920): Perf: *** Config cache update - complete: 1708 ms
I/DeviceManagement( 3920): Perf: *** Cache update - complete: 1712 ms
,I/DeviceManagement( 3920): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41d9a6b8]
,I/DeviceManagement( 3920): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4175
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4175:com.htc.widget.process2/u0a48 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4175
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4555 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  907): killProcessQuiet, pid=4110
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4110:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4110
,E/dalvikvm( 4555): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4555): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
I/Babel   ( 4555): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4555): MmsConfig.loadMmsSettings
E/dalvikvm( 4555): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4555): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4555): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4555, uid=10111, userID:0
,W/Settings( 4555): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4578 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4555, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4555, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4555, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4555, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4555, uid=10111, userID:0
,I/ProviderInstaller( 4555): Installed default security provider GmsCore_OpenSSL
,D/MessageFrequencyProvider( 4578): onCreate
,V/GetPrviateResource( 4578): GetPrviateResource
,V/GetPrviateResource( 4578): GetPrviateResource
,D/MmsCustomizationProvider( 4578): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/AutoSetting( 4370): receiver - intent: android.intent.action.USER_PRESENT
,I/jxcore-log( 4038): Test app app.js loaded
I/jxcore-log( 4038): 
,I/Choreographer( 4038): Skipped 561 frames!  The application may be doing too much work on its main thread.
,D/AutoSetting( 4370): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/MmsCustomizationProvider( 4578): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4555/10111)
,W/ResourceType( 4038): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4038): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41bd8358 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/Babel   ( 4555): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4555): MmsConfig.loadFromDatabase
D/TetherSettings( 3822): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3822): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3822): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3822): Cust_ConnectToPC   : spcsc>false
D/        ( 3822): Cust_ConnectToPC   : IPT>true
,D/        ( 3822): Cust_ConnectToPC   : Singel_USB>false
,D/PMS     (  907): releaseWL(42c5bc50): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/Settings( 3822): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3822): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3822): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3822): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/chromium( 4038): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/Babel   ( 4555): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4555): MmsConfig.loadFromResources
E/Babel   ( 4555): canonicalizeMccMnc: invalid mccmnc nullnull
I/PSReceiver( 3822): onReceive:android.intent.action.USER_PRESENT
,I/Babel   ( 4555): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3822): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3822): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3822):  defaultType:0
I/ActivityManager(  907): Delay finish: com.android.settings/.PSReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4555/10111)
I/ActivityManager(  907): Resuming delayed broadcast
D/MessageCustFlag( 4578): sense_version=6.0
D/BTAccessoryUtil( 4578): createReceiver
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4602 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  907): killProcessQuiet, pid=4128
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/BTAccessoryUtil( 4578): registerReceiver return intent = null
I/ActivityManager(  907): Killing 4128:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/MessageCustFlag( 4578): sku_id=99
W/SystemReader( 4578): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  907): Recipient 4128
D/Messaging( 4578): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4578): networkCode: 
D/MessageCustFlag( 4578): sku_id=99
D/MmsConfig( 4578): SIE smsPri: null
D/MmsConfig( 4578): networkCode: 
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcTelephonyCapability( 4578): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4578): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4578): getRATByHtcTelephonyCapability:1
W/SystemReader( 4578): Cannot find qct_8960_interface, use default value instead
,W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,I/CheckinTask( 1203): Sending checkin request (9146 bytes)
W/ContextImpl( 4602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/ActivityThread( 1203): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,D/SmartSyncUtils( 4602): isEpsOn(), nState = 0
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  907): acquireWL(43553780): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4602 1000 null
,E/Babel   ( 4555): UserRecoverableAuthException.
,E/Babel   ( 4555): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4555): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4555): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4555): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4555): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4555): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4555): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4555): Error getting auth token
,E/Babel   ( 4555): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4555): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4555): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4555): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4555): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4555): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4555): Account registration failedRedacted-21
E/Babel   ( 4555): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4555): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4555): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4555): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4555): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4555): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4555): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4555): Account sign in complete with state 106account: Redacted-21
D/libc    ( 1203): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1203): [NET] getaddrinfo-,err=8
D/libc    ( 1203): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1203): [NET] getaddrinfo-, 1
,D/libc    ( 1203): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =2853 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4555/10111)
D/PMS     (  907): releaseWL(43553780): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4602): getMobilePolicyEnabled, result = true
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=4277
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4277:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/ProviderChangeReceiver( 3989): ---------------------------------------------------
,D/ProviderChangeReceiver( 3989): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3989): start to updateAlertNotification!
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 272
D/libc    (  366): [NET]res_nsend:resplen=84
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1203): [NET] getaddrinfo_proxy-, success
W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/AlertService( 3989): No fired or scheduled alerts
D/HtcAlertUtils( 3989): -- cancelReminderNotification --
D/HtcAlertUtils( 3989): broadcastExistReminder!
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  907): Resuming delayed broadcast
,W/ContextImpl( 4602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Recipient 4277
,D/MediaRouterService(  907): Client com.google.android.music (pid 4277): Died!
,D/SmartSyncUtils( 4602): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4602): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4602): isEpsOn(), nState = 0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
,E/Babel   ( 4555): Unexpected exception while authenticating.
,E/Babel   ( 4555): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4555): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4555): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4555): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4555): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4555): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4555): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4555): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4555): 	at java.lang.Thread.run(Thread.java:864)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/GCM     ( 1350): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@421c31d0
D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@421c31d0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@421c31d0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@421c31d0
I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41c1c3c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1112): com.google.android.gms 6 7 2 12
D/libc    ( 1203): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1203): [NET] getaddrinfo-,err=8
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425501d0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425501d0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(43829178): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4504 10070 null
W/fb4a(:<default>):UserScope( 4327): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4327): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/TodoTaskNotifyService( 4504): java.lang.NullPointerException
W/System.err( 4504): java.lang.NullPointerException
W/System.err( 4504): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4504): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4504): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4504): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  907): acquireWL(43803e08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4504 10070 null
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  907): releaseWL(43829178): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(43803e08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,W/NotifyReceiver( 4504): stopSelfResult true
D/PMS     (  907): acquireWL(437f9db0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4504 10070 null
D/PMS     (  907): acquireWL(437f6070): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4504 10070 null
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4633 uid=10038 gids={50038}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [29][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
D/PMS     (  907): releaseWL(437f9db0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
E/TodoTaskNotifyService( 4504): java.lang.NullPointerException
W/System.err( 4504): java.lang.NullPointerException
W/System.err( 4504): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4504): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4504): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4504): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 4504): stopSelfResult true
D/PMS     (  907): releaseWL(437f6070): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4647 uid=10077 gids={50077}
,D/Process (  907): killProcessQuiet, pid=4327
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4327:com.facebook.katana/u0a26 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4327/10026)
,D/SMSBackup( 4647): Got a database change event
,D/Process (  907): killProcessQuiet, pid=4388
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  907): Killing 4388:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4388
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4327
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): acquireWL(435d6e60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1431 10028 null
,D/PMS     (  907): acquireWL(435d6cd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1431 10028 null
,D/PMS     (  907): releaseWL(435d6e60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(435d6cd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): acquireWL(435b48f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10028 null
,D/PMS     (  907): releaseWL(435b48f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/CheckinResponseProcessor( 1203): From server: 2 gservices updates and 0 deletes
,I/CertBlacklister(  907): Certificate blacklist changed, updating...
,I/CertBlacklister(  907): Certificate blacklist updated
,I/GservicesProvider( 1350): main difference update completed
,I/ActivityManager(  907): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4662 uid=10016 gids={50016, 3003, 5012, 2001}
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1203/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1203/10028)
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [3][0][0]
,W/ContextImpl( 4662): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4662): Update started
,I/ActivityManager(  907): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,I/ActivityManager(  907): Resuming delayed broadcast
W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/UpdateRequestReceiver( 4662): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  907): getAllNetworkInfo called by  (2180/10021)
,W/ContextImpl( 4662): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4662): Update started
D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1203): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
I/ActivityManager(  907): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41c51b70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/DownloadManager( 2180): Download 195 starting
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 9 3 12
D/PMS     (  907): acquireWL(4260b5a8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2180 10021 WorkSource{10016}
D/ConnectivityService(  907): getAllNetworkInfo called by  (2180/10021)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
W/ActivityThread( 2180): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/CheckinTask( 1203): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1203): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
I/ActivityManager(  907): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4662): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/ConnectivityService(  907): getAllNetworkInfo called by  (2180/10021)
E/UpdateRequestReceiver( 4662): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4662): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/Process (  907): killProcessQuiet, pid=4295
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4295:com.android.chrome/u0a96 (adj 15): empty #17
,I/DownloadManager( 2180): Download 196 starting
D/PMS     (  907): acquireWL(435a4988): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2180 10021 WorkSource{10016}
I/ActivityManager(  907): Recipient 4295
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getAllNetworkInfo called by  (2180/10021)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.analytics.internal.GServicesChangedReceiver
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,V/GA-SERVICE( 1203): Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
D/libc    ( 2180): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2180): [NET] getaddrinfo-,err=8
D/libc    ( 2180): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2180): [NET] getaddrinfo-, 1
,D/libc    ( 2180): [NET] getaddrinfo_proxy+
,D/libc    (  366): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =1774 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/libc    ( 2180): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2180): [NET] getaddrinfo-,err=8
D/libc    ( 2180): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2180): [NET] getaddrinfo-, 1
,D/libc    ( 2180): [NET] getaddrinfo_proxy+
,D/libc    (  366): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =dc62 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1203, uid=10028, userID:0
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(43806060): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1203 10028 null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.checkin.CheckinService$Receiver
D/PMS     (  907): releaseWL(440de4b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/PMS     (  907): acquireWL(42b64900): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1203 10028 null
D/PMS     (  907): releaseWL(43806060): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
E/ActivityThread( 1203): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cf72f0 that was originally bound here
E/ActivityThread( 1203): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cf72f0 that was originally bound here
E/ActivityThread( 1203): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1203): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1203): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1203): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1203): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1203): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1203): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1203): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1203): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1203): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1203): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1203): 	at bks.a(SourceFile:298)
E/ActivityThread( 1203): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1203): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1203): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1203): 	at java.lang.Thread.run(Thread.java:864)
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): releaseWL(42b64900): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  366): [NET]res_nsend:resplen=49
D/libc    (  366): [NET]res_queryN: exit 3, ancount=1
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2180): [NET] getaddrinfo_proxy-, success
D/libc    (  366): [NET]res_nsend:resplen=49
D/libc    (  366): [NET]res_queryN: exit 3, ancount=1
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2180): [NET] getaddrinfo_proxy-, success
,I/SystemUpdateService( 1203): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/PMS     (  907): acquireWL(4308a9b0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1203 10028 null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/SystemUpdateService( 1203): cancelUpdate (empty URL)
,I/SystemUpdateService( 1203): active receiver: disabled
I/SystemUpdateService( 1203): cancelUpdate (empty URL)
,I/SystemUpdateService( 1203): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1203, uid=10028, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1203, uid=10028, userID:0
I/ActivityManager(  907): Resuming delayed broadcast
,D/GCM     ( 1350): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/PMS     (  907): releaseWL(4308a9b0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
,D/PMS     (  907): acquireWL(426cb7d8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(426cb7d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/GCM     ( 1350): GCM config loaded
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
I/DownloadManager( 2180): Ignoring Content-Length since Transfer-Encoding is also defined
,D/SystemEventReceiver( 1203): Received GSERVICES_CHANGED broadcast
I/ActivityManager(  907): Resuming delayed broadcast
,I/OcrUtils( 1203): Updating ocr activity enabled=false
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
,I/GCoreUlr( 1431): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=8 [12][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(441384d0): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1431 10028 null
,I/GCoreUlr( 1431): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4710 uid=10031 gids={50031, 3003, 5012}
,D/PMS     (  907): releaseWL(44083f88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,I/DownloadManager( 2180): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2180): Download 196 finished with status SUCCESS
D/PMS     (  907): releaseWL(435a4988): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4710, uid=10031, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4710, uid=10031, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4710, uid=10031, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=4710, uid=10031, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4710, uid=10031, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4710, uid=10031, userID:0
,D/PMS     (  907): acquireWL(43c60520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,D/PMS     (  907): releaseWL(43c60520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  907): acquireWL(43859628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,I/DownloadManager( 2180): Download 195 finished with status SUCCESS
D/PMS     (  907): releaseWL(43859628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  907): releaseWL(4260b5a8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/PMS     (  907): acquireWL(4248b138): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,D/PMS     (  907): releaseWL(4248b138): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  907): acquireWL(42bda3c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,D/PMS     (  907): releaseWL(42bda3c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  907): acquireWL(43f19008): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,I/GCoreUlr( 1431): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1431): Unknown pending intent to remove.
D/PMS     (  907): releaseWL(43f19008): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  907): acquireWL(430d2f58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1431 10028 null
,I/GCoreUlr( 1431): Unbound from all location providers
D/PMS     (  907): releaseWL(430d2f58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  907): releaseWL(441384d0): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,D/PMS     (  907): acquireWL(434f27e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,D/PMS     (  907): releaseWL(434f27e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  907): acquireWL(432cf3d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
,D/PMS     (  907): releaseWL(432cf3d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3920
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3920:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3920
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4734 uid=10078 gids={50078, 3003, 5012}
,E/PhoneMonitor( 4734): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4734): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  907): killProcessQuiet, pid=4408
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4408:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ContactAccountLoggerTas( 2735): canRun() : Opted Out
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4734/10078)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4734/10078)
,I/Search.GservicesUpdateTask( 2735): Updating Gservices keys
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4734/10078)
,I/ActivityManager(  907): Recipient 4408
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4414f878): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1203 10028 null
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
,D/PMS     (  907): acquireWL(44143598): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4414f878): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/Messaging( 4578): mNeedToUpdateDate2 start
,D/MmsConfig( 4578): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4578): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4578): 
D/MmsAsyncWorkHandler( 4578): HM tk = 20001
,D/ReportIndicatorCache( 4578): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4578): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41bd26f8
,I/Messaging( 4578): mccmnc> 
D/DraftCache( 4578): [DraftCache/1] DraftCache.constructor
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
D/DraftCache( 4578): [DraftCache/1] refresh
D/MmsConfig( 4578): networkCode: 
D/Messaging( 4578): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1224):  phoneType = -1
D/MmsSmsV2Provider( 1224): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
I/dalvikvm-heap( 3803): Grow heap (frag case) to 13.620MB for 1821008-byte allocation
D/PhoneStorageUtil( 4578): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4578): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4578): createReceiver
D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1224):  phoneType = -1
D/MmsSmsV2Provider( 1224): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/MessageCustFlag( 4578): sense_version=6.0
D/Jerry   ( 4578): start to preload cursor >>>>>>>
D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1224):  phoneType = -1
D/MmsSmsV2Provider( 1224): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/TelephUtils( 1224): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
V/MmsProvider( 1224): Update uri=content://mms, match=0
,V/MmsProvider( 1224): selection=st=129 AND m_type!=134
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3803, uid=10160, userID:0
,D/PMS     (  907): releaseWL(44143598): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/Messaging( 4578): mNeedToUpdateDate2: false
,D/Messaging( 4578): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4578): TransactionService is going to be woken up.
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1224): sku_id=99
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3803, uid=10160, userID:0
,I/ActivityManager(  907): Delaying start of: ServiceRecord{44084f60 u0 com.htc.sense.mms/.transaction.TransactionService}
D/DraftCache( 4578): [DraftCache/469] rebuildCache
I/ContactAccountLoggerTas( 2735): canRun() : Opted Out
D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1224):  phoneType = -1
I/ContactAccountLoggerTas( 2735): canRun() : Opted Out
,I/dalvikvm-heap( 3803): Grow heap (frag case) to 15.318MB for 1821008-byte allocation
,W/Search.LoginHelper( 2735): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2735): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3803, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3803, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3803, uid=10160, userID:0
,I/ContactAccountLoggerTas( 2735): canRun() : Opted Out
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
I/ContactAccountLoggerTas( 2735): canRun() : Opted Out
,D/MmsSmsV2Provider( 1224):  phoneType = -1
,D/MmsSmsV2Provider( 1224): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4578): ViewCache CreatePreload
,D/Messaging( 4578): ViewCache CreatePreloadOnlyMultipleOpsList
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3803, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3803, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3803, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3803, uid=10160, userID:0
,D/Cust_MMSMS( 4578): _has_set_default_values_2=true
,D/Messaging( 4578): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,V/TransactionService( 4578): 1-Creating TransactionService
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/Jerry   ( 1224): URI_DRAFT
,D/MsgPreferenceUtils( 4578): def_index: 0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3803, uid=10160, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3803, uid=10160, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3803, uid=10160, userID:0
V/TransactionService( 4578): onStartCommand: 1
D/MmsSystemEventReceiver( 4578): unRegisterForConnectionStateChanges
V/TransactionService( 4578): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4578): Loading previous transactions.
D/MsgPreferenceUtils( 4578): globalIndex = 1
D/MsgPreferenceUtils( 4578): phone state: true
D/MsgPreferenceUtils( 4578): sd state: false
D/MsgPreferenceUtils( 4578): vIndex = 0
D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/DraftCache( 4578): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4578): [DraftCache/469] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4578): 
D/MmsAsyncWorkHandler( 4578): HM tk = 20002
D/AccFlag ( 1224): device_type: 1
D/TransactionService( 4578): Force set service start id to 1
V/TransactionService( 4578): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4578): unRegisterForConnectionStateChanges
,V/TransactionService( 4578): Destroying TransactionService
,D/TransactionService( 4578): stopSelfResult: true, mLastHandledServiceId: 1
,I/ActivityManager(  907): Resuming delayed broadcast
D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/AccFlag ( 1224): sku_id=99
V/TransactionService( 4578): 4-Handling incoming message: { when=-7ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/GCM     ( 1350): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/TelephUtils( 1224): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1224): sku_id=99
,I/GCM     ( 1350): GCM config loaded
,D/GCM     ( 1350): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl( 4662): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  907): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/ConnectivityService(  907): getAllNetworkInfo called by  (2180/10021)
,I/DownloadManager( 2180): Download 197 starting
D/PMS     (  907): acquireWL(43d4e3d0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2180 10021 WorkSource{10016}
D/ConnectivityService(  907): getAllNetworkInfo called by  (2180/10021)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/ContextImpl( 4662): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/DownloadManager( 2180): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager(  907): Resuming delayed broadcast
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,I/AdsMeasurementBroadcastReceiver( 1203): Reporting settings might have changed, alerting AdsMeasurementService
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getAllNetworkInfo called by  (2180/10021)
,D/AdsMeasurementBroadcastReceiver( 1203): Unauthorized to start the main service
,D/GCM     ( 1350): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DownloadManager( 2180): Download 198 starting
D/PMS     (  907): acquireWL(4246dbb8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2180 10021 WorkSource{10016}
D/ConnectivityService(  907): getAllNetworkInfo called by  (2180/10021)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2180): Download 197 finished with status SUCCESS
D/PMS     (  907): releaseWL(43d4e3d0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/DownloadManager( 2180): Ignoring Content-Length since Transfer-Encoding is also defined
,W/ContextImpl( 4662): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=6 [31][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2180/10021)
,I/ActivityManager(  907): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=0 [0][0][0]
I/UpdateFetcherService( 4662): Update downloaded, starting installation
I/UpdateFetcherService( 4662): Started installation
,I/ActivityManager(  907): Resuming delayed broadcast
,I/DownloadManager( 2180): Download 198 finished with status SUCCESS
D/PMS     (  907): releaseWL(4246dbb8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/DownloadManager( 2180): Download 198 already finished; skipping
,W/ContextImpl( 4662): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4662): Update downloaded, starting installation
,I/UpdateFetcherService( 4662): Started installation
I/ActivityManager(  907): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ConfigUpdateInstallReceiver(  907): Not installing, new version is <= current version
,D/Process (  907): killProcessQuiet, pid=3519
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3519:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3519
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=4488
,I/ActivityManager(  907): Killing 4488:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4488
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4555, uid=10111, userID:0
,D/Process (  907): killProcessQuiet, pid=4519
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4519:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4519
,I/dalvikvm-heap( 3803): Grow heap (frag case) to 17.065MB for 1821008-byte allocation
,I/GAV2    ( 3803): Thread[GAThread,5,main]: No campaign data found.
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1249): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.htc.cs.dm
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/Launcher( 1249): Deferring update until onResume
,D/Launcher( 1249): waitUntilResume // bindAppsUpdated
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,D/PackageBroadcastService( 1203): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,D/AutoSetting( 4370): service - mRequestRunnable: screen on delay 10s, request NLP now
,I/[PluginManager]RegisterService( 4370): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 4370): handle notify Blinkfeed plugin client changed
D/AutoSetting( 4370): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4370): service - requestNLP() NetworkLocationProvider not enabled
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(440cf5d8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/PeopleContactsSync( 1203): CP2 sync disabled
,D/PhoneApp( 1224): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
I/ActivityManager(  907): Resuming delayed broadcast
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
D/PMS     (  907): releaseWL(440cf5d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4805 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms",
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4805, uid=10073, userID:0
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,D/Finsky  ( 4805): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
,D/PhoneApp( 1224): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4805/10073)
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4805/10073)
,D/Finsky  ( 4805): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4805): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4805): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4805, uid=10073, userID:0
,D/Finsky  ( 4805): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4805): [1] 2.run: Finished loading 1 libraries.
,D/Process (  907): killProcessQuiet, pid=4536
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4536:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4536
,I/IcingCorporaProvider( 2735): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 4805): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  907): Delaying start of: ServiceRecord{42dcccb0 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(43557da0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3803 10160 null
,D/PMS     (  907): releaseWL(43557da0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4805): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 1203): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PeopleContactsSync( 1203): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
D/PMS     (  907): acquireWL(43176238): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(43176238): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 4370): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 4370): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2735): UpdateCorporaTask done [took 166 ms] updated apps [took 166 ms] 
,I/IcingCorporaProvider( 2735): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(440f8f50): PARTIAL_WAKE_LOCK  AsyncService 0x1 3803 10160 null
,D/PMS     (  907): releaseWL(440f8f50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2735): UpdateCorporaTask done [took 64 ms] updated apps [took 64 ms] 
,W/PackageManager(  907): Unable to load service info ResolveInfo{43805f30 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41c55e98 +
,I/Prism.WidgetManager( 1249): onLoadItems() +
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 1
,W/PackageManager(  907): Unable to load service info ResolveInfo{43cb30d0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PMS     (  907): acquireWL(4397f790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10073}
,V/AlarmManager(  907): sending alarm PendingIntent{421d7e68: PendingIntentRecord{423af968 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452596515508, Int=0
,D/PMS     (  907): releaseWL(4397f790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/PackageSettings(  907): Skipping PackageSetting{4230df78 com.example.hello/10356} due to missing metadata
,W/asset   ( 1249): Copying FileAsset 0x67569198 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1249): onLoadItems() -
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41c55e98 -
,W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4805): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4805): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4805): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4805): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4805): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/PhoneApp( 1224): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1224): -- N1 =0
,D/PhoneApp( 1224): -- N2 =0
,D/PhoneApp( 1224): -- N3 =0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4469f310 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41c55e98 +
,I/Prism.WidgetManager( 1249): onLoadItems() +
,E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1249): onLoadItems() -
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41c55e98 -
,D/PMS     (  907): acquireWL(41ff47a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424446d0: PendingIntentRecord{424441f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=128376, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41ff47a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(424f8ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424f8ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4255d270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41dacf88: PendingIntentRecord{42554680 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=137488, Int=0
,D/PMS     (  907): acquireWL(4247c1b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(4255d270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42ded068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4247c1b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42ded068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(42bf1900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10073}
,V/AlarmManager(  907): sending alarm PendingIntent{428286d0: PendingIntentRecord{4372ad60 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452596530927, Int=0
,D/PMS     (  907): releaseWL(42bf1900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/AutoSetting( 4370): service - mHandler: update timezone
,D/Finsky  ( 4805): [1] 5.onFinished: Installation state replication succeeded.
,D/AutoSetting( 4347): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4347): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4347): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4347): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4347): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4347): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4347): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4347): service - mHandler: update timezone
,D/AutoSetting( 4347): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4347): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4347): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4347): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41d03c88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 3 24 8 11
,D/AutoSetting( 4370): service - handleMessage() stop self
,D/AutoSetting( 4370): service - handleMessage() quit looper
,D/AutoSetting( 4370): service - onDestroy() END
,D/PMS     (  907): acquireWL(4368fce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10028}
,V/AlarmManager(  907): sending alarm PendingIntent{440878f8: PendingIntentRecord{4258cec8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140663, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{4245c8c8: PendingIntentRecord{42596ac8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140798, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{43d028a8: PendingIntentRecord{42dfa758 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452596535012, Int=563223000
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1350/10028)
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(424e49d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10028 null
D/PMS     (  907): acquireWL(432a8fb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(424e49d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  907): acquireWL(4321f570): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4368fce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  907): acquireWL(426bbe50): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1203 10028 null
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
,D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =d86b +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/PMS     (  907): releaseWL(4321f570): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,I/CheckinService( 1203): Preparing to send checkin request
,I/EventLogService( 1203): Accumulating logs since 1452596501780
,W/EventLogAggregator( 1203): Unknown tag: install_package_attempt
W/EventLogAggregator( 1203): Unknown tag: snet
,W/EventLogAggregator( 1203): Unknown tag: snet_gcore
,I/GoogleHttpClient( 1203): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1203): Using GMS GoogleHttpClient
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  366): [NET]res_nsend:resplen=238
D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1203/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1203/10028)
I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4144): environment dirty rate=7 [14][1][0]
,W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1203): awaiting user notification for token
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41f67438 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 9 2 12
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4440/10028)
,I/Adreno-EGL( 4440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4440): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4440): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4440): Local Branch: 
I/Adreno-EGL( 4440): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4440): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4440):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4440): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4440): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4440): Local Branch: 
I/Adreno-EGL( 4440): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4440): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4440):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4440): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4440): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4440): Local Branch: 
I/Adreno-EGL( 4440): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4440): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4440):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4440): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ContactMessageStore( 1224): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1224): MSG_NOTIFY_CS_TO_SYNC <<
,I/CheckinTask( 1203): Sending checkin request (9004 bytes)
,D/libc    ( 1203): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
,D/libc    ( 1203): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1203): [NET] getaddrinfo-, 1
,D/libc    ( 1203): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =f0de +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1203): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1203): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(4370b718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1350 10028 null
,D/PMS     (  907): releaseWL(4370b718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1203/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4144): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4144): nl80211: survey data missing!
E/wpa_supplicant( 4144): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4144): environment dirty rate=0 [39][0][0]
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1203/10028)
,W/GLSUser ( 1350): GoogleAccountDataService.getToken()
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1350): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1350): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1203): awaiting user notification for token
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41f7ba88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 0 9 2 12
,I/CheckinTask( 1203): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1203): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,D/GCM     ( 1350): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): releaseWL(426bbe50): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1203): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d969d0 that was originally bound here
E/ActivityThread( 1203): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d969d0 that was originally bound here
E/ActivityThread( 1203): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1203): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1203): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1203): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1203): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1203): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1203): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1203): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1203): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1203): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1203): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1203): 	at bks.a(SourceFile:298)
E/ActivityThread( 1203): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1203): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1203): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1203): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1350): GCM config loaded
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  907): releaseWL(432a8fb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{44117300 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,D/AutoSetting( 4347): service - handleMessage() stop self
,D/AutoSetting( 4347): service - onDestroy() END
,D/AutoSetting( 4347): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4555
,I/ActivityManager(  907): Killing 4555:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4555
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(440dac48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440dac48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1224): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(437ec528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424446d0: PendingIntentRecord{424441f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=188376, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437ec528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4315d468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4315d468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4396c850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{437fb878: PendingIntentRecord{43cca7a8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230449, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4866 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{426902e0: PendingIntentRecord{42615d38 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452596612078, Int=10800000
,D/PMS     (  907): releaseWL(4396c850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10047}
,D/PMS     (  907): acquireWL(437ff700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{43605cd0: PendingIntentRecord{428a14b8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230451, Int=120000
,D/PMS     (  907): releaseWL(437ff700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4866/10047)
,D/Process (  907): killProcessQuiet, pid=3989
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3989:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3989
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4416e4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4416e4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4264d5f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424446d0: PendingIntentRecord{424441f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=248376, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4264d5f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(437ddf68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(437ddf68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4353d988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4353d988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4038): --= Surplus to requirements =--
I/jxcore-log( 4038): 
I/jxcore-log( 4038): ****TEST TOOK:  ms ****
I/jxcore-log( 4038): 
,I/jxcore-log( 4038): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4038): 
,E/cutils-trace( 4889): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4889): ====startRecUseTime====
D/htc.customization.log.level( 4889):  is 
,W/CustomizationLogLevel( 4889): Level value is invalid, use default level 2
,D/CustomizationManager( 4889):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4889): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4889): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4889): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4889): Parsing tag category name = system
,I/CustomizationCIDLoader( 4889): Parsing tag category name = application
I/CustomizationCIDLoader( 4889): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 4889): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4889): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4889): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4889): Parsing tag category name = Settings
D/CustomizationManager( 4889):  Read CID file spent 0.120 (s)
,D/CustomizationManager( 4889):  All configurations done spent 0.120 (s)
W/HtcNativeFlag( 4889): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4889): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4889): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4889): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4889, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=4038
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907): Killing 4038:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  907):   Force finishing activity ActivityRecord{421c20e8 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x62ac23c8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4038 uid 10348
,E/JavaBinder( 1189): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  907): Skipping PackageSetting{4230df78 com.example.hello/10356} due to missing metadata
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
,I/acms    ( 1776): Unregistering com.test.thalitest
,E/acms    ( 1776): Could not unregister removed application com.test.thalitest
,D/PMS     (  907): acquireWL(42b200b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1431 10028 null
W/GeofencerStateMachine( 1431): Ignoring removeGeofence because network location is disabled.
D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1309): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1309): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(42b200b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,D/VoicemailCleanupService( 1277): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1309): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  907): WIN DEATH: Window{4256fa50 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  907): Client connection lost with reason: 4
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/Launcher( 1249): Deferring update until onResume
,D/Launcher( 1249): waitUntilResume // bindAppsRemoved
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
,D/PackageBroadcastService( 1203): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4904 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/ExternalAccountType( 1309): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/MultiDex( 4904): install
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
,I/MultiDex( 4904): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/MultiDex( 4904): loading existing secondary dex files
I/MultiDex( 4904): load found 1 secondary dex files
I/MultiDex( 4904): install done
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/ActivityManager(  907): Delaying start of: ServiceRecord{44163e58 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,D/PhoneApp( 1224): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4920 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PeopleContactsSync( 1203): CP2 sync disabled
,I/Icing   ( 1203): doRemovePackageData com.test.thalitest
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
D/PMS     (  907): acquireWL(4253f250): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,I/ProviderInstaller( 4904): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(4253f250): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4920): install
,I/MultiDex( 4920): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4920): loading existing secondary dex files
,I/MultiDex( 4920): load found 1 secondary dex files
,I/MultiDex( 4920): install done
,I/ProviderInstaller( 4920): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4003
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4003:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4003
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/[PluginManager]RegisterService( 4370): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 4370): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2735): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4942 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,W/PackageManager(  907): Unable to load service info ResolveInfo{43555d88 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/SQLiteLog( 4904): (3850) statement aborts at 134: [DELETE FROM FileContent24 WHERE hash IN WipeoutFileContentHashView] disk I/O error
,E/SQLiteDBG( 4904): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca37cb0
,E/DocListDatabase( 4904): Failed to delete from FileContent24
E/DocListDatabase( 4904): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4904): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4904): 	at cva.j(SourceFile:1094)
E/DocListDatabase( 4904): 	at chh.run(SourceFile:272)
E/DocListDatabase( 4904): 	at crv.run(SourceFile:48)
E/DocListDatabase( 4904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 4904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 4904): 	at java.lang.Thread.run(Thread.java:864)
,W/dalvikvm( 4904): threadid=12: thread exiting with uncaught exception (group=0x41793e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
E/SQLiteLog( 4904): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4904): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca37cb0
D/PMS     (  907): acquireWL(44124798): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,E/AndroidRuntime( 4904): FATAL EXCEPTION: pool-4-thread-1
E/AndroidRuntime( 4904): Process: com.google.android.gms.drive, PID: 4904
E/AndroidRuntime( 4904): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4904): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4904): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4904): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4904): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4904): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4904): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4904): 	at cva.j(SourceFile:1094)
E/AndroidRuntime( 4904): 	at chh.run(SourceFile:272)
E/AndroidRuntime( 4904): 	at crv.run(SourceFile:48)
E/AndroidRuntime( 4904): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4904): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4904): 	at java.lang.Thread.run(Thread.java:864)
E/DocListDatabase( 4904): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4904): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4904): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4904): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4904): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4904): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4904): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4904): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4904): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4904): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4904): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4904): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4904): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4904): threadid=1: thread exiting with uncaught exception (group=0x41793e30)
D/Process ( 4904): killProcess, pid=4904
,D/Process ( 4904): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
E/AndroidRuntime_2_crash( 4904): crash in the same process: main
E/AndroidRuntime_2_crash( 4904): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime_2_crash( 4904): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime_2_crash( 4904): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime_2_crash( 4904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime_2_crash( 4904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_2_crash( 4904): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime_2_crash( 4904): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime_2_crash( 4904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime_2_crash( 4904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime_2_crash( 4904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime_2_crash( 4904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime_2_crash( 4904): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime_2_crash( 4904): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime_2_crash( 4904): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime_2_crash( 4904): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime_2_crash( 4904): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime_2_crash( 4904): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime_2_crash( 4904): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime_2_crash( 4904): 	at ctj.a(SourceFile:859)
E/AndroidRuntime_2_crash( 4904): 	at cva.k(SourceFile:1117)
E/AndroidRuntime_2_crash( 4904): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime_2_crash( 4904): 	at chr.a(SourceFile:75)
E/AndroidRuntime_2_crash( 4904): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime_2_crash( 4904): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime_2_crash( 4904): 	... 10 more
E/SQLiteLog( 2735): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2735): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x647c94b8
E/IcingCorporaProvider( 2735): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2735): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2735): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2735): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2735): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2735): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2735): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2735): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2735): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2735): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2735): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2735): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2735): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2735): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2735): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2735): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2735): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2735): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2735): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2735): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2735): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2735): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2735): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2735): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2735): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2735): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2735): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2735): 	... 15 more
W/IcingCorporaProvider( 2735): notifyTableChanged failed.
W/IcingCorporaProvider( 2735): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2735): UpdateCorporaTask done [took 147 ms] updated apps [took 147 ms] 
I/ActivityManager(  907): Recipient 4904
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4904) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): releaseWL(44124798): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SQLiteDatabase( 4942): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4942): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4942): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4942): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4942): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4942): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4942): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4942): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4942): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4942): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4942): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4942): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4942): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4942): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4942): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4942): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4942): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4942): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4942): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4942): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4942): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4942): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4942): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4942): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4942): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4942): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4942): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4942): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4942): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4942): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4942): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4942): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4942): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4942): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4942): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4942): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4942): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4942): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4942): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4942): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4942): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4942): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4942): Opened ClientFlag.db in read-only mode,
,E/SQLiteDatabase( 4942): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4942): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4942): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4942): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4942): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4942): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4942): threadid=11: thread exiting with uncaught exception (group=0x41793e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4942): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4942): Process: com.google.android.apps.docs, PID: 4942
E/AndroidRuntime( 4942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4942): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4942): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4942): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4942): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4942): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 4942): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.,
E/SQLiteDatabase( 4942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4942): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4942): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4942): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4942): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4942): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4942): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4942): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4942): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4942): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4942): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4942): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
,E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4942): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
,E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4942): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4942): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
,E/SQLiteOpenHelper( 4942): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4942): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4942): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4942): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4942): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4942): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4942): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4942): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4942): 	,at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4942): Opened ClientFlag.db in read-only mode
D/Process ( 4942): killProcess, pid=4942
,D/Process ( 4942): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4964 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4942
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4942) has died.
,W/ContextImpl( 4964): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4964): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4964): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4964): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4964): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4964): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4964): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4964): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4964): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4964): threadid=10: thread exiting with uncaught exception (group=0x41793e30)
E/AndroidRuntime( 4964): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4964): Process: com.android.keychain, PID: 4964
E/AndroidRuntime( 4964): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849),
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4964): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4964): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4964): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4964): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4964): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4964): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4977 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/PMS     (  907): acquireWL(440dad58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{424446d0: PendingIntentRecord{424441f0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=308376, Int=0
,D/Process ( 4964): killProcess, pid=4964
,D/Process ( 4964): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452596700019.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  907): Recipient 4964
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.keychain (pid 4964) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10556ms
,D/PMS     (  907): releaseWL(440dad58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AppTag  ( 4977): getInstance(Context context)
,D/AppTag  ( 4977): getInstance(Context context)
,D/AppTag  ( 4977): onCreate()
,D/PMS     (  907): acquireWL(42e2be98): PARTIAL_WAKE_LOCK  AsyncService 0x1 3803 10160 null
,D/PMS     (  907): releaseWL(42e2be98): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4995 uid=10098 gids={50098, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=4602
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4602:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/DeviceManagement( 4995): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4995 dbg=false s=true
,I/DeviceManagement( 4995): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4995): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4995): WorkflowService: Starting workflow service
I/DeviceManagement( 4995): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41befe28] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4995): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4995): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4995): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4995): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4995): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4995): SessionStateController: Checking invariants...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5009 uid=10099 gids={50099, 3003, 5012}
,D/Documents( 5009): Loading roots for com.android.providers.downloads.documents
,D/Documents( 5009): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 5009): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5009): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5009): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5009): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5009): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5009): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5009): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5009): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5009): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5009): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5009): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5009): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5009): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5009): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5009): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5009): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5009): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5009): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5009): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 5009): threadid=1: thread exiting with uncaught exception (group=0x41793e30)
I/ActivityManager(  907): Recipient 4602
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
E/AndroidRuntime( 5009): FATAL EXCEPTION: main
E/AndroidRuntime( 5009): Process: com.android.documentsui, PID: 5009
E/AndroidRuntime( 5009): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5009): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5009): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5009): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5009): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5009): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5009): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5009): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5009): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5009): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5009): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5009): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5009): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5009): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5009): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5009): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5009): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5009): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5009): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5009): 	... 10 more
,I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5023 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  907): killProcessQuiet, pid=4504
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Killing 4504:com.htc.task/u0a70 (adj 15): empty #17
,E/ActivityManager(  907): App crashed! Process: com.android.documentsui
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process (  907): killProcessQuiet, pid=4633
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
,D/GCM     ( 1350): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Killing 4633:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4504
,E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452596700330.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 5009): killProcess, pid=5009
,D/Process ( 5009): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Recipient 4633
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 5009
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.documentsui (pid 5009) has died.
,D/GCM     ( 1350): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ExternalStorage( 5023): After updating volumes, found 1 active roots
,E/SQLiteDatabase( 4995): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4995): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4995): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4995): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4995): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4995): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4995): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4995): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4995): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4995): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4995): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4995): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4995): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4995): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4995): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4995): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4995): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4995): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4995): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4995): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4995): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,E/SQLiteDatabase( 4995): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4995): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4995): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4995): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4995): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4995): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4995): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4995): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4995): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4995): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4995): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4995): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 4995): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41befe28]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4995): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4995): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4995): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4995): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4995): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4995): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4995): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4995): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4995): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4995): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 4995): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5039 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 5039): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 5039): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5039): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5039): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5039): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5039): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 5039): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 5039): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 5039): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 5039): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5039): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5039): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 5039): Couldn't open MyDB.db for writing (will try read-only):,
E/SQLiteOpenHelper( 5039): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5039): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5039): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5039): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5039): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 5039): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 5039): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 5039): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 5039): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
E/SQLiteOpenHelper( 5039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5039): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5039): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 5039): Opened MyDB.db in read-only mode
,D/Process (  907): killProcessQuiet, pid=4647
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4647:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41c55e98 +
,I/Prism.WidgetManager( 1249): onLoadItems() +
I/ActivityManager(  907): Recipient 4647
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.gms.drive for service com.google.android.gms/.drive.api.ApiService: pid=5054 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 5054): install
,I/MultiDex( 5054): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)

```
